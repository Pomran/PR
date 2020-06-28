```c
#include <stdio.h> 
#include <math.h>

int main()
{
	int a,b;
	scanf("%d", &a);
	if (a <= 1)
		printf("非素数");
	else
	{
		double i = sqrt(a);
		for (b = 2; b < i / 2; b++)
		{
			if (a % b == 0)
			{
				printf("非素数");
				return 0;
			}
		}
		printf("素数");
	}
	
	return 0;
}
```
