# A-function-that-writes-the-sum-of-2-integers-sent-into-it.
A function that writes the sum of 2 integers sent into it
#include <stdio.h>
#include <stdlib.h>
#include <conio.h>

int main()
{
    int num1,num2,sum;
    printf("Number 1 :");
    scanf("%d",&num1);
    printf("Number 2 :");
    scanf("%d",&num2);

    sum=num1+num2;

    printf("\n\nSum: %d",sum);

    return 0;
}

