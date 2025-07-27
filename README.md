This program explores C++'s fundamental data types and demonstrates how to find out how much memory they occupy.

Core Concepts:

Fundamental Data Types: C++ is a statically-typed language, which means you must declare a variable's type before you can use it. This program uses several common types:

int: Used for whole numbers (integers).

float: Used for single-precision floating-point numbers (decimals).

double: Used for double-precision floating-point numbers. It can store larger decimal numbers with much greater precision than float.

string: A special type from the <string> library used to store sequences of characters (text).

The sizeof() Operator: This is a built-in C++ operator that determines the size (in bytes) of a variable or data type. The results can vary slightly depending on the computer's architecture (e.g., 32-bit vs. 64-bit) and the compiler being used.

sizeof(a) where a is an int: Typically returns 4 bytes.

sizeof(b) where b is a float: Typically returns 4 bytes.

sizeof(d) where d is a double: Typically returns 8 bytes, allowing for its higher precision.

sizeof(c) where c is a string: This is a special case. It does not give you the number of characters in the string. Instead, it returns the size of the string object itself, which contains internal information like pointers and capacity management data. The actual text is stored elsewhere in memory.
