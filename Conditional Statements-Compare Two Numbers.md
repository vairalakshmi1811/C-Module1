## Conditional Statements-Compare Two Numbers
## Aim
Write a C program to read values of x and y and print whether x == y or x != y using an if-else statement.

## Algorithm
Declare variables x and y.

Read two integers x and y from the user.

Check if x is equal to y using the if statement.

If x is equal to y, print "X is equal to Y".

If x is not equal to y, print "X is NOT equal to Y".

## Program
```
#include <stdio.h>
int main()
{
    int x,y;
    scanf("%d%d",&x,&y);
    if(x==y)
    printf("x is equal to y.");
    else if(x!=y)
    printf("x is NOT equal to y.");
}
```

## Output
<img width="847" height="331" alt="Screenshot 2026-06-08 211342" src="https://github.com/user-attachments/assets/bfea7492-c4db-4077-8a39-716c1a8dad33" />




## Result
C program to read values of x and y and print whether x == y or x != y using an if-else statement is written
