# EX 20 C program to convert the given string to lowercase without using string functions.
## DATE:
## AIM:
To write a C program to convert the given string to lowercase without using string functions.

## Algorithm
Start.
Define the required variable.
Convert the string to lowercase.
Read the value using scanf.
Print out the answer.
End.  

## Program:
```
#include <stdio.h> 
int main() { 
    char str[100]; 
    int i = 0; 
    scanf("%s", str);   
    while (str[i] != '\0') { 
        if (str[i] >= 'A' && str[i] <= 'Z') { 
            str[i] = str[i] + 32;        } 
        i++;    } 
    printf("Lowercase string: %s\n", str); 
    return 0; 
} 
```

## Output:
<img width="453" height="171" alt="image" src="https://github.com/user-attachments/assets/827439d9-da0b-472a-a722-d240c051a2b8" />

## Result:
Thus the program was executed and the output was verified successfully.
