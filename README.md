# Expense-tracker-eeltut3
#include<stdio.h>
int main(){
    char week1,week2,week3,week4;
    char name[20],id[10],no[10],type[10];
    float amt1,amt2,amt3,amt4;
    
    printf("USER DETAILS-\n");
    printf("ENTER CUSTOMER ID-\n");
    scanf("%s",&id);
    printf("ENTER CUSTOMER NAME-\n");
    scanf("%s" ,&name);
    printf("ENTER CUSTOMER'S CONTACT NO-\n");
    scanf("%s",&no);
    printf("ENTER CUSTOMER TYPE(DOMICILE/COMMERCIAL)\n"); 
    scanf("%s",&type);
    
    printf("____ENTER WEEK 1 EXPENSE___\n");
    printf("CATEGORY-");
    scanf("%s",&week1);
    printf("AMOUNT-");
    scanf("%f",&amt1);
   printf("____ENTER WEEK 2 EXPENSE___\n");
printf("CATEGORY-");
    scanf("%s",&week2);
    printf("AMOUNT-");
    scanf("%f",&amt2);
    
    printf("____ENTER WEEK 3 EXPENSE___\n");
printf("CATEGORY-");
    scanf("%s",&week3);
    printf("AMOUNT-");
    scanf("%f",&amt3);
    
    printf("____ENTER WEEK 4 EXPENSE___\n");
printf("CATEGORY-");
    scanf("%s",&week4);
    printf("AMOUNT-");
    scanf("%f",&amt4);
    printf("\n");
  float total=(amt1+amt2+amt3+amt4);

printf(" =========================================\n");
printf("    MONTHLY EXPENSE REPORT\n");
printf(" =========================================\n");
printf("CUSTOMER ID-            %s\n",id);
printf("CUSTOMER NAME-          %s\n",name);
printf("CONTACT NO-             %s\n",no);
printf("CUSTOMER TYPE-          %s\n",type);
printf("Week 1 EXPENSE=         %f\n",amt1);
printf("Week 2 EXPENSE=         %f\n",amt2);
printf("Week 3 EXPENSE=         %f\n",amt3);
printf("Week 4 EXPENSE=         %f\n",amt4);
printf(" =========================================\n");
printf("TOTAL EXPENSE=          %f\n",total);
printf(" =========================================\n");
return 0;
 }
