# c-programming
#include <stdio.h>
int main()
{
    int n;
    printf("Enter size of the array:\n");
    scanf("%d",&n);
    int a[n],i;
    printf("Enter array elements:\n");
    for(i=1;i<=n;i++){
        scanf("%d",&a[i]);
    }
    int p;
    printf("Enter element to search:\n");
    scanf("%d",&p);
    for(i=0;i<n;i++){
        if(a[i]==p){
            printf("Given element %d is found at %d",p,i);
        }
    }
    
    return 0;
}
