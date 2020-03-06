#include <stdio.h>

int main()
{
	int n[20],inverte,i,j;
	
	for(i=0;i<20;i++)
	{
		scanf("%i", &n[i]);
	}
	for(i=0,j=19;i<10;i++,j--)
	{
		inverte=n[i];
		n[i]=n[j];
		n[j]=inverte;
	}
	
	for(i=0;i<20;i++)
	{
		printf("N[%i] = %i\n", i, n[i]);
	}
		
	return 0;
}
