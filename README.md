# A1065542_HW01
大學入門_作業4
#include <stdio.h>
#include <stdlib.h>

int main(){
	int a = 3;
	float b = 5.5;

	printf("%d %d %d %d\n",a+b,a-b,a*b,a/b);//结果乱码
	printf("%f %f %f %f\n",a+b,a-b,a*b,a/b);//结果正常

	system("PAUSE");
	return 0;
}
