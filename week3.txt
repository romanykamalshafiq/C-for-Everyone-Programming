#include<stdio.h>
#include<math.h> /* has  sin(), abs(), and fabs() */


int main(void)
{
double interval,val,result;
int i;
for(i = 0; i <30; i++)
{
 interval = i/10.0;
 result= fabs(sin(interval));
 printf("sin( %.4lf ) = %.4lf \t",interval ,result );
}


printf("\n+++++++\n");
return 0;
}
