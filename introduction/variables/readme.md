# Variables

Variables are containers for storing data values.

In C++, there are different types of variables (defined with different keywords), for example:

- **int** - stores integers (whole numbers), without decimals, such as 123 or -123
- **double** - stores floating point numbers, with decimals, such as 19.99 or -19.99
- **char** - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
- **string** - stores text, such as "Hello World". String values are surrounded by double quotes
- **bool** - stores values with two states: true or false

## Declaring (Creating) Variables

To create a variable, specify the type and assign it a value:
Syntax:
```
type variableName = value;
```
Where type is one of C++ types (such as int), and variableName is the name of the variable (such as x or myName). The equal sign is used to assign values to the variable.

To create a variable that should store a number, look at the following example:
```cpp
int myNum = 15;
cout << myNum; 
```