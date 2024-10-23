# odd-or-even-and-right-to-vote-program-in-c-lang
#include <stdio.h>

int main()
{
    printf("Hello World");
    int a=10,b=20,no,age;
    printf("\n%d",(a>b)&&(a<b));
    printf("\n%d",(a>b)||(a<b));
    printf("\n%d",!(b>a));
    printf("enter the number:");
    scanf("%d",&no);
    printf((no%2==0)?"ITS EVEN":"ITS ODD");
    printf("\nEnter your age:");
    scanf("%d",&age);
    printf((age>=18)?"RIGHT TO VOTE":"NOT ELIGIBLE");
    return 0;
}
