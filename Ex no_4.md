# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
## DATE:01/09/2025
## AIM:
To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm
1. Start the program.
2. Declare an integer variable age.
3. Read the age of the person from the user.
4. Use an if-else statement:
      If age >= 21, print "Eligible for marriage".
      Else, print "Not eligible for marriage". 
5. Stop the program.  

## Program:


#include <stdio.h>

int main() {
    int age;

    printf("Enter the age of the person: ");
    scanf("%d", &age);

    if (age >= 21) {
        printf("Eligible for marriage\n");
    } else {
        printf("Not eligible for marriage\n");
    }

    return 0;
}

## Output:

<img width="1696" height="616" alt="image" src="https://github.com/user-attachments/assets/2445da2c-37ae-42d3-b63f-360d2dd0c020" />


## Result:
Thus the program was executed and the output was verified successfully.
