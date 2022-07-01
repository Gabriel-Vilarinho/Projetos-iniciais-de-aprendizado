#include <stdio.h>
#include <stdlib.h>
int main()
{
	int cont, n, numeron, somarpar, somarimpar;
	somarpar=0, somarimpar=0;
	printf("Escolha um numero inteiro: \n");
	scanf("%d", &n);
	for(cont = 1; cont<=n; cont++)
	{
		printf("Os numeros sao: \n");
		scanf("%d", &numeron);
		if(numeron%2==0)
		{
		somarpar= somarpar + numeron;
	    }
		else
		{
		somarimpar = somarimpar + numeron;
		}
   }
		printf("A soma dos numeros pares e igual a: %d\n", somarpar);	
		printf("A soma dos numeros impares e igual a: %d\n", somarimpar);
	
}