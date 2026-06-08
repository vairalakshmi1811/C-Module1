## Conditional Statements: Positive Number Checker
## Aim
To write a C program that reads a value A from the user and checks whether it is a positive number or not.

## Algorithm
Declare a variable to store the input value A.

Use the scanf function to read the value of A from the user.

Check if the value of A is greater than zero.

If A is greater than zero, print a message indicating that it's a positive number.

Otherwise, print a message indicating that it's not a positive number.

End the program.

## Program
```
#include <stdio.h>
int main()
{
    int A;
    printf("Enter a number: ");
    scanf("%d", &A);
    if (A > 0) {
        printf("The number is positive.\n");
    } else {
        printf("The number is NOT positive.\n");
    }

    return 0;
}
```

## Output
<img width="633" height="208" alt="image" src="https://github.com/user-attachments/assets/f09e98d4-43e4-48fc-b6a7-0469d9c14f92" />



## Result
programme was implemented and executed.
