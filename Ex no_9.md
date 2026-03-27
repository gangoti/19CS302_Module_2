# EX 9 C program to find the sum of odd digits using do while loop.
## DATE:
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm

Start the program.
Read the input number from the user.
Initialize sum = 0.
Using a do while loop.
Repeat the loop until num becomes 0.
Display the sum.
End.

## Program:
```
#include <stdio.h>

int main()
{
    int num, digit, sum = 0;
    scanf("%d", &num);
    int temp = num; 
    do
{
        digit = num % 10;
        if (digit % 2 != 0)
 {
            sum += digit;
        }
        num /= 10;
    } while (num != 0);
    printf("Sum of odd digits of %d is: %d\n", temp, sum);
    return 0;
}

Developed by: GONGOTI SANDEEP YADAV
RegisterNumber:  212222060067
```

## Output:
<img width="516" height="190" alt="image" src="https://github.com/user-attachments/assets/a4a74088-b377-475f-a1ff-935f906dd621" />


## Result:
Thus the program was executed and the output was verified successfully.
