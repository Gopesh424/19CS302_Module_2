# EX 9 C program to find the sum of odd digits using do while loop.
## DATE:07/05/2025
## AIM:To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1.Start 
2. Input the number and initialize a variable sum to 0.
3.Extract each digit using modulo (%) and check if it is odd. If odd, add it to sum. Remove the last digit using division (/). Repeat using a do...while loop until the number becomes 0.
4.Output the sum of the odd digits.  
5.End  

## Program:
```
#include <stdio.h>

int main() {
    int num, digit, sum = 0;

    printf("Enter a number: ");
    scanf("%d", &num);

    int temp = num; // Preserve original number if needed

    if (num == 0) {
        sum = 0;  // Edge case
    } else {
        do {
            digit = num % 10;
            if (digit % 2 != 0) {
                sum += digit;
            }
            num /= 10;
        } while (num != 0);
    }

    printf("Sum of odd digits of %d = %d\n", temp, sum);
    return 0;
}

/*
Program to find the sum of odd digits using do while loop.
Developed by: 
RegisterNumber:  
*/
```

## Output:
12345
9


## Result:
Thus the program was executed and the output was verified successfully.
