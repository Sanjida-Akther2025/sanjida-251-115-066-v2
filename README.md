solution number  4 :
```c
#include<stdio.h>
int main()
{
    int K,M;
scanf("%d %d",&K,&M);
int r =K%M;
printf("%d\n",r);
return 0 ;
}
```

solution number 2:
```c
#include<stdio.h>
int main()
{
    int a;
  scanf("%d",&a);
  for(int i=1;i<=a;i++){
  if(a%i == 0)
    printf("%d\n",i);}
  return 0 ;
}
```
solution number 3
```c
include<stdio.h>
int main()
{
    int N,i;
    scanf("%d",&N);
    int a[N];
    for(i=0; i<N; i++)
    {
        scanf("%d",&a[i]);
    }
    int p = a[0],f=0;
    for(i=1; i<N; i++)

        if(a[i]<p)
        {
            f=1;
        }
    p = a[i];
    if(f==0)
        printf("Yes\n");
    else
    {
        printf("No\n");
    }
    return 0 ;
}
```
solution 6
```c
#include<stdio.h>
int main()
{
    int n ,i;
    scanf("%d",&n);
    for(i=1;i<n;i++)
        n=n/i;
    {
        printf("%d",n);
    }
    return 0 ;
}
```
