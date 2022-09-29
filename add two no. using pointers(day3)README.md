# c-programming
#include <stdio.h>

int main()
{
  int *p,*q;
  int n1,n2;
  p=&n1;
  q=&n2;
  printf("Enter two numbers:\n");
  scanf("%d %d",p,q);
  printf("\nsum of %d and %d:%d",*p,*q,*p+*q);
}
