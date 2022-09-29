# c-programming
#include <stdio.h>     

int main() {  

    int x, y, *p1, *p2;  

    printf("Please Enter Two different values\n");  
    scanf("%d %d", &x, &y);  
    
    p1 = &x;
    p2 = &y;

    if(*p1 > *p2) 
	{
         printf("The maximum = %d\n", *p1);  
    } 
	else if (*p2 > *p1)
	{ 
        printf("The maximum = %d\n", *p2); 
    } 
	else 
	{
		printf("Both are Equal\n");
    }
   
    return 0;  
}
