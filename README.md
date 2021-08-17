# test_8_10
#include <stdio.h>

int main()
{
	int i=0;
	scanf("%d",&i);
	printf("%d\n",i);
	return 0;
}

//void Exchange(int *p,int *q)
//{
//	int w=*p;
//	*p=*q;
//	*q=w;
//}
//
//int main()
//{
//	int a=1;
//	int b=3;
//	Exchange(&a,&b);
//	printf("a=%d\nb=%d\n",a,b);
//	return 0;
//}


//extern：声明外部符号

//int main()
//{
//	int num =0;
//	printf("%p\n",&num);//%p：以地址形式打印
//	return 0;
//}


//int g=1;
//
//void test()
//{
//	printf("test g=%d\n",g);
//}
//
//int main()
//{
//	int num1=0;
//	int num2=0;
//	int sum=0;
//	test();
//	scanf("%d%d%d",&num1,&num2,&g);//输入函数，&：取地址符号；&num：num的地址
//	sum=num1+num2;
//	printf("sum=%d\ng=%d\n",sum,g);
//	test();
//	return 0;
//}


//局部变量和全局变量的名字建议不一样，容易产生bug；
//二者同时存在时，局部变量优先；
//局部变量：仅在当前范围内使用；
//全局变量：作用域是整个工程；

//int main()
//{
//	float w=8.2;
//	float i=81.2;
//	double p=80.2;
//	double q=881.21;
//	float e=888.2;
//	int a=2^10;
//	int b=2^5;
//	char c='2^3';
//	printf("%f\n",i);
//	printf("%f\n",p);
//	printf("%f\n",q);
//	printf("%f\n",w);
//	printf("%f\n",e);
//	printf("%d\n",a);
//	printf("%d\n",b);
//	printf("%d\n",c);
//	printf("%c\n",c);
//	return 0;
//}

//int main()
//{
//	char i=10;
//	printf("");
//	scanf("");
//	return 0;
//}



//int main()
//{
//	printf("%d\n",sizeof(char));
//	printf("%d\n",sizeof(int));
//	printf("%d\n",sizeof(short));
//	printf("%d\n",sizeof(long));
//	printf("%d\n",sizeof(long long));
//	printf("%d\n",sizeof(float));
//	printf("%d\n",sizeof(double));
//	return 0;
//}

//int main()
//{
	//char ch='A';
	//printf("%c\n",ch);   //%c：打印字符格式的数据
	//				////以字符的形式打印ch，并换行
	
	//int age=18;
	//printf("%d\n",age);//%d：打印整形十进制数据
	//return 0;

	//float f=5.20;
	//double n=5.21;
	//printf("%f\n%lf\n",f,n);//打印单精度的时候用%f--float，双精度一般用%lf--long float
//}


//20：整形
//50.5：浮点型
//int		整形			4byte: 32位二进制/32个bit位=2^32-1个数字
//short		短整型
//long		长整形
//long long
//char：字符类型：'A'
//float：		单精度浮点型
//double：	双精度浮点型

//%d--打印整形
//%c--打印字符
//%f--打印浮点型（小数）
//%p--以地址的形式打印
//%x--打印十六进制数字



//#include <stdio.h>			//包含一个叫stdio.h的文件（引用/使用stdio.h文件）
//							////stdio.h：standard input output .head：标准输入输出流的头文件
////int main(){
////	printf("%d\n",strlen("abcde"));
////	return 0;
////}
//
////int main(){
////	int a=0;
////	int b=0;
////	int Add=0;
////	printf("请输入两个数字:>");
////	scanf("%d %d",&a,&b);
////	Add=a+b;
////	printf("a=%d\nb=%d\n",a,b);
////	printf("Add=%d\n",Add);
////	return 0;
////}
//
//int main()     ////主函数-程序的入口-main函数有且只有一个
//				////main前面的int表示main函数调用后返回一个整形值
//{
//	printf("hehe\n");   //printf--print function：打印函数
//	return 0;   //返回值 0
//}
