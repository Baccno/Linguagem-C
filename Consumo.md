#include <stdio.h>
 
int main() {
 
    double km, x, y;
    scanf("%lf", &x);
    scanf("%lf", &y);
    km=x/y;

    printf("%.3lf km/l\n", km);
    return 0;
}
