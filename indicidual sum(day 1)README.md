# c-programming
#include<stdio.h>
int main()
{
    int n,sum=0;
    scanf("%d",&n);
    int a[n];
    for(int i=1;i<n;i++){
        if(i<=n){
    scanf("%d",&a[i]);
     sum+=a[i];
        }
    }
    printf("%d",sum);
}
