#include <stdio.h>

int main()
{
    int arr[1000],n,sum=1;
    printf("enter n value:");
    scanf("%d",&n);
    printf("enter array elements:");
    for(int i=0;i<n;i++)
    scanf("%d",&arr[i]);
    for(int i=0;i<n;i++)
    sum=sum*arr[i];
    printf("sum of array elements:");
    printf("%d",sum);

    return 0;
}
