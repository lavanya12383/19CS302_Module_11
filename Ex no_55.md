# EX 55 C program to find a square of number using function with arguments without return type.
## DATE:17/3/26
## AIM:
To write a C program to find a square of number using function with arguments without return type.

## Algorithm
tart
Define a function findSquare(num) that takes an integer argument.
Inside the function, compute num * num and display the result.
In the main() function:
Accept an integer input from the user.
Call findSquare(number) with the input value.
End 

## Program:
```
/*
C program to find a square of number using function with arguments without return type.
#include <stdio.h>

void findSquare(int num) {
    printf("Square of %d is: %d\n", num, num * num);
}

int main() {
    int number;
    printf("Enter a number: ");
    scanf("%d", &number);
    
    findSquare(number);
    
    return 0;
}  
*/
```

## Output:
<img width="422" height="201" alt="image" src="https://github.com/user-attachments/assets/77bf639c-9220-4918-b746-b4d176ff9091" />



## Result:
Thus the program was executed and the output was verified successfully.
