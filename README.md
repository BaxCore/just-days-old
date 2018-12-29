# just-days-old
this program helps you calculate the days you have spent on earth 
#include <stdio.h>
//days old calculator
int main()
{
//valiable diclaration
    int currentdate, currentmonth, currentyear, datebirth, monthbirth, yearbirth;
    int yearsindays, numberdaysbirthmonth, numberdaysbirthyear;
 printf("\n.......................................................................\n");
//dateS
    printf("\n\nEnter the current date:");
    scanf("%d", &currentdate);
         printf("Enter your date of birth:");
         scanf("%d",&datebirth);

//months
    printf("\n\nEnter the current month:");
    scanf("%d",&currentmonth);
        printf("Enter your month of birth:");
        scanf("%d",&monthbirth);

//year
    printf("\n\nEnter the current year:");
    scanf("%d",&currentyear);
        printf("Enter your year of birth:");
        scanf("%d",&yearbirth);

 //no. of days in a month
    printf("\n\nEnter the number of days of your month of birth:");
    scanf("%d",&numberdaysbirthmonth);
        printf("Enter the number of days in your year of birth:");
        scanf("%d",&numberdaysbirthyear);

//your age
int yold;
 yold = currentyear-yearbirth;
        printf("\n\n\t\tYOUR %d YEARS OLD", yold);

//days in a month
int mdays;
 mdays = numberdaysbirthmonth-datebirth;

//days old
int days = (((yold)-1)*numberdaysbirthyear)+((12-monthbirth)*numberdaysbirthmonth)+(mdays);
             printf("\n\t\tYOUR %d DAYS OLD\n",days);
    return 0;
}
