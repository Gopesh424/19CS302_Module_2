# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).
## DATE:07/05/2025
## AIM:To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm
1. Start. 
2. Declare the variables. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Enter number for multiplication and division. 
6. End.    

## Program:
```
#include<stdio.h> 
void multiply(int a,int b); 
void div(int a,int b); 
int main () 
{ 
int a,b; 
scanf("%d%d",&a,&b); 
multiply(a,b); 
div(a,b); 
} 
void multiply(int a,int b) 
{ 
int product; 
product= a*b; 
printf("Multiplication: %d",product); 
} 
void div(int a,int b) 
{ 
int result; 
result=a/b; 
printf("\nDivision: %d",result); 
} 

/*
Program to perform multiplication and division of two numbers using functions (without argument and without return type).
Developed by: 
RegisterNumber:  
*/
```

## Output:
10  2
Multiplication: 20     Division: 5


## Result:
Thus the program was executed and the output was verified successfully.
