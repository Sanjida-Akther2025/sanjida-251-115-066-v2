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
solution 1
```c
#include<stdio.h>
int main()
{
    int A,B,sum=0;
    scanf("%d %d",&A,&B);
    sum=A+B;
    printf("%d",sum);
    return 0;

}
```
solution 5
```c
#include<stdio.h>
#define pi 3.14159
int main()
{
    float r,c,d;
    scanf("%f",&r);
     c=2*pi*r;
     d=2*r;
    printf("%.5f", c/d);

    return 0;

}
```
