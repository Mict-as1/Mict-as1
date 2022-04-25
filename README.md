#include<stdio.h>
int addition(int a, int b);
int subtraction (int a, int b);
int main()
{
    int x, y;
    printf("enter the first value\n");
    scanf("%d", & x);
    printf("enter the second value\n");
    scanf("%d", & y); 
    addition(x, y);
    subtraction(x, y);
    
    printf("the addition of two number is %d\n", addition(x, y));
    printf("the subtraction oftwo number is %d\n", subtraction(x, y));
    return 0;
}
int addition(int a, int b){
     return (a + b);
}
int subtraction (int a, int b){
     return (a - b);
}

