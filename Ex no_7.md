# EX 7 C Program to Print a right triangle star Pattern
## DATE:
## AIM:
To write a C Program to Print a right triangle star Pattern

## Algorithm
Start.
Declare the variables i,j,k,n.
Prompt the user to enter a value.
Read the value using scanf.
Enter number of rows and columns.
End. 

## Program:
```
#include <stdio.h> 
int main() { 
    int i, j, rows; 
    scanf("%d", &rows); 
    for (i = 1; i <= rows; i++) { 
        for (j = 1; j <= i; j++) { 
            printf("*"); 
        } 
        printf("\n"); 
    }    return 0; 
}
Developed by: GONGOTI SANDEEP YADAV
RegisterNumber: 212222060067
```

## Output:
<img width="340" height="153" alt="image" src="https://github.com/user-attachments/assets/acf12a06-a4f7-49f4-91a5-dbf36e07ab15" />


## Result:
Thus the program was executed and the output was verified successfully.
