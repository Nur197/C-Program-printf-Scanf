# C-Program-printf-Scanf

PROBLEM 06 - 

#include<stdio.h>
int main()
{
    int x ,y;
    printf("Enter 1st value - ");
    scanf("%d",&x);
    printf("Enter 2nd value - ");
    scanf("%d",&y);
    printf("%d %d \n",x,y);
    return 0;
}


Problem 08 - 

#include<stdio.h>
int main()
{
    int x;
    printf("Enter your name - ");
    scanf("%c",&x);
    printf("First word of your name is - %c \n",x);
    return 0;

}

PROBLEM 09 - 

#include<stdio.h>
int main()
{
    int x,y,sum;
    printf("Enter 1st value - ");
    scanf("%d",&x);
    printf("Enter 2nd value - ");
    scanf("%d",&y);
    sum = x + y;
    printf("%d + %d = %d",x,y,sum);
    return 0;


}

PROBLEM 11 - 

#include<stdio.h>
int main()
{
    int a,b,sub;
    printf("Enter 1st Number - ");
    scanf("%d",&a);
    printf("Enter 2nd Number - ");
    scanf("%d",&b);
    sub = a - b;
    printf("%d - %d = %d\n",a,b,sub);
    return 0;
}

PROBLEM 12 - 

#include<stdio.h>
int main()
{
    int a,b,sum,sub,mul,div,rim;
    a = 10;
    b = 4;
    sum = a + b;
    sub = a - b;
    mul = a * b;
    div = a / b;
    rim = a % b;
    printf("sum - %d + %d = %d\n",a,b,sum);
    printf("sub - %d - %d = %d\n",a,b,sub);
    printf("mul - %d * %d = %d\n",a,b,mul);
    printf("div - %d / %d = %d\n",a,b,div);
    printf("rim - %d % %d = %d\n",a,b,rim);
    return 0;
}

