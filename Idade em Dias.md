#include <stdio.h>
 
int main() {
 
    int n,a,m,d;
    scanf("%d",&n);
    a=n/365;
    n=n%365;
    m=n/30;
    d=n%30;
    printf("%d ano(s)\n", a);
    printf("%d mes(es)\n", m);
    printf("%d dia(s)\n", d);
    
 
    return 0;
}
