# trabalho-de-eng.-de-software
#include <stdio.h>
#include <locale.h>
float a , b,x1,x2;
float eixoX(){
return -b/a;
}
float eixoF(){
return b;
}



void main(){
setlocale(LC_ALL,"");
printf("insira o valor de A:\n");
scanf("%f",&a);
printf("insira o valor de B:\n");
scanf("%f",&b);
    printf("Eixo X  : %0.2f",eixoX());
printf("Eixo f(x)  : %0.2f",eixoF());
getch();
}
