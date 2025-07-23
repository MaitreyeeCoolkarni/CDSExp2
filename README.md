# Data Types in C++

Aim: To learn different types of data types in C++  
Apparatus: Programiz / VS Code

---

## Algorithm

1. Include the standard input/output library.  
2. Enable use of standard namespace for simplified name access.  
3. Start the main program.  
4. For each data type (integer, string, float, character, boolean):  
   - Declare a variable of the respective type.  
   - Display the memory size of the variable in bytes using the `sizeof` operator.  
5. End the program with a successful return status.

---

## Theory

In C++, fundamental data types are the basic built-in types provided by the language to store simple kinds of data. These are not derived from other types and are directly supported by the compiler.

### Integer Types (for whole numbers)

- `int`: Standard integer (e.g., 42, -10). Typically 4 bytes  
- `short`: Smaller integer. Typically 2 bytes  
- `long`: Larger integer. At least 4 bytes  
- `long long`: Even larger integer. At least 8 bytes  
- Modifiers: `signed` (default, allows negative) or `unsigned` (non-negative only)

### Floating-Point Types (for decimal numbers)

- `float`: Single-precision floating-point (e.g., 3.14). Typically 4 bytes  
- `double`: Double-precision floating-point (e.g., 3.14159). Typically 8 bytes  
- `long double`: Extended-precision floating-point. Size varies (often 8 or 16 bytes)

### Character Types (for characters)

- `char`: Single character (e.g., 'A', '5'). Exactly 1 byte  
- `wchar_t`: Wide character for extended character sets (e.g., Unicode). Size varies by system

### Boolean Type (for true/false)

- `bool`: Stores `true` or `false`. Typically 1 byte

### Void Type

- `void`: Represents the absence of a type, used in functions (e.g., no return value) or pointers

---

## Sizeof Operator

In C++, the `sizeof` operator is a compile-time unary operator that returns the size (in bytes) of a variable, data type, or expression. It is used to determine how much memory is allocated for a given type or object on a specific system.

**Syntax:**  
```cpp
sizeof(data_type_or_variable)

CONCLUSION:
In this program, we explored the different fundamental data types in C++, such as integers, floats, characters, booleans, and void.
We also used the sizeof operator to understand the amount of memory each type occupies.
This knowledge is essential for efficient memory usage and for writing optimized and portable C++ programs.
