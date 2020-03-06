#include <stdio.h>
int main()
{
    int t,rmenor=0,r,i,menor=0,resposta=0,solucao=1;//t=tentativas
    scanf("%i", &t);
    
    for(i=1;i<=t;i++)
    {
        scanf("%i", &r);
        menor++;
        if(r<rmenor && solucao==1)
        {
            resposta=menor;
            solucao=0;
    	}
        rmenor=r;
    }
    
    printf("%i\n", resposta);
    
    return 0;
}
