# EX-02-2d-Loop
## AIM:
Write a c program to find the sum of odd digits using for loop 
## ALGORITHM:
1. Declare variables to store the input number and the sum of odd digits.
2. Initialize the sum of odd digits to 0.
3. Use a for loop to iterate through each digit of the input number.
4. Inside the loop, extract the rightmost digit of the number (using the modulo operator % and division by 10).
5. If the digit is odd, add it to the sum of odd digits.
6. Print the sum of odd digits.
## PROGRAM:
```
#include<stdio.h>
int main()
{
    int i=1,n,s=0;
    scanf("%d",&n);
    while(i<=(2*n))
    {
        s=s+i;
        printf("%d ",i);
        i=i+2;
    }
    printf("\n%d",s);
    return 0;
}
```
## OUTPUT:
![image](https://github.com/Yogabharathi3/EX-02-2d-Loop/assets/118899387/f3c9d2a7-4335-4911-87a5-cbf7e97b131b)

## RESULT:
Thus the program to find the sum of odd digits using for loop has been executed successfully.
