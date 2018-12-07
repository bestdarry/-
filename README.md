# -
a little boy only
/*------------------------------------------------


功能：求两个整数的最大公约数。

------------------------------------------------*/

#include<stdio.h>


int gcd(int n,int m)
{
  /**********Program**********/
  int a=m,b=n,r;
  while(a) { r=b%a;b=a;a=r;
  } 
  return a;
  
  
  /**********  End  **********/
}

main()
{
  int n,m,result;
  scanf("%d%d",&n,&m);
  result=gcd(n,m);
  printf("the gcd is %d\n",result);

}
