# Pattern-print
#include<stdio.h>
int main()
{   
    int row,col,n;
    printf("Enter the values of row:");
    scanf("%d",&n);
    for(row=1;row<=n;row++)
    {
        for(col=1;col<=n+1-row;col++)
        {
            printf("* ");
        }
        printf("\n");
    }
    return 0;
}
