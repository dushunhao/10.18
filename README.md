#define _CRT_SECURE_NO_WARNINGS 

#include<stdio.h>

int main(void)

{

	int data1, data2, sum;
	
	char op;
	
	printf("请输入data1+data2\n");
	
	scanf("%d%c%d", &data1, &op, &data2);
	
	printf("%d%c%d=%d\n", data1, op, data2, data1 + data2);

	int a = 0;
	
	int b = 0;
	
	float x = 0;
	
	float y = 0;
	
	scanf("%d%d", &a, &b);
	
	printf("a=%d,b=%d\n", a, b);
	
	scanf("%f%f", &x, &y);
	
	printf("x=%5.2f,y=%5.2f\n", x, y);

	int a;
	
	char b;
	
	float c;
	
	printf("请输入int：");
	
	scanf("%d",&a);
	
	printf("int:%d\n",a);
	
	printf("请输入char：");
	
	getchar();//或下一行%c前加空格
	
	scanf("%c",&b);
	
	printf("char:%c\n", b);
	
	printf("请输入float：");
	
	getchar();
	
	scanf("%f",&c);
	
	printf("float:%f\n", c);

	int a, b;
	scanf("%2d%*2s%2d",&a,&b);
	
	printf("%d,%d\n",a,b);
	
	int a, b;
	
	scanf("%2d%2d",&a,&b);
	
	printf("a=%d,b=%d\n",a,b);
	
        int a = 12, b = 15;
	
	printf("a=%d,b=%d\n",a,b);
	
	char c1 = 'a', c2 = 'b', c3 = 'c';
	
	printf("a%cb%cc%c\n",c1,c2,c3);
	
	return 0;
}

{
	char ch;
	
	printf("input\n");
	
	ch=getchar();
	
	ch -= 32;
	
	putchar(ch);
	
	putchar('\n');
	
	printf("%c,%d\n",ch,ch);
	
	return 0;
}

{
	int num1 = 0;
	
	int num2 = 0;
	
	int sum = 0;
	
	scanf("%d%d",&num1,&num2);
	
	sum = num1 + num2;
	
	printf("sum=%d\n",sum);
	
	return 0;
}




int main()
{
	printf("加入\n");
	
	int line = 0;
	
	while (line<= 10000)
	
	{
		line++;
		
		printf("敲一行代码:%d\n",line);
    }
	if (line > 10000)
	
		printf("好offer\n");
		
	return 0;
	
}

{
	int input = 0;
	
	printf("加入\n");
	
	printf("你要好好学习吗?\n(1)好好学习(2)不好好学习>:");
	
	scanf("%d",&input);
	
	if (input == 1)
	{
		printf("好offer\n");
	}
	else
	{
		printf("卖红薯\n");
	}
	return 0;
	
	
}

int main()

{
	char arr1[] = "abc";
	
	char arr2[] = { 'a','b','c','\0'};
	
	printf("%s\n",arr1);
	
	printf("%s\n",arr2);
	
	printf("%d\n",strlen(arr1));
	
	printf("%d\n",strlen(arr2));
	
	return 0;
}

enum Sex

{

	MALE,
	
	FEMALE,
	
	SECRET
};


int main()
{
	printf("%d\n", MALE);
	
	printf("%d\n", FEMALE);
	
	printf("%d\n", SECRET);
	
	return 0;
}



int main()
{
	int a = 10;
	
	int b = 20;
	
	int max = 0;
	
	max = (a > b ? a : b);
	
	printf("max=%d\n",max);
	
	return 0;
}
int main()
{
	int a = 0;
	
	printf("%d\n",!a);
	
	return 0;
}
int main()
{
	int a = 2;//010
	
	int b = 5;//101
	
	int c = a ^ b;
	
	printf("c=%d\n",c);
	
	return 0;
}

int Add(int x, int y)

{
	int z = x + y;
	
	return z;
	
}
int main()
{
	int num1 = 10;
	
	int num2 = 20;
	
	int sum1 = 0;
	
	int sum2 = 0;
	
	int a = 100;
	
	int b = 200;
	
	sum1 = Add(num1, num2);
	
	sum2 = Add(a, b);
	
	printf("sum=%d\n", sum1);
	
	printf("sum=%d\n", sum2);
	
	return 0;
	
}

int main()

{

	int a = 3;
	
	int b = 5;
	
	int c = a && b;
	
	printf("c=%d\n",c);
	
	return 0;
}

int Max(int x, int y)

{
	if (x > y)
		return x;
	else
		return y;
}

int main()

