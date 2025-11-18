# bee1113-number-problem
[main.c](https://github.com/user-attachments/files/23599036/main.c)
#include <stdio.h>
#include <stdlib.h>

int main(){
int a,b;
while(1){
    scanf("%d %d",&a,&b);
    if(a==b)break;
    if(a>b)printf("Decrescente\n");
    if(a<b)printf("Crescente\n");
}
return 0;
}
