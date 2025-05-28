# 📄 ListManipulatorCLI

A command-line C++ program that demonstrates manipulation of a list (`std::list`) using templates and the Standard Template Library (STL). The program supports both `int` and `double` data types and offers a menu-driven interface to perform common list operations.

## Features

- Choose between integer and double list types
- Fill list with random values (1000–2000)
- Calculate sum and average
- Find the first number in range [1500, 1900]
- Divide all numbers by 2
- Swap element positions
- Find minimum and maximum values
- Sort the list
- Clear the list
- Save/load list from a file
- Print list contents

## How to Compile
You must compile all .cpp files and ensure template definitions are included in the same translation unit. One way is to include implementation files at the end of header files or directly in main.cpp.

Example using g++:
```bash
g++ -std=c++17 main.cpp testProgram.cpp menuTestProgram.cpp -o listmanip
```

## How to Run
After compilation:
```bash
./listmanip
```
Follow the menu prompts:

1. Select list type (int or double)

2. Use the menu to perform operations on the list
