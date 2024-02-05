Requirements
The function is written in C language and this needs the gcc compiler and some standard C libraries to run.

Instructions
1. Using it in your code

To use the function in your code, simply include its header:

#include "get_next_line.h"
and, when compiling your code, add the source files and the required flag:

get_next_line.c get_next_line_utils.c -D BUFFER_SIZE=<size>
📋 Testing
You only have to edit the get_next_line.c file and uncomment the main function and headers inside it. You can edit test.txt files to put another text if you wish to test othe cases. Then simply run this command (change "xx" with desired buffer size) :

gcc -Wall -Werror -Wextra -D BUFFER_SIZE=xx get_next_line.c get_next_line_utils.c && ./a.out
Or you can also use this third party tester to fully test the project
