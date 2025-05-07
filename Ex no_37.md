## Hackerrank problem - 2

Your task is to take two numbers of int data type, two numbers of float data type as input and output their sum:
Declare 4 variables: two of type int and two of type float.
Read 2 lines of input from stdin (according to the sequence given in the 'Input Format' section below) and initialize your variables.
Use the + and - operator to perform the following operations:
Print the sum and difference of two int variable on a new line.
Print the sum and difference of two float variable rounded to one decimal place on a new line.

## AIM:
To write a program to print the sum of the integers in the array.
## ALGORITHM:
1. Start.
2. Define a variables.
3. Write a program to print the sum of the integers in the array.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.
## PROGRAM:
```
#include<stdio.h>
int main()
{
int i,n,sum=0,arr[100];
scanf("%d",&n);
{
for(i=0;i<n;i++)
scanf("%d",&arr[i]);
for(i=0;i<n;i++)
sum=sum+arr[i];
i++;
}printf("%d",sum);
}
```
## output:
![image](https://github.com/user-attachments/assets/989a2c54-3a95-4d6a-a16e-370ce01b4ff8)
## RESULT:
Thus, the program is executed and verified successfully.
