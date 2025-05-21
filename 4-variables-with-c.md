# Variables in C

## Code
#include <stdio.h>

int main()
{
    int a = 3;
	double b = -2.5;
	int c = 4;
	int d = 2;
	double res1;
	double res2;

	res1 = a * b + c * d;
	res2 = a * (b + c) * pow(d, d);

	printf("res1 = %g\n", res1);
	printf("res2 = %g\n", res2);

	return 0;
}
