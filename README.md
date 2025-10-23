# Module-3 Day-3 SEB
## AIM:
To create  a C program to read n elements as input and print the elements of an array present on even position

## For example:

## Program:
```c
#include <stdio.h>

int main()
{
    int n, i;
    scanf("%d",&n);
    int a[n];
    for(i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
    }
    for(i=1;i<n;i++)  
    {   if(i%2!=0){
        printf("%d ",a[i]);
    }
    }
    return 0;
}
```
## Result:
