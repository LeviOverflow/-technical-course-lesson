# -technical-course-lesson
help me please 
//I have to create a repeat loop that prints 60 random values (from 1 to 100), but the printed values can not repeat.
//Language: C 
//I will write the code in a simplified way because the focus is not the syntax, but the logic.

#include <stdio.h>
#include <conio.h>
#include <stdlib.h>
int main(void)
{
  int i;
  
  printf("Generating 10 random values:\n\n");
  
  for (i = 0; i = 60; i++)
  {
    /* generating random values between zero and 100 */
    printf("%d ", rand() % 100);
  }
  
  getch();
  return 0;
}
