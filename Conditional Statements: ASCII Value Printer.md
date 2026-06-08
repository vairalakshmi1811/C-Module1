# Conditional Statements: ASCII Value Printer in C

## Aim
To write a C program that prints the ASCII value of the characters 'a', 'z', 'A', or 'Z' using a switch statement. If any other character is entered, the program prompts the user to enter a valid alphabet.

## Algorithm
1.Declare a variable ch of type char.

2.Read a character from the user.

3. Use a switch statement to check if ch is 'a', 'A', 'z', or 'Z'.

4. If ch matches any of these cases, print its ASCII value using the printf function with %d format specifier.

## Program
#include <stdio.h>

int main() {
    char ch;
    scanf(" %c", &ch);  
    switch (ch) {
        case 'a':
        case 'z':
        case 'A':
        case 'Z':
            printf("ASCII value of '%c' is %d\n", ch, ch);
            break;
        default:
            printf("Invalid input. Please enter a valid alphabet: a, z, A, or Z.\n");
    }
    return 0;
}

## Output
<img width="860" height="392" alt="Screenshot 2026-06-08 212908" src="https://github.com/user-attachments/assets/8e9689f4-1ae3-45f9-b300-5419fd9e9cf2" />


## Result
programme was implemented and executed.
