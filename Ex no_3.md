# EX 3 C program to find number of years based on principle,rate & simple interest.
## DATE:
## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
1. Start the program.
2. Declare variables for Principal (P), Rate (R), Simple Interest (SI), and Time (T).
3. Read the values of Principal, Rate, and Simple Interest from the user.
4. Display the number of years. 
5. Stop the program.  

## Program:
///
#include <stdio.h>

int main() {
    float principal, rate, si, time;

    printf("Enter Principal amount: ");
    scanf("%f", &principal);

    printf("Enter Rate of interest: ");
    scanf("%f", &rate);

    printf("Enter Simple Interest: ");
    scanf("%f", &si);

    // Formula: T = (SI * 100) / (P * R)
    time = (si * 100) / (principal * rate);

    printf("Number of years = %.2f\n", time);

    return 0;
}
///
## Output:

<img width="1554" height="679" alt="image" src="https://github.com/user-attachments/assets/672b37a3-0a27-4dbc-9e93-4d877e700888" />


## Result:
Thus the program was executed and the output was verified successfully.
