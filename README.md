C - printf
   A recreation of the C printf library function.

Usage - complie all c files in the repo and include the header file in main.h with any main function
		example main.c
		
		"#include 'main.h'
		int main ()
		{
			_printf("Hello world");

			return (0);
		}
compilation:  $gcc *.c -o demo
      Hello, world

      Description
The _printf function just like the std, printf writes a formatted output to the stdout. The format to print is specified by the format string.
Prototype:
	int _printf(const char *format, ...)

Requirements:
Authorized functions and macros:
	     write (man 2 write)
             malloc (man 3 malloc)
             free (man 3 free)
             va_start (man 3 va_start)
             va_end (man 3 va_end)
             va_copy (man 3 va_copy)
             va_arg (man 3 va_arg)



