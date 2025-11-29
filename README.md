#include<stdio.h>
int main() {

float km,m,cm;
printf("enter the numbers in cm : ")
scanf("%f",&cm);

km = cm/100000;
m = cm/100;

printf("kilometer = %.10f km \n",km);
printf("meter = %.14f m\n",m);
printf("centimeter = %f cm \n"cm);
return 0;
}
