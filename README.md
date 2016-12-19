# c-programing
#include <stdio.h> 
int main()
{
	float a,b,c,d,e;
	printf("Case I:please input five floating-point numbers\n");
	scanf("%f %f %f %f %f",&a,&b,&c,&d,&e);
	float s=a+b+c+d+e;
	printf("sum:%f\n",s);
	printf("average:%f\n\n",s/5);
	float x,sum=0;
	printf("Case II:please input five floating-point numbers:\n") ;
	scanf("%f",&x);
	sum=sum+x;
	scanf("%f",&x);
	sum=sum+x;
	scanf("%f",&x);
	sum=sum+x;
	scanf("%f",&x);
	sum=sum+x;
	scanf("%f",&x);
	sum=sum+x;
	printf("sum=%f\n",sum);
	printf("average=%f",sum/5);
	return 0;		
}
