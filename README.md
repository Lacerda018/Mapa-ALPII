# Mapa-ALPII

#include <stdio.h>
#include <stdlib.h>

/*programe um algoritmo em linguagem C para encontrar o quociente e o resto 
com base nos valores do dividendo e divisor inseridos pelo usuário.*/

int main(){

    int D, d, quo, rest;

    printf("Digite o valor do Dividendo:\n");
    scanf("%d", &D);
    fflush(stdin);

    printf("Digite o valor do divisor:\n");
    scanf("%d", &d);
    fflush(stdin);

    quo= D/d;
    rest=D%d;

    printf("o quociente e: %d.\n", quo);
    printf("O resto e: %d.\n", rest);

return 0;
}
