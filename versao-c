#include <stdio.h>
#include <stdlib.h>
//função vez do X
void vezDoX(char tabuleiro[3][3]){
	sla <- "X"
	printf("Entre com a coordenada X: ");
	scanf("%d", &x);	
	
	printf("Entre com a coordenada Y: ");
	scanf("%d", &y);	
	tabuleiro[x][y] = sla;
}
//funçao vez do O
void vezDoO(char tabuleiro[3][3]){
	sla <- "O"
	printf("Entre com a coordenada X: ");
	scanf("%d", &x);	
	
	printf("Entre com a coordenada Y: ");
	scanf("%d", &y);	
	tabuleiro[x][y] = sla;
}
//funçao imprimir o tabuleiro
void imprime(int y, tabuleiro[3][3]){
	for(y = 1; y <= 3; y ++)
		printf("%c | ", &tabuleiro[1,y])
	prinf("\n");
	for(y = 1; y <= 3; y ++)
		printf("%c | ", &tabuleiro[2,y])
	prinf("\n");
	for(y = 1; y <= 3; y ++)
		printf("%c | ", &tabuleiro[3,y])
	prinf("\n");
}
//funçao teste - testa se o jogo acabou
void JogoAcabou(char tabuleiro[3][3]){
//casos em linhas
if (tabuleiro[1][1] == tabuleiro[1][2]) && (tabuleiro[1][2] == tabuleiro[1][3])
	acabou();
if (tabuleiro[2][1] == tabuleiro[2][2]) && (tabuleiro[2][2] == tabuleiro[2][3])
	acabou();
if (tabuleiro[3][1] == tabuleiro[3][2]) && (tabuleiro[3][2] == tabuleiro[3][3])
	acabou();
//casos em colunas
if (tabuleiro[1][1] == tabuleiro[2][1]) && (tabuleiro[2][1] == tabuleiro[3][1])
	acabou();
if (tabuleiro[1][2] == tabuleiro[2][2]) && (tabuleiro[2][2] == tabuleiro[3][2])
	acabou();
if (tabuleiro[1][3] == tabuleiro[2][3]) && (tabuleiro[2][3] == tabuleiro[3][3])
	acabou();
//casos em diagonal
if (tabuleiro[1][1] == tabuleiro[2][2]) && (tabuleiro[2][2] == tabuleiro[3][3])
	acabou();
if (tabuleiro[1][3] == tabuleiro[2][2]) && (tabuleiro[2][2] == tabuleiro[3][1])
	acabou();
acabou 
}
int main(){
	char tabuleiro[3][3], sla;
	int i, j, r;
	char espaco = " ";
	//inicializa tabuleiro
	for(x = 1; x >= 3; x++)
		for(y = 1; y >= 3; y++)
			tabuleiro[x][y] = espaco; 
	
	printf("Quem começa jogando(X ou O): ");
	scanf("%c", &opcao);
	int valido = 0;
	char vezDeQuem;
	do{	
		switch(opcao)
		{
			case "x":
				vezDoX();
				valido = 1;				
				vezDeQuem = "x"; 
				break;		
			case "o":
				vezDoO();
			    valido = 1;
				vezDeQuem = "o";
			default
				printf("Opçao invalida!! Nao vem zuar nao, viado");
		}	
	while(valido != 1);
	//verifica qual jogou e qual vai ser o prox jogador
	while 
	if(vezDeQuem == "x")
		vezDeQuem = "o"
		vezDoO();
	else
		if(vezDeQuem == "o")
			vezDeQuem = "x"
			vezDoX();
   //Imprime o tabuleiro
   //      _ | _ | Escreva (tabuleiro[x,y])   = 1.1, 1.2, 1.3
   //      _ | _ | _   = 2.1, 2.2, 2.3
   //        |   |     = 3.1, 3.2, 3.3
   //      _ | x | _   = vazio, 1.2 , vazio
   //      _ | _ | _   = 2.1, 2.2, 2.3
   //        |   |     = 3.1, 3.2, 3.3
//casos em linhas
if (tabuleiro[1][1] == tabuleiro[1][2]) && (tabuleiro[1][2] == tabuleiro[1][3])
	acabou();
if (tabuleiro[2][1] == tabuleiro[2][2]) && (tabuleiro[2][2] == tabuleiro[2][3])
	acabou();
if (tabuleiro[3][1] == tabuleiro[3][2]) && (tabuleiro[3][2] == tabuleiro[3][3])
	acabou();
//casos em colunas
if (tabuleiro[1][1] == tabuleiro[2][1]) && (tabuleiro[2][1] == tabuleiro[3][1])
	acabou();
if (tabuleiro[1][2] == tabuleiro[2][2]) && (tabuleiro[2][2] == tabuleiro[3][2])
	acabou();
if (tabuleiro[1][3] == tabuleiro[2][3]) && (tabuleiro[2][3] == tabuleiro[3][3])
	acabou();
//casos em diagonal
if (tabuleiro[1][1] == tabuleiro[2][2]) && (tabuleiro[2][2] == tabuleiro[3][3])
	acabou();
if (tabuleiro[1][3] == tabuleiro[2][2]) && (tabuleiro[2][2] == tabuleiro[3][1])
	acabou();
	
return 0;
}
