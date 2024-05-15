# primeiros-codigos-em-C
ATIVIDADE 1
#include <stdio.h>

int main() {
	float nota1;
	float nota2;
	float nota3;
	float nota4;
	
	printf("digite a primeira nota do aluno:");
scanf("%f", &nota1);
	printf("digite a segunda nota do aluno:");
	scanf("%f", &nota2);
	printf("digite a terceira nota do aluno:");
	scanf("%f", &nota3);
	printf("digite a quarta nota do aluno:");
	scanf("%f", &nota4);
	
	float total = nota1+nota2+nota3+nota4;
	printf("nota total: %f", total);
	return 0;
}
