//C program to find power of a number using recursion

#include<stdio.h>

double pow(double b, double p){
    if(p==0){
        return 1;
    }else if (p>0){
        return b * pow (b,p-1);
    }
}

int main (){
    int b,p,ans;
    printf("enter base ans power \n");
    scanf("%d %d", &b, &p);
    ans = pow(b,p);
    printf("ans = %d \n", ans);

    return 0;
}
