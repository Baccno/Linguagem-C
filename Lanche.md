#include <stdio.h>
 
int main() {
	double a,b,c,d,e,f,g,h;
	scanf("%lf", &a);
	if(a == 1)
	{
		c=4.00;
		scanf("%lf", &b);
		h=c*b;
		printf("Total: R$ %.2lf\n", h);
	}
	if(a == 2)
	{
		d=4.50;
		scanf("%lf", &b);
		h=d*b;
		printf("Total: R$ %.2lf\n", h);	
	}
	if(a == 3)
	{
		e=5.00;
		scanf("%lf", &b);
		h=e*b;
		printf("Total: R$ %.2lf\n", h);	
	}
	if(a == 4)
	{
		f=2.00;
		scanf("%lf", &b);
		h=f*b;
		printf("Total: R$ %.2lf\n", h);
	}
	if(a == 5)
	{
		g=1.50;
	    scanf("%lf", &b);
		h=g*b;
		printf("Total: R$ %.2lf\n", h);
	}
    return 0;
}
