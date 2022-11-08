# exerc-cios-de-c-2
exercícios de c = 
//  by mhttpmarin2s \\

#include <stdio.h>
#include <stdlib.h> 
#include <locale.h> 

int main()
{   
    setlocale(LC_ALL,"");
    printf("Ler o nome de uma pessoa na forma “nome” seguido por “sobrenome” e \n escrever na forma “sobrenome” seguido por “nome”. ");
    char a [100], b [100]; 
    printf("Digite seu nome > \n ");
    scanf("%s",a);
    fflush(stdin);
    printf("\nDigite seu sobrenome > \n ");
    scanf("%s",b);
    fflush(stdin);
    printf ("olá, é um prazer te receber aqui  %s, %s ", b, a ); 
    
    
      

    return 0;
}
