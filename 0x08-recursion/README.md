Prototype: void _puts_recursion(char *s);
Solution: 0-puts_recursion.c

$ amonkeyprogrammer@ubuntu:~/0x08. Recursion$ cat 0-main.c
#include "main.h"

/**
 * main - check the code for Holberton School students.
 *
 * Return: Always 0.
 */
int main(void)
{
    _puts_recursion("Betty main");
    return (0);
}
$ amonkeyprogrammer@ubuntu:~/0x08. Recursion$ gcc -Wall -pedantic -Werror -Wextra _putchar.c 0-main.c 0-puts_recursion.c -o 0-puts_recursion
$ amonkeyprogrammer@ubuntu:~/0x08. Recursion$ ./0-puts_recursion 
Betty main
