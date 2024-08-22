
## Aim
To explore various data types and their sizes in C++, and to demonstrate the use of storage classes.

## Software Used
- VS Code

## Problem Statements

1. **Display Sizes of Different Data Types**
   - Create a program to show the sizes of various data types in C++.

2. **Demonstrate Static Storage Class**
   - Develop a program to illustrate the behavior of the `static` storage class.

## Theory

### Data Type Sizes

The typical sizes of common data types in C++ are as follows:

- **`int`**: 4 bytes
- **`float`**: 4 bytes
- **`std::string`**: Typically 24 bytes (size may vary by implementation and platform)
- **`char`**: 1 byte
- **`short int`**: 2 bytes

Use the `sizeof` operator to determine the size of these data types in C++.

### Storage Classes

- **`static`**: Used to preserve the value of a variable between function calls or across the entire program lifetime when used globally.

# Program Codes

```javascript

//Mukesh Rothe //23070123089 //CDS EXP 2
#include<iostream>
using namespace std;
int main()
{ 
cout << "Size of Integer is: "   << sizeof(int) <<" bytes"<< endl;
cout << "Size of Float is: "   << sizeof(float) <<" bytes"<< endl;
cout << "Size of String is: "   << sizeof(string) <<" bytes"<< endl;
cout << "Size of Character is: "   << sizeof(char) <<" bytes"<< endl;
cout << "Size of Character is: "   << sizeof(char) <<" bytes"<< endl;
cout << "Size of Short Integer is: "   << sizeof(short int) <<" bytes"<< endl;
}

//Mukesh Rothe //23070123089 //CDS EXP 2
#include<iostream>
using namespace std;
void staticExample(){
int z = 0;
z++;
cout<<"The value of z is: "<<z<<endl;
}
int main(){
staticExample();
staticExample();
return 0;
}
```
# Output:
Sizeof()-

Static-
## Conclusion

- We learned how to use the `sizeof` operator to determine the size of different data types.
- We explored the `static` storage class and its effect on variable persistence.


