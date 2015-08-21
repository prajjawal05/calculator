# calculator
learned switch case
#include <stdio.h>
#include <stdlib.h>

void main()
{
    printf("Enter the purpose of calculator\n");
    printf("1.Addition\n");
    printf("2.Subtraction\n");
    printf("3.Multiplication\n");
    printf("4.Division\n");
    int n;
    float a,b,c;
    scanf("%d", &n);
    printf("PLease enter the two numbers\n");
    scanf("%f",&b);
    scanf("%f",&a);
    c=(a/b);
    switch(n)
    {
        case 1: printf("The sum of the two numbers are %d", a+b);
                break;
         case 2: printf("The subtraction of the two numbers are %d", a-b);
                break;
         case 3: printf("The multiplication of the two numbers are %d", a*b);
                break;
         case 4: printf("The remainder of the two numbers are %f", c);
                break;
        default:printf("Invalid Input");
    }
}
