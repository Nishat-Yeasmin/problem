#include<stdio.h>
int main()
{
   int by,age;
   int current_year=2025;
   char gender;
   printf("enter your birth year: ");
   scanf("%d",&by);
   printf("enter your gender(m for male, f for female): ");
   scanf(" %c",&gender);
   age = current_year-by;
   printf("age = %d\n",age);
   if(age>=60)
    {
        if(gender=='m'||gender=='M')
       printf("you are old boy.\n");
   else if (gender=='f'||gender=='F')
    printf("you are old lady.\n");
    }
       else if(age>=30&&age<=59){
        if (gender=='m'||gender=='M')
            printf("you are middle aged men.\n");
       else if(gender=='f'||gender=='F')
         printf("middle aged women.\n");
       }

       else if(age<=29){
          if(gender=='m'||gender=='M')
       printf("you are young boy.\n");
   else if (gender=='f'||gender=='F')
    printf("you are young girl.\n");
       }

       else
        ptintf("invalid input");


}
