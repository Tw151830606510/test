# test
3
#include <stdio.h>

//int main()
//{
//	int a = 0;
//	for (a =0;a < 100; a++)
//	{
//		if (a % 3 == 0)
//			printf("%d ",a);
//	}
//	return 0;
//}			//0到100中3的倍数

//main()
//{
//	int year = 0;
//	for (year = 1000; year < 2000; year++)
//	{
//		if ((year % 4== 0) && (year % 100 != 0) || (year % 400 ==0))
//			printf("%d ",year);
//	}
//	return 0;
//}			//1000年到2000年的闰年

int main()
{
	int a = 0, b = 0;
	for (a = 1; a < 100; a++)
	{
		for (b=2; b < a; b++)
		{
			if (a % b == 0)
			{
				break;
			}
			if (b = a)
			{
				printf("%d ", a);
			}
		}
	}
	return 0;
}			//求质数
