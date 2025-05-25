# addition-of-two-matrices
#include<stdio.h>
int main()
{
int a[10][10],b[10][10],res[10][10],i,j,r,c;
printf("Enter no of rows, columns: ")
;scanf("%d%d",&r,&c);
printf("Elements of matrix 1: ");
for(i=0;i<r;i++)
{
for(j=0;j<c;j++
)
{
scanf("%d ",&a[i][j]);
}
}
printf("Elements of matrix 2: \n")
;
for(i=0;i<r;i++)
{
for(j=0;j<c;j++)
{scanf("%d",&b[i][j]);
}
}
printf("Addition of matrices:\n");
//logic
for(i=0;i<r;i++)
{for(j=0;j<c;j++)
{
res[i][j]=a[i][j]+b[i][j];
printf("%d ",res[i][j]);
}
printf("\n");
}
}
