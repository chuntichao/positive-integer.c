# positive-integer.c
#include <stdio.h>
#include <cs50.h>
int get_positive_int(string prompt);
int main(void)
{
   int i j= get_positive_int("positive integer: ");
   printf("%i", i );
   
   int get_positive_int(string prompt)
   {   int i;
   do
     {  n = get_int("%s", prompt);
     }
     while (n < 1 );
     return n;
     }
