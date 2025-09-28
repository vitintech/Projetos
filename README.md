# Projetos
#include <stdio.h>
#include <stdlib.h>

int main(){
    int opcao, continuar;

    while (1){
    printf("BANCO DO BRASIL \n");

    printf("=============== \n");
   
    printf("\n Bem - Vindo de Volta \n");
    printf("1- Verificacao de saldo \n");
    printf("2- Deposito \n");
    printf("3- Saque \n");
    printf("4- Sair \n");
    printf("Escolha uma opcao: ");
    scanf("%d", &opcao);

    switch (opcao){
    case 1: opcao = 1;
        printf("\nSaldo verificado com sucesso: R$ 1000,00 \n");
        break;

    case 2: opcao = 2;
       printf("\nDeposito efetuado com sucesso: R$ 1000,00 \n");
       break;

    case 3: opcao = 3;
       printf("\nSaque realizado com sucesso: R$ 1000,00 \n");
       break;

    case 4: opcao = 4;
       printf("\nTudo certo, tenha um otimo dia \n");
       break;
    default:
       printf("\nOpcao invalida: \n");
        break;
    }
    if (opcao == 4){
        break;
    }
    else{
        printf("\nDeseja voltar as opcoes? (1- sim ou 2- nao): ");
        scanf("%d", &continuar);

        if (continuar == 2){
            printf("\nTudo certo, tenha um otimo dia\n");
            break;
        }
    }
}
system("\n pause");
return 0;
