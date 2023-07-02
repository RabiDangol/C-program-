# C-program-
WAP in c to sort array of size 5 in an ascending order?
#include<stdio.h>
#include<conio.h>
int main()
{
int a[5],i,j,temp;
printf("array element:\n");
for(i=0;i<5;i++)
{
scanf("%d",&a[i]);
}
printf("the sorting is done\n");
for(i=0;i<5;i++)
{
for(j=i+1;j<5;j++)
{
if (a[i]>a[j])
temp=a[i];
a[i]=a[j];
a[j]=temp;
}
}
printf("element of sorting data are \n");

}
for(i=0;i<5;i++)
{
printf("%d\n",a[i]);
}
getch();
}
