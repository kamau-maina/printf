C - printf
   A recreation of the C printf library function.

Usage 
	complie all .c files in the repo and include the header file in main.h with any main function
		example main.c
		
		#include 'main.h'
		int main ()
		{
			_printf("Hello world");

			return (0);
		}
compilation: 
	 $gcc *.c -o demo
		Hello, world

      Description
The _printf function just like the std librarie's printf writes a formatted output to the stdout. The format to print is specified by the format string.
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

The format string (Hw the subsequents are accessed)
	The _printf() however, does not handle:
			i. Flag characters\n
			ii. Field width\n
			iii. Precision\n
			iv. Length modifiers

Return value
	_printf, upon successful return, returns the number of characters printed excluding the null byte. If an error occurs, it returns -1

Parameters
	Format -This string contains the text to be written to stdout. It may also contain embedded format tags which are required by values specified by subsequent additional argument.

	The format tag prototype is %[flags]


