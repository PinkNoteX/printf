## Printf Project
* The printf project is a collaboration between **Omar Ehab** and **Eslam Gamal** 
* The goal of this project is to create a function called "_printf" that imitates the actual "printf" located in the stdio.h
library
* _printf() is a function that performs formatted output conversion and print data
 
  > If the program runs successfully, the return value is the amount of chars printed. 
* _printf() function specifiers include
  *  c : Ouputs a Character
  *  d or i : Ouputs a Signed decimal integer
  *  s : Ouputs a String of characters
  *  b : Ouputs a Signed binary
  *  o : Ouputs a Signed octal
  *  u : Ouputs a Unsigned integer
  *  x : Ouputs a Unsigned hexadecimal
  *  p : Ouputs a Pointer adaress
  *  r : Ouputs a Reverse string of characters
  *  % : Ouputs a Character
* Some Examples:
1. Printing the string of chars "Hello, World:

   * Use: ```_printf("Hello Wo%s.", "rld");```
   * Output: Hello World.
2. Printing an integer number:
   * Use: ```_printf("10 + 10 is equal to %d.", 20);```
   * Output: 10 + 10 is equal to 20.
3. Printing a binary, octal and hexadecimal:
   * Use: ```_printf("10 in binary is [%b], in octal is [%o] and in hexadecimal is [%x]", 5, 5, 5);```
   * Output: 10 in binary is [1010], in octal is [12] and in hexadecimal is [A]

