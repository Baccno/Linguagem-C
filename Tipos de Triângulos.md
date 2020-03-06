#include <stdio.h>
int main (){

	double A, B, C;
	double maior;//para falar que a vai ser sempre maior

	scanf("%lf %lf %lf", &A, &B, &C);
	
	if(A < B)
	{
		maior=A;
		A=B;
		B=maior;	
	}
	if(A < C)
	{
		maior=A;
		A=C;
		C=maior;	
	}
	if(B < C)
	{
		maior=B;
		B=C;
		C=maior;	
	}

	if(A >= (B+C))
  	{
  		printf ("NAO FORMA TRIANGULO\n");
	}
	else
    {
	if((A*A) == (B*B)+(C*C))
	{
		printf("TRIANGULO RETANGULO\n");
	}
	if((A*A) > (B*B)+(C*C))
	{
		printf("TRIANGULO OBTUSANGULO\n");
	}
	if((A*A) < (B*B)+(C*C))
	{
		printf("TRIANGULO ACUTANGULO\n");
	}
	}
	if(A == B && B == C && C == A)
	{
		printf("TRIANGULO EQUILATERO\n");
	}
	else
	{
	if (A == B  ||  B == C  ||  C ==A)
	{
        printf("TRIANGULO ISOSCELES\n");
    }
    }
	return 0;
}
