#include<stdio.h>
main()
{
printf("Enter the marks\n");
int marks;
scanf("%d",&marks);
if(marks>=85)
{
printf("CONGRATS! YOU GOT GRADE A\n");
}
else if(marks>=70)
{printf("Good to know that you secured GRADE B\n");
}
else if(marks>=55)
{
printf("your GRADE is C ,need to improve ");
}
else if(marks>=40){
printf("work hard , you got GRADE D ");
}
else{printf("sad to inform that your GRADE IS F,DON'T BE DEMOTIVATED. ");}
}
