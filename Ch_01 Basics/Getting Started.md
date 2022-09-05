
#include <stdio.h>
#include <math.h>
int main(){
    //float variables for principle,rate of interset and compound interset
    float principal, rate,amount; 
    //variable time which in years
    int t;
    //input Princple
    printf("Enter The Principal Amount: \n");
    scanf("%f", &principal);
    //iput 
    printf("Enter Rate of Interest: \n");
    scanf("%f", &rate);
    printf("Enter Time Period: \n");
    scanf("%d", &t);
    amount = principal * (pow((1 + rate/100), t));
    printf("%f\n", amount);
    return 0;
}
