# c-LAnguage-
#include<stdio.h>
#include<conio.h>
int main()
{
int i,age;
for(i=1;i<=30;i++)
{
printf("*");
}
printf(" \t\nDriving Licence Checker\n ");
for(i=1;i<=30;i++)
{
printf("*");
}

printf("Enter Your Age: ");
scanf("%d",&age);
if(age<=18)
{
printf("You Are Not ELigible For DL");
}
else
{
printf("You Are Eligible For DL");
}


getch();

}
