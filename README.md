# find-length-of-fibonacci-nth-term-by-using-for-lop-in-c-language
#include<stdio.h>
int main()
{
    int first=0,second=1,third,i,n;
    printf("enter the lengh of fibo:");
    scanf("\n%d",&n);
    printf("\n the fibo series\n");
    printf("%d",first);
    printf("%d",second);
    for(i=2;i<=n;i++)
    {
        third=first+second;
        printf("\n%d",third);
        first=second;
        second=third;
    }
    return 0;
}
