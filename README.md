# sum-of-natural-number
#include <stdio.h>
int main() {
    int n,i,sum=0;
    printf("Enter n value:");
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    {
        sum=sum+i;
    }
    printf("%d",sum);
}
    
    
    
