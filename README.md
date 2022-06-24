//# Salary-Tax-Calculator
//It will calculate tax for your salary
#include<stdio.h>
int main()
{
int salary;
float tax1,tax2,tax3;
printf("Enter your salary\n");
scanf("%d",&salary);
tax1=salary*5/100;
tax2=salary*20/100;
tax3=salary*30/100;
if(250000<salary<500000){
    printf("you have to pay 5 percent of tax is %f",tax1);
}
else if(500000<salary<1000000){
    printf("you have to pay 20 percent of tax is %f",tax2);
}
else if(salary>1000000){
    printf("you have to pay 30 percent of tax is %f",tax3);
}
    return 0;
}
