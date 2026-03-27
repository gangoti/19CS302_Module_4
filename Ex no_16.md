# EX 16 C program to find minimum between three fraction numbers using conditional operator.
## DATE:
## AIM:
To write a C program to find minimum between three fraction numbers using conditional operator.

## Algorithm
Start.
Define a variables a,b,c,min.
Write program to find minimum numbers.
Read the value using scanf.
Ask the user to make an input.
Print out the answer.
End.   

## Program:
```
#include <stdio.h> 
int main() { 
float a, b, c, min; 
scanf("%f%f%f", &a, &b, &c); 
// Finding minimum using conditional operator 
min = (a < b) ? ((a < c) ? a : c) : ((b < c) ? b : c); 
 
printf("Minimum between %.3f, %.3f and %.3f = %.3f\n",a,b,c, min); 
return 0; 
} 
```

## Output:
<img width="661" height="181" alt="image" src="https://github.com/user-attachments/assets/1fc14439-157c-4642-99d4-ea175ee84d24" />

## Result:
Thus the program was executed and the output was verified successfully.
