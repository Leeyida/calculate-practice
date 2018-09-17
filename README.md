# calculate-practice
1.1
#include<stdio.h>
int main()
{
	float a,b;
	char c;
	printf("int expression:\n");
	scanf("%f%c%f",&a,&c,&b);
	switch(c)
	{
		case '+':
			printf("=%f\n",a+b);break;
		case '-':
			printf("=%f\n",a-b);break;
		case '*':
			printf("=%f\n",a*b);break;
		case '/':
			if(b==0)
				printf("Dvision by zero!\n");
			else 
				printf("=%f\n",a/b);
			break;
		default :
			printf("Operator error!\n");
			}
	return 0;
}
