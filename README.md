# Simple-interest
#include<stdio.h>
int main()
{
	float p, t, r, SI;
	printf("Program to calculate simple interest\n");
	printf("Enter principle amount: ");
	scanf("%f", &p);
	printf("Enter time (in years): ");
	scanf("%f", &t);
	printf("Enter rate: ");
	scanf("%f", &r);
	SI = (p * t * r) /100;
	printf("simple interest = %.2f",SI);
	return 0;
}
