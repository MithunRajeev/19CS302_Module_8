## Hackerrank problem - 2

Your task is to take two numbers of int data type, two numbers of float data type as input and output their sum:
Declare 4 variables: two of type int and two of type float.
Read 2 lines of input from stdin (according to the sequence given in the 'Input Format' section below) and initialize your variables.
Use the + and - operator to perform the following operations:
Print the sum and difference of two int variable on a new line.
Print the sum and difference of two float variable rounded to one decimal place on a new line.

## AIM:
To write a C program to find the sum and difference of two integers and two float numbers entered by the user.
## ALGORITHM:
1. Start.
2. Define a variables.
3. Write a program to print the given string.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.
## PROGRAM:
```
#include <stdio.h>
int main()
{
    int a, b;
    float x, y;
    printf("Enter two integers: ");
    scanf("%d %d", &a, &b);
    printf("Enter two floats: ");
    scanf("%f %f", &x, &y);
    printf("%d %d\n", a + b, a - b);
    printf("%.1f %.1f\n", x + y, x - y);
    return 0;
}
```
## OUTPUT:
![Screenshot 2025-05-07 164549](https://github.com/user-attachments/assets/2e2af757-bc2a-4f45-a06b-c3def8a4236d)

## RESULT:
Thus, the program is executed and verified successfully.
