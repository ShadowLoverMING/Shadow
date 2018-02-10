# Shadow
Plan A

```
#include <stdio.h>
int main()
{   int n,i,j;
    for (i=1;i<=9;i++)
      printf("%-4d",i);
    printf("\n");
    for(i=1;i<=9;i++)
     for(j=1;j<=i;j++) 
     {  printf("%-4d",i*j);
        if(j==i)
          printf("\n");
      }
    return 0;
}
```

```
#include <stdio.h>
int main( )
{  int i,j,n;
   printf("\nPlease Enter n:");
   scanf("%d",&n);
   for(i=1;i<=n;i++)
   {  for(j=1;j<=n-i;j++)
         printf(" ");
      for(j=1;j<=2*i-1;j++)
         printf("*");
      printf("\n"); 
   }
   return 0; 
 }
 ```
 
