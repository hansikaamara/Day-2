# Day-2
#include <stdio.h>
int main()
{
    float meal_cost,tax,tip,total_bill;
    float each_share,your_payment,friend2_payment,friend3_payment,forgot_payment;
    printf("Enter meal cost\n");
    scanf("%f",&meal_cost);
    tax = 0.05*meal_cost;
    tip = 0.10*meal_cost;
    total_bill = meal_cost+tax+tip;
    printf("total bill= %f\n", total_bill);
    each_share = total_bill/3;
    printf("Each share = %f\n",each_share);
    printf("Each persone should pay as follows:\n");
    your_payment = each_share+(each_share/2);
    printf("you = %f\n",your_payment);
    friend2_payment = each_share=(each_share/2);
    printf("Friend2 = %f\n",friend2_payment);
    forgot_payment = 0;
    friend3_payment = forgot_payment;
    printf("friend3 = %f\n",friend3_payment);
    return 0;
}
