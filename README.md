# ciao-ragazzi
Gênesis1:1 
/*Programa que lê um número natural, que representa a quantidade de dias
e exiba a quantidade equivalente de anos
Veronica Lemos*/

#include "stdio.h"
#include "math.h"  // biblioteca matematica//
#define ano 365
int main (void) {

int qtdias;
float qtanos;

printf("Escreva a quantidade de dias:\n");
scanf("%d", &qtdias);

qtanos = qtdias / ano;

printf("A quantidade de anos é: %.2f\n", qtanos);

return 0;
}
