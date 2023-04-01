This is the first group project that we have at Holberton School, which consists of replicating the printf (3) function of language c, calling it this way _printf.

This function is part of the standard library and to use it we must specify the header file <stdio.h>.

Writes the C string pointed by format to the standard output (stdout). If format includes format specifiers (subsequences beginning with %), the additional arguments following format are formatted and inserted in the resulting string replacing their respective specifiers.

Parameters
format -> C string that contains the text to be written to stdout.

Where the specifier character at the end is the most significant component, since it defines the type and the interpretation of its corresponding argument:
