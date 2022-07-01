#include <stdio.h>
#include <stdlib.h>
int main()
{
	int cont;
	float nota1, nota2, nota3, media;
	cont=1;
	while(cont<=40)
	{
		printf("Digite a 1a nota: \n");
		scanf("%f", &nota1);
		printf("Digite a 2a nota: \n");
		scanf("%f", &nota2);
		printf("Digite a 3a nota: \n");
		scanf("%f", &nota3);
		media=(nota1+nota2+nota3)/3;
	if(media>=7)
		{
		printf("Aluno foi APROVADO com a media igual a: %.2f\n", media);
		}
	else
		{
		printf("Aluno foi REPROVADO com a media igual a: %.2f\n", media);
		}
	cont++;
	}
	return 0;
}