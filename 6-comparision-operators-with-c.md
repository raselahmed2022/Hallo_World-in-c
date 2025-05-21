# Hello World in C

## Code


#include <stdio.h>

int main()
{
    int a = 12;
	int b = 3;
	int c = 4;
	double d = 2.5;
	double e = 0.5;
	int f = 2;
	int g = -1;

	double res1;
	double res2;

	res1 = a - b >= c * d;
	res2 = e <= pow(f, g);

	printf("res1 = %g\n", res1);
	printf("res2 = %g\n", res2);

	//printf("a - b >= c * d; res1 = %g\n", res1);
	//printf("e <= pow(f, g); res2 = %g\n", res2);

	return 0;
}
