```c
#include <stdio.h>   

int main()   
{   
    int a, b;
    
    scanf("%d", &a);
    for (b = 2;b < a;b++)
    {
        if (a % b == 0)
        {
            break;
    }
}

if (b>=a)
printf("素数\n");
else
printf("非素数\n");
   return 0;
}
```
