# Program-2-e
## C-Module 2
## EX_NO-02)e)-LOOPS
### Date: 19-10-2025
### Name: Anish D
### Register Number:25010086
## AIM:
Write a C program to print the multiplication table of  a given number using do while loop within the certain limit or range
## ALGORITHM:
1. Start the program.
2. Declare three integer variables: num1, num2, and i. Initialize i to 1.
3. Read two integer values (num1 and num2) from the user using scanf.
4. Use a do-while loop that runs as long as i is less than or equal to num2:

    a. Multiply num1 by i and store the result in a variable mul.

    b. Print the value of mul followed by a space.

    c. Increment i by 1.

6. End the program.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int num1,num2,i=1;
    scanf("%d\n%d",&num1,&num2);
    do{
        int mul=num1*i;
        printf("%d ",mul);
        i++;
    }while(i<=num2);
}

```
## OUTPUT:
<img width="844" height="338" alt="Screenshot 2025-10-19 220637" src="https://github.com/user-attachments/assets/2268e54a-1cce-4637-b323-20f52bb7961a" />

## RESULT:
Thus the program to print the multiplication table of  a given number using do while loop within the certain limit or range has been executed successfully
