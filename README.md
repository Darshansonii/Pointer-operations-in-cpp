# Pointer-operations-in-cpp



## Aim

To understand and implement different function calling methods in C++ such as call by value and call by reference, and to perform pointer-based operations like incrementing pointers and reversing strings using pointers.

## Software Used

* **Language:** C++
* **Compiler:** g++ / Turbo C++ / Visual Studio Code with C++ extension
* **Platform:** Any operating system with a C++ compiler

## Theory

### 1. Call by Value

* In call by value, the actual value of an argument is copied into the function’s parameter.
* Any changes made inside the function do not affect the original variable.
* It provides safety since the original variable remains unchanged.
* However, it can be inefficient when passing large data structures because copies are created.
* Example use case: simple arithmetic operations where original values should not be modified.

### 2. Call by Reference

* In call by reference, instead of passing values, the reference (address) of the variable is passed to the function.
* Any change made inside the function directly affects the original variable.
* This method avoids unnecessary copying of large data structures, improving efficiency.
* However, it should be used carefully since unintended modifications may occur.
* Example use case: swapping two variables or updating values inside a function.

### 3. Pointers in Increment

* Pointers can be incremented or decremented to move across memory locations.
* When a pointer is incremented, it moves to the next element of its type (e.g., `int*` moves by 4 bytes in a 32-bit system).
* Pointer arithmetic is widely used in traversing arrays and strings.
* Incrementing pointers is more efficient than using array indexing, as it directly manipulates memory addresses.
* It also provides flexibility in working with continuous blocks of memory.

### 4. Reverse String using Pointers

* A string in C++ is essentially a character array terminated by `'\0'`.
* Using pointers, we can set one pointer at the start of the string and another at the end.
* By swapping characters and moving both pointers inward, the string can be reversed efficiently.
* This approach avoids indexing and directly uses memory manipulation for reversing.
* It demonstrates the power of pointers in handling arrays and strings with minimal overhead.

## Conclusion

This set of concepts highlights two important aspects of C++: **function calling mechanisms** and **pointer-based memory operations**.

* **Call by Value** ensures safety but can be less efficient with large data since it copies values.
* **Call by Reference** provides efficiency and direct modification but must be handled cautiously to avoid unwanted side effects.
* **Pointer Increment** shows how memory can be navigated efficiently without relying on indexing.
* **Reversing Strings with Pointers** demonstrates practical application of pointer arithmetic to manipulate arrays in a memory-friendly way.

In conclusion, mastering both function calling techniques and pointer operations provides a strong foundation for writing efficient, flexible, and optimized C++ programs. These concepts are stepping stones toward understanding advanced topics like dynamic memory allocation, data structures, and system-level programming.

