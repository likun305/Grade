#include<stdio.h>
#include<stdlib.h>
int main()
{
	float per;
	printf("Enter percentage marke");
	scanf("%f",&per);
	if(per>=85)
	printf("Grade is A");
	else if (per>=70)
	printf("Grade is B");
	else if (per>=55)
	printf("Grade is C");
	else if(per>=40)
	printf("Grade is D");
	else
	printf("Grade is F");
	
	return 0;
	
	
}
