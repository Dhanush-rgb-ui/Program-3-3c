# Module-3 Day-3 SEB
## AIM:
To create  a C program to read n elements as input and print the elements of an array present on even position

## For example:
<img width="156" height="92" alt="image" src="https://github.com/user-attachments/assets/7f0bfe6d-0e88-4c69-932c-c520021e8a9a" />

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
<img width="342" height="193" alt="image" src="https://github.com/user-attachments/assets/ffd241fe-2a60-4cb7-b4c1-5ff4ac1c4af3" />
