# EX 51 C program to reverse a string.
## DATE:17/3/26
## AIM:
To write a C program to reverse a string.

## Algorithm
Start

Accept a string from the user.

Determine the length of the string.

Initialize two pointers:- One at the beginning (i = 0).

One at the end (j = length - 1).

Swap the characters at positions i and j.

Increment i and decrement j.

Repeat steps 5 and 6 until i is greater than or equal to j.
## Program:
```
/*
C program to reverse a string.
#include <stdio.h>
#include <string.h>

int main() {
    char str[100], reversed[100];
    int length, i;

    printf("Enter a string: ");
    scanf("%s", str);  // Reads a single word

    length = strlen(str);

    // Reverse manually
    for (i = 0; i < length; i++) {
        reversed[i] = str[length - i - 1];
    }
    reversed[length] = '\0'; // Null-terminate the reversed string

    printf("Reversed string: %s\n", reversed);
    
    return 0;
}
*/
```

## Output:

<img width="378" height="201" alt="image" src="https://github.com/user-attachments/assets/108d732e-7a54-47ef-9340-8cd94095b606" />


## Result:
Thus the program was executed and the output was verified successfully.