{
	int num1 = 20;
	
	int num2 = 40;
	
	int max = 0;
	
	max = Max(num1, num2);
	
	printf("max=%d\n",max);
	
	return 0;
	
}

int main()

{
	int a = 1;
	
	int b = a << 1;
	
	printf("b=%d\n", b);
	
	return 0;
}

int main()

{
	int arr[10] = { 1,2,3,4,5,6,7,8,9,10 };
	
	int i = 0;
	
	while (i < 10)
	
	{
		printf("%d\n", arr[i]);
		
		i++;
	}
	printf("arr[4]=%d\n",arr[4]);
	
	return 0;
	
}

int Add(int x, int y)

{
	int z = x + y;
	
	return z;
}
int main()
{
	int num1 = 25;
	
	int num2 = 52;
	
	int sum1 = 0;
	
	int sum2 = 0;
	
	int a = 100;
	
	int b = 200;
	
	sum1 = Add(num1,num2);
	
	sum2 = Add(a, b);
	
	printf("sum=%d\n",sum1);
	
	printf("sum=%d\n",sum2);
	
	return 0;
}
{
	int a = (int)3.14;
	
		printf("%d\n",a);
		
	return 0;
}
int main()
{
	int a = 0;
	
	int b = ~a;
	
	printf("%d\n",b);
	
	return 0;
}
int main()

{
	int a = 0;
	
	int arr[] = { 1,2,3,4,5,6 };
	
	printf("%d\n",sizeof(a));
	
	printf("%d\n",sizeof(int));
	
	printf("%d\n",sizeof(arr));
	
	printf("%d\n",sizeof(arr)/sizeof(arr[0]));
	
	return 0;
}
int Max(int x,int y)
{
	if (x > y)
		return x;
	else
	    return y;
}
int main()
{
	int num1 = 10;
	
	int num2 = 20;
	
	int max = 0;
	
	max = Max(num1, num2);
	
	printf("max=%d\n",max);
	
	return 0;
}
int main()
{
	int num1 = 10;
	
	int num2 = 20;
	
	if (num1 > num2)
	{
	    printf("较大的是：%d\n", num1);
	}
	else
	{
		printf("较大的是：%d\n",num2);
	}
	return 0;
}

int main(void)
{
	char ch;
	
	printf("input\n");
	
	ch=getchar();
	
	ch -= 32;
	
	putchar(ch);
	
	putchar('\n');
	
	printf("%c,%d\n",ch,ch);
	
	char a, b;
	
	int c;
	
	scanf("%c*%c*%d", &a, &b, &c);
	
	printf("%c,%c,%d\n", a, b, c);
	
	printf("%-2c%-2c%d\n",a,b,c);
	
	printf("%c,%c,%d\n", a, b, c);
	
	return 0;
}
{
	int a = 0;
	
	int b = 0;
	
	float x = 0;
	
	float y = 0;
	
	scanf("%d%d", &a, &b);
	
	printf("a=%d,b=%d", a, b);
	
	scanf("%f%f", &x, &y);
	
	printf("x=%f,y=%f\n", x, y);
	
	return 0;
}

int main()

void main()
{
	char c1, c2;
	
	scanf("%c", &c1);
	
	c2 = c1 + 32;
	
	printf("%c,%c", c1, c2);
	
}
{

	int a, b, temp;

	printf("输入整数a,b:");

	scanf("%d%d", &a, &b);

	temp = a;
	
	int c;
	
	c = a;
	
	a = b;
	
	b = c;
	
        printf("a=%d  b=%d\n", a, b);

}


 int main()

{
    long int i;

	double bonus1, bonus2, bonus4, bonus6, bonus10, bonus;



	scanf("%ld",&i);

	bonus1 = 100000 * 0.1;
	bonus2 = bonus1 + 100000 * 0.75;
	bonus4 = bonus2 + 200000 * 0.5;
	bonus6 = bonus4 + 200000 * 0.3;
	bonus10 = bonus6 + 400000 * 0.15;



		if (i <= 100000)
		{
			bonus = i * 0.1;
		}
		else if (i <= 200000)
		{
			bonus = bonus1 + (i - 100000)*0.075;
		}
		else if (i <= 400000)
		{
			bonus = bonus2 + (i - 200000)*0.05;
		}
		else if (i <= 600000)
		{
			bonus = bonus4 + (i - 400000)*0.03;
		}
		else if (i <= 1000000)
		{
			bonus = bonus6 + (i - 600000)*0.015;
		}
		else

			bonus = bonus10 + (i - 1000000)*0.01;



		printf("bonus=%f", bonus);
		return 0;

}

