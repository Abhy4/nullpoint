# nullpoint
/ nullpoint
/simple Calculator
#include<stdio.h>
int main()
{
    int a,b,c,d,ch,n,m;
    printf("enter your choice\n");
    printf("\n1:Addition");
    printf("\n2:Subtraction");
    printf("\n3:Division");
    printf("\n4:Multiplication");
    scanf("%d",&ch);
    printf("enter any two numbers");
    scanf("%d%d",&n,&m);
    switch(ch)
    {
    case 1:
        a=n+m;
        printf("%d is the Addition",a);
        break;

    case 2:
        b=n-m;
        printf("%d is the Subtraction",b);
        break;  

    case 3:
        c=n/m;
        printf("%d is the Division",c);
        break;

    case 4:
        d=n*m;
        printf("%d is the Multplication",d);
        break;  
    default:
    printf("Individual Error");
    break;    
    }
        return 0;
        }
