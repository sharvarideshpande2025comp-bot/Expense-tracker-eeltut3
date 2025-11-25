# Expense-tracker-eeltut3
#include <stdio.h>

int main() {
    char week1[20], week2[20], week3[20], week4[20];
    char name[20], id[10], no[15], type[15];
    float amt1, amt2, amt3, amt4;

    printf("USER DETAILS-\n");

    printf("ENTER CUSTOMER ID-\n");
    scanf("%s", id);

    printf("ENTER CUSTOMER NAME-\n");
    scanf("%s", name);

    printf("ENTER CUSTOMER'S CONTACT NO-\n");
    scanf("%s", no);

    printf("ENTER CUSTOMER TYPE (DOMICILE/COMMERCIAL)-\n");
    scanf("%s", type);

    printf("____ENTER WEEK 1 EXPENSE___\n");
    printf("CATEGORY- ");
    scanf("%s", week1);
    printf("AMOUNT- ");
    scanf("%f", &amt1);

    printf("____ENTER WEEK 2 EXPENSE___\n");
    printf("CATEGORY- ");
    scanf("%s", week2);
    printf("AMOUNT- ");
    scanf("%f", &amt2);

    printf("____ENTER WEEK 3 EXPENSE___\n");
    printf("CATEGORY- ");
    scanf("%s", week3);
    printf("AMOUNT- ");
    scanf("%f", &amt3);

    printf("____ENTER WEEK 4 EXPENSE___\n");
    printf("CATEGORY- ");
    scanf("%s", week4);
    printf("AMOUNT- ");
    scanf("%f", &amt4);

    float total = amt1 + amt2 + amt3 + amt4;

    printf("\n =========================================\n");
    printf("    MONTHLY EXPENSE REPORT\n");
    printf(" =========================================\n");
    printf("CUSTOMER ID-            %s\n", id);
    printf("CUSTOMER NAME-          %s\n", name);
    printf("CONTACT NO-             %s\n", no);
    printf("CUSTOMER TYPE-          %s\n", type);
    printf("Week 1 (%s) EXPENSE =   %.2f\n", week1, amt1);
    printf("Week 2 (%s) EXPENSE =   %.2f\n", week2, amt2);
    printf("Week 3 (%s) EXPENSE =   %.2f\n", week3, amt3);
    printf("Week 4 (%s) EXPENSE =   %.2f\n", week4, amt4);
    printf(" =========================================\n");
    printf("TOTAL EXPENSE =         %.2f\n", total);
    printf(" =========================================\n");

    return 0;
}
