# EX 2 C program to check whether the attendance is PRESENT using simple if statement.
## DATE:01/09/2025
## AIM:
To write a program to check whether the attendance is PRESENT using simple if statement.

## Algorithm
1. Start the program.
2. Declare a character array (string) to store the attendance status.
3. Use a simple if statement to check if the status is "PRESENT".
4. If true, display "The student is PRESENT". 
5. Stop the program.  

## Program:
///
#include <stdio.h>
#include <string.h>

int main() 
{
    char attendance[20];

    printf("Enter attendance (PRESENT/ABSENT): ");
    scanf("%s", attendance);

    // Simple if statement
    if (strcmp(attendance, "PRESENT") == 0) {
        printf("The student is PRESENT\n");
    }

    return 0;
}
///

## Output:

<img width="1544" height="557" alt="Screenshot 2025-09-01 082040" src="https://github.com/user-attachments/assets/01ef7f5e-5788-4e13-a509-567bbebc63d5" />


## Result:
Thus the program was executed and the output was verified successfully.
