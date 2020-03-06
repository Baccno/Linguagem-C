#include <stdio.h>
int main (){

	int h1,m1,h2,m2,a,b;//a representa a resposta em minutos e b representa horas
	scanf("%i %i %i %i", &h1, &m1, &h2, &m2);
	
	if(h1 == m2 && m1 == m2 && m2 == h2)
	{
		a=m1-m2;
		b=24+h1-h2;
		printf("O JOGO DUROU %i HORA(S) E %i MINUTO(S)\n", b, a);
	}
	else
    {
    if(h1 == h2 && m2 > m1)
    {
    	a=m2-m1;
    	b=h1-h2;
    	printf("O JOGO DUROU %i HORA(S) E %i MINUTO(S)\n", b, a);
	}
	if(h1 == h2 && m1 > m2)
	{
		a=60-m1+m2;
		b=24-h1+h2-1;
		printf("O JOGO DUROU %i HORA(S) E %i MINUTO(S)\n", b, a);
	}
	if(m1 == m2 && h1 < h2)
	{
		a=0;
		b=h2-h1;
		printf("O JOGO DUROU %i HORA(S) E %i MINUTO(S)\n", b, a);
	}
	if(m1 == m2 && h2 < h1)
	{
		a=0;
		b=24-h1+h2;
		printf("O JOGO DUROU %i HORA(S) E %i MINUTO(S)\n", b, a);
	}
	if(h2 > h1 && m2 > m1)
	{
		a=m2-m1;
		b=h2-h1;
		printf("O JOGO DUROU %i HORA(S) E %i MINUTO(S)\n", b, a);
	}
	if(h1 < h2 && m1 > m2)
	{
		a=60-m1+m2;
		b=h2-h1-1;
		printf("O JOGO DUROU %i HORA(S) E %i MINUTO(S)\n", b, a);
	}
	if(h1 > h2 && m1 < m2)
	{
		a=m2-m1;
		b=24-h1-1+h2;
		printf("O JOGO DUROU %i HORA(S) E %i MINUTO(S)\n", b, a);
	}
	if(h1 > h2 && m1 > m2)
	{
		a=60+m2-m1;
		b=24+h2-h1-1;
		printf("O JOGO DUROU %i HORA(S) E %i MINUTO(S)\n", b, a);
	}
	}
	
    
	return 0;
}
