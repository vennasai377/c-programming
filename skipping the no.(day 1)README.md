# c-programming
#include<stdio.h>
int main(){
    int p,q,r;
    scanf("%d %d %d",&p,&q,&r);
    int i=0;
    printf("Numbers are=");
    for(i=p;i<=q;i++){
        if(i%10!=r){
            printf("%d ",i);
        }
    }
}
