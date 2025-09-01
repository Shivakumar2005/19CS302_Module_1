# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
## DATE:01/09/2025
## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm
1. Start the program.
2. Declare an array to store the marks of 7 subjects and variables for total, average, and percentage.
3. Input the marks of 7 subjects from the user.
4. Calculate the total by summing all the subject marks. 
5. Stop the program.  

## Program:
#include <stdio.h>

int main() {
    int marks[7], i, total = 0;
    float average, percentage;

    printf("Enter marks of 7 subjects (out of 100 each):\n");
    for (i = 0; i < 7; i++) {
        printf("Subject %d: ", i + 1);
        scanf("%d", &marks[i]);
        total += marks[i];
    }

    average = total / 7.0;
    percentage = (total / 700.0) * 100;

    printf("\nTotal Marks = %d\n", total);
    printf("Average Marks = %.2f\n", average);
    printf("Percentage = %.2f%%\n", percentage);

    return 0;
}

## Output:

<img width="1682" height="673" alt="image" src="https://github.com/user-attachments/assets/76a839b4-ad10-4682-8105-d573cfe46819" />


## Result:
Thus the program was executed and the output was verified successfully.
