# Arithmatic operations in C

## Code
#include <stdio.h>

int main()
{
   int i;
	int j;
	int result;
	
	printf("First number:  ");
	scanf("%d", &i);

	printf("Second number: ");
	scanf("%d", &j);

	result = i + j;
	printf("%d + %d = %d\n", i, j, result);

	return 0;
}