int Max(int x, int y)
{
	if (x > y)
		return x;
	else
		return y;
}
int main()
{
	int x = 1234, y = 123, z = 12;
	
	printf("%4d+%3d+%2d", x, y, z);

	int k, i = 2, j = 4;
	
	k = (++i)*(j--);
	
	printf("k=%d\n", k);
	
	int a = 30;
	
	int b = 0;
	
	printf("请玩家输入猜的数:\n");
	
	scanf("%d", &b);
	
	if (b < a)
	
	{
		printf("错误！\n提示:太小了");
		
	}
	else if (b > a)
	{
		printf("错误！\n提示:太大了");
	}
	else
	{
		printf("恭喜你答对了\n答案为%d\n",a);
	}
{
	printf("你准备好了吗？？？\n");
	
	int line = 0;
	
	while (line < 10000)
	
	{
		line++;
		
		printf("你努力敲代码,第%d行\n", line);
	}
	if (line >= 10000)
	{
		printf("恭喜你成功了\n");
	}
}
	int a = 10;
	
	printf("%d\n", a);
	
	printf("%d\n", !a);

	int a;
	printf("Input:\n");
	
	scanf("%d", &a);
	
	if (a%2==0)
	{
		printf("a是偶数\n");
	}
	else
	{
		printf("a是奇数\n");
	}

	int a;
	
	printf("Input:\n");
	
	scanf("%d", &a);
	
	if (a < 0)
	{
		a = -a;
		printf("a=%d\n",a);
	}
	else
	{
		printf("a=%d\n",a);
	}

	int a, b, max;
	
	printf("Input a,b\n");
	
	scanf("%d,%d", &a, &b);
	
	if (a > b)
	{
		max = a;
	}
	else
	{
		max = b;
	}
	printf("max=%d\n", max);

	int a, b;
	
	printf("Input a,b\n");
	
	scanf("%d,%d", &a, &b);
	
	int max=Max(a, b);
	
	printf("max=%d\n", max);
	
	int a, b, max;
	
	printf("Input a,b\n");
	
	scanf("%d,%d", &a, &b);
	
	if (a > b)
	{
		max = a;
	}
	if (a <= b)
	{
		max = b;
	}
	printf("max=%d\n", max);

	int data1, data2, sum;
	
	char op;
	
	printf("请输入data1+data2\n");
	
	scanf("%d%c%d", &data1, &op, &data2);
	
	printf("%d%c%d=%d\n", data1, op, data2, data1 + data2);
	
	return 0;
}

int main()
{
	int N;

	scanf("%d", &N);

	while (N > 0)
	{
		printf("%d\n", N);
		
		N--;
	}
	
	return 0;
}
{
	int a, b, c, d, Sum;
	
	float Average;
	
	scanf("%d %d %d %d", &a, &b, &c, &d);
	
	Sum = a + b + c + d;
	
	Average = Sum / 4.0;
	
	printf("Sum=%d;Average=%.1f", Sum, Average);
	
	return 0;
}



int Add(int x, int y)
{
	int z = x + y;
	
	return z;
}
void test()
{
	int a = 1;
	
	a++;
	
	printf("a=%d\n", a);
}

int main()
{
	int i = 0;
	
	while (i < 5)
	{
		test();
		
		i++;
	}

	int a = 10;
	
	printf("%d\n", a);
	
	printf("%d\n",!a);

	char arr1[] = "abc";
	
	char arr2[] = { 'a','b','c','\0' };
	
        printf("%s\n", arr1);
	
	printf("%s\n", arr2);
	
	printf("%d\n", strlen(arr1));
	
	printf("%d\n", strlen(arr2));
	
	int arr[10] = { 0 };
	
	int sz = 0;
	
	printf("%d\n", sizeof(arr));
	
	sz = sizeof(arr) / sizeof(arr[0]);
	
	printf("sz=%d\n", sz);

	int a = 10;
	
	printf("%d\n", sizeof(a));
	
	printf("%d\n", sizeof(int))
	;
	printf("%d\n", sizeof a);

	int arr[10] = { 1,2,3,4,5,6,7,8,9,10 };
	
	int i = 0;
	
	while (i < 10)
	
	{
		printf("%d\n", arr[i]);
		i++;
	}

	int num1 = 10;
	
	int num2 = 20;
	
	int sum = 0;
	
	int a = 100;
	
	int b = 200;
	
	//sum = Add(num1, num2);
	
	sum = Add(a, b);
	
	printf("sum=%d\n", sum);
	
	return 0;
}
