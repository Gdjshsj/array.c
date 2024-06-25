 #include<stdio.h>
int main()
{
    int n,ar[1000],sum;
    scanf("%d",&n);
    for(int i=0;i<n;i++)
    scanf("%d",&ar[i]);
    for(int i=0;i<n;i++)
    sum=sum+ar[i];
    printf("%d",sum);
}
