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

ATIVIDADE 2
#include<stdio.h>

int main() {
	float nota1;
	float nota2;
	float nota3;
	float nota4;
	float media;
	
	printf("digite a primeira nota do aluno:");
scanf("%f", &nota1);
	printf("digite a segunda nota do aluno:");
	scanf("%f", &nota2);
	printf("digite a terceira nota do aluno:");
	scanf("%f", &nota3);
	printf("digite a quarta nota do aluno:");
	scanf("%f", &nota4);

	media = (nota1 + nota2 + nota3 + nota4) / 2.0;
	printf("A media das notas do aluno e: %.2f\n", media);

	return 0;
}

ATIVIDADE 3
#include<stdio.h>

int main(){
	
float base;
float altura;

printf("escreva o valor da altura do retangulo:");
scanf("%f", &altura);
printf("escreva a qual o valor base do retngulo:");
scanf("%f", &base);

float total = base * altura;

printf("o calculo da area do retangulo e:, %.2f\m", total);

return 0;

}

ATIVIDADE 4
#include<stdio.h>

int main ()
{
	float contador;
    float valor1, valor2;
    
    printf("digite um valor:");
    scanf("%f", &valor1);
    printf("digite outro valor:");
    scanf("%f", &valor2);
    float total = valor1 - valor2;
    printf("a diferenca entre os dois valores e de: %f", total);
 
    return 0;
    
}

ATIVIDADE 5
#include<stdio.h>

int main ()
{
    float valor1, valor2;
    float media;
	    
    printf("digite um valor:");
    scanf("%f", &valor1);
    printf("digite outro valor:");
    scanf("%f", &valor2);
    media = valor1 / valor2;
    printf("o valor da divisao dos dois valores e: %.2f\n", media);
 
    return 0;
    
}

 ATIVIDADE 6
 	#include<stdio.h>
	
	int main ()
	{
	    float peso;
	    float gramas;
		    
	    printf("digite o seu peso:");
	    scanf("%f", &peso);
	    
	float total = peso * 1000;
	    
	    printf("o valor do seu peso em gramas e de: %f", total);
	 
	    return 0;
	    
	}
	
	ATIVIDADE 7

 	#include<stdio.h>
	
	int main ()
	{
	    float quilogramas;
	    float valor = 45.00;
	    
	    
		    
	    printf("peso do prato:");
	    scanf("%f", &quilogramas);
	    
	    
	float total = quilogramas * valor;
	    
	    printf("o valor do seu prato e de: %f", total);
	 
	    return 0;
	    
	}
	
	 ATIVIDADE 8
