# Project Name
0x11. C - printf
## Author Details
1. Antony Wainaina
2. Lucy Kinyanjui

## Requirements
Allowed editors: vi, vim, emacs.
All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89.
Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl.
All your files should end with a new line.
You are not allowed to use global variables.
No more than 5 functions per file.
Note that we will not provide the _putchar function for this project.
The main.c files are used to test your functions, but you don’t have to push them to your repo.
The prototypes of all your functions should be included in your header file called main.h.
All your header files should be include guarded.

### Project Description
Write your own printf function. _printf is a custom implementation of the C programming function printf. This project is an application of the C programming knowledge that ALX School cohort 5 students have learned since starting the program on February 2022. Below are examples of how to use it:

String

Input: _printf("%s\n", 'This is a string.');
Output: This is a string.
Character

Input: _printf("The first letter in the alphabet is %c\n", 'A');
Output: The first letter in the alphabet is A
Integer

Input: _printf("There are %i dozens in a gross\n", 12);
Output: There are 12 dozens in a gross
Decimal:

Input: _printf("%d\n", 1000);
Output: 1000
Compilation
Your code will be compiled this way.
$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c
Your code will be compiled as shown above.
As a consequence, be careful not to push any c file containing a main function in the root directory of your project (you could have a test folder containing all your tests files including main functions).
Our main files will include your main header file (main.h): #include main.h.
You might want to look at the gcc flag -Wno-format when testing with your _printf and the standard printf.
