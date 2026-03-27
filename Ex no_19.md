# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.
## DATE:
## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm
Start
Declare variables: num, leftShift, rightShift
Display the message: "Enter an integer"
Read the integer num from the user
Perform left shift: leftShift = num << 1
Perform right shift: rightShift = num >> 1
Display the original number num
Display the result of the left shift (leftShift)
Display the result of the right shift (rightShift)
End   

## Program:
```
#include <stdio.h>
int main() {
    int num, leftShift, rightShift;
    printf("Enter an integer: ");
    scanf("%d", &num);
    leftShift = num << 1;
    rightShift = num >> 1;
    printf("Original number: %d\n", num);
    printf("After left shift by 1: %d\n", leftShift);
    printf("After right shift by 1: %d\n", rightShift);
    return 0;
}
```

## Output:
<img width="298" height="136" alt="image" src="https://github.com/user-attachments/assets/a51e4b18-eb39-4b90-8e70-19e6dd2d2faf" />

## Result:
Thus the program was executed and the output was verified successfully.
