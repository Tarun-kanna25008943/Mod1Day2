# EX-02 Check Whether the Value is Greater Than or Equal to 100

## AIM:
To write a C program to read a value and check whether the value is greater than or equal to 100.

## ALGORITHM:
1. Start
2. Declare an integer variable int a.
3. Prompt the user to enter a number.
4. Read the number using scanf.
5. Use an if condition to check whether a >= 100.
6. If true, display “Value is greater than or equal to 100”.
7. Else, display “Value is less than 100”.
8. Stop

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int num;
    printf("Enter your number: ");
    scanf("%d",&num);
    if(num>=100)
    {
        printf("The Value is greater than or equal to 100");
    }
    else
    {
      printf("The value is less than 100");
    }
 return 0;   
}
```

## OUTPUT:

<img width="655" height="131" alt="image" src="https://github.com/user-attachments/assets/f2eb7cb1-6b00-44c6-b5c3-c7a0937e942a" />

## RESULT:
The program correctly identifies whether the entered value is greater than or equal to 100.
