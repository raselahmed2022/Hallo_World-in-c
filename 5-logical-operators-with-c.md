# Hello World in C

## Code


#include <stdio.h>
#include <math.h>
#include <stdbool.h>

int main()
{
   int a = 4;
	int b = 3;
	int c = -4;
	int d = -3;

	bool res1;
	bool res2;

	res1 = a > b && c < d;
	res2 = !(a > b || c > d);

	//printf("res1 = %d\n", res1);
	//printf("res2 = %d\n", res2);

	printf("a > b && c < d;    res1 = %d\n", res1);
	printf("!(a > b || c > d); res2 = %d\n", res2);

	return 0;
}
