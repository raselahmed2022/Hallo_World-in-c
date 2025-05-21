# Hello World in C

## Code
```c

Q1. find the perameter of the rectangle area

#include <stdio.h>
#include <math.h>
#include <stdbool.h>

int main()
{
  // Declare variables
    float length, width;
    const float CONVERSION_FACTOR = 10000;
    
    // Input values
    printf("Enter the length of the rectangle (in meters): ");
    scanf("%f", &length);
    
    printf("Enter the width of the rectangle (in meters): ");
    scanf("%f", &width);
    
    // Perform calculations
    float area = length * width;
    float perimeter = 2 * (length + width);
    float area_in_cm = area * CONVERSION_FACTOR;
    
    // Output results
    printf("Length: %.2f meters, Width: %.2f meters\n", length, width);
    printf("Area: %.2f square meters\n", area);
    printf("Perimeter: %.2f meters\n", perimeter);
    printf("Area in square centimeters: %.2f cm²\n", area_in_cm);
    
    

	return 0;
}
