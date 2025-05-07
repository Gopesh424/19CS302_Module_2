# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## DATE:07/05/2025
## AIM:To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
1. Start. 
2. Declare the variables. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Enter factorial of the number. 
6. End.   

## Program:
```
#include <stdio.h> 
int main() { 
    int n, i; 
    unsigned long long factorial = 1; 
    scanf("%d", &n); 
 
    if (n < 0) { 
        printf("Factorial is not defined for negative numbers.\n"); 
    } else { 
        for (i = 1; i <= n; i++) { 
            factorial *= i; 
        } 
        printf("Factorial of %d = %llu\n", n, factorial); 
    } 
    return 0; 
}
/*
Program to find the factorial of a given number using a function with arguments and return type.
Developed by: 
RegisterNumber:  
*/
```

## Output:
5
120


## Result:
Thus the program was executed and the output was verified successfully.
