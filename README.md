# Armstrong
#include<stdio.h>
void main ()
{
int n,m,d,c,sum=0;
printf("enter any number ");
scanf("%d",&n);
 m=n;
 while(n>0)
{
 d=n%10;
 c=d*d*d;
 n/=10;
 sum+=c;
}
 printf("Sum of cube of digits of a number=%d\n",sum);
 if (m==sum)
 printf("Armstrong number");
 else
 printf("N0T Armstrong number");

}
