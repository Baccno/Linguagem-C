#include <stdio.h>
int main (){

    int i, a, b, c, d;
    
    while(scanf("%i", &d)!=EOF)
	{
    	b=20;
        for(i = 0;i < d;i++)
		{
            scanf("%i", &c);
            if(c<b){
                b=c;
                a=i+1;
            }
        }
        printf("%i\n", a);
    	a=0;
    }
    
return 0;
}
