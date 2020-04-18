#include "stdio.h"
#include "stdlib.h"

int MDC(int a,int b){
    int div=1,i,menor;
    
    if(a>b){
        menor=b;
    }else{
        menor=a;
    }
    for(i=1;i<=menor;i++){
        if(a%i==0 && b%i==0){
            div=i;
        }
    }

   return div;
}

int main(){
   
    int casos,i;
    scanf("%d",&casos);

    int vetor[casos];
    
    for(i=0;i<casos;i++){
        int num1,num2;
        scanf("%d %d",&num1,&num2);   
        vetor[i]=MDC(num1,num2);  
   }
    for(i=0;i<casos;i++){
        printf("%d\n",vetor[i]);
    }
    
    return 0;
}

