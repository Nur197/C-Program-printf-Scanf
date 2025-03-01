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

