#include<stdio.h>
int main(){
	int F,H;
	float S;
	double TS;
	
	scanf("%d %d %f", &F,&H,&S);
	TS = H*S; 
	printf("NUMBER = %d\n",F);
	printf("SALARY = U$ %.2lf\n",TS);
	return 0;
}
