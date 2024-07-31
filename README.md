# 0x11. C - printf


## Description
Create an simple exact replica of the printf function found in the C programming language. Using Variadic functions, structs, and multiple helper functions, the program we created will be able display inputed characters, strings, integers, and decimals (base 10). Whatever format specifier you use with our `_prinf` function, should display the same results when used by the actual printf function. This project is to show an alternative method of creating your very own simple printf function in the C programming language.

If successfully compiled and executed, the function should return the number of characters printed (excluding the null byte used to end output to strings). And if it fails, then the function should return a `(-1)` upon error and `"(null)"` if the string argument takes in NULL. If the format specifier is unkown, then the output would print out the format specifier as a string.

The code was made to handle all the format specifiers, but because of the simplicity of our code, we only used 5 so far.

### Prototype
`int _printf(const char *format, ...)`

- Returns: the number of characters printed (excluding the null byte used to end output to strings).
- Write output to stdout, the standard output stream.
- `format` is a character string. The format string is composed of zero or more directives. See `man 3 printf` for more detail.
