#include <stdio.h>
 
int main() {
 
  double n;
 	int l,m,a,o,p,q,r,s,t,u,v,w;
    scanf("%lf", &n);
    l=n*100;
    m=l/10000;
    l=l%10000;
    a=l/5000;
    l=l%5000;
    o=l/2000;
    l=l%2000;
    p=l/1000;
    l=l%1000;
    q=l/500;
    l=l%500;
    r=l/200;
    l=l%200;
    s=l/100;
    l=l%100;
    t=l/50;
    l=l%50;
    u=l/25;
    l=l%25;
    v=l/10;
    l=l%10;
    w=l/5;
    l=l%5;
    printf("NOTAS:\n");
    printf("%d nota(s) de R$ 100.00\n",m);
    printf("%d nota(s) de R$ 50.00\n",a);
    printf("%d nota(s) de R$ 20.00\n",o);
    printf("%d nota(s) de R$ 10.00\n",p);
    printf("%d nota(s) de R$ 5.00\n",q);
    printf("%d nota(s) de R$ 2.00\n",r);
    printf("MOEDAS:\n");
    printf("%d moeda(s) de R$ 1.00\n",s);
    printf("%d moeda(s) de R$ 0.50\n",t);
    printf("%d moeda(s) de R$ 0.25\n",u);
    printf("%d moeda(s) de R$ 0.10\n",v);
    printf("%d moeda(s) de R$ 0.05\n",w);
    printf("%d moeda(s) de R$ 0.01\n",l);
    return 0;
}
