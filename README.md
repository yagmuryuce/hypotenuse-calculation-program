# hypotenuse-calculation-program
```
#include <stdio.h>
#include <stdlib.h>
#include <math.h>

int main() {
	
	double A;
	double B;

	double hypotenuse;
	
	printf("\n Enter side A:");
	scanf("%lf",&A);
	printf("\n Enter side B:");
	scanf("%lf",&B);
	
	hypotenuse= sqrt((A*A)+(B*B));
	printf("\n Hypotenuse= %0.0lf",hypotenuse);

	

	return 0;
}
```
