# c-programming
#include<stdio.h>
#include<math.h>
int main(){
    int l;
    scanf("%d",&l);
 int a, b, c = 0;
        int m = 2;
        while (c < l) {
            for (int n = 1; n < m; ++n) {
                a = m * m - n * n;
                b = 2 * m * n;
                c = m * m + n * n;
 
                if (c > l){
                printf("Enter correct input");
                    break;
                }
 
                printf("(%d,%d,%d),",a,b,c);
            }
            m++;
}
}
