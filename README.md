#include<stdio.h>
void main()
{
    int a[3],sum=0,i,*ptr;
    
    printf("\n enter array element");
    for(i=0;i<3;i++)
{
    scanf("%d",&a[i]);
}    
ptr=&a[0];
for(i=0;i<3;i++)
{
    sum=sum+(*ptr);
    ptr=ptr+1;
}
printf("\n sum=%d",sum);
}
