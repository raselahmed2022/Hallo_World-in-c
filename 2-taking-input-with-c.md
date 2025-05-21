# Taking input in C

## Code

#include <stdio.h>

int main()
{
    int i;			//integer to be read by the console
	char s[10];		//string to be read by the console

	//Ask the user to enter a number and read it with scanf
	//Number is saved in i
	printf("Enter a number: ");
	scanf("%d", &i);

	//Ask the user to enter a string and read it with scanf
	//String is saved in i (max. length: 10 signs)
	printf("Enter a string: ");
	scanf("%s", s);

	//show the values in the console
	printf("The number you have entered is: %d\n", i);
	printf("The string you have entered is: %s\n", s);

	return 0;
}
