# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
## DATE:23/02/2026
## AIM:
To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm
1. Start.
2. Declare a variable value of type char.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Check eligible for marriage.
6. If age >= 21, print "Eligible".
7. If false, print " Not Eligible".
8. End.
## Program:
```
#include <stdio.h>
int main() {
    int age;
    printf("Enter your age: ");
    scanf("%d", &age);
    if (age >= 21)
    {
        printf("You are eligible for marriage.\n");
    } else {
        printf("You are not eligible for marriage.\n");
    }
    return 0;
}
```

## Output:
Case 1: Enter your age: 25 You are eligible for marriage.

Case 2: Enter your age: 18 You are not eligible for marriage.

## Result:
Thus the program was executed and the output was verified successfully.
