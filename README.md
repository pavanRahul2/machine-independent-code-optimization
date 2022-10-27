# machine-independent-code-optimization
#include <stdio.h>
#include<conio.h>
int main(){
    int f=1,n;
    printf("enter the number: ");
    scanf("%d",&n);
    do{
        f=f*n;
        n--;
    } while(n>0);
    printf("the factorial value is :%d",f);
    return(0);
}


#include <stdio.h>
#include<conio.h>
int main(){
    int i,n;
    int fact=1;
    printf("enter the number: ");
    scanf("%d",&n);
    for(i=n;i>=1;i--)
    fact=fact*i;
    printf("the factorial value %d ",fact)
    return(0);
}
