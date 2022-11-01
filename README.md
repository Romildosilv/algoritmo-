# algoritmo-
Categoria //

#include <stdio.h>

int idade;

int main(){


	printf("digite a sua idade\n");
	scanf("%d",&idade);
if (idade<=0 && idade>=100){
	if (idade>=5 && idade<=7){
	printf ("\ncategoria e infantil");
     }
	else if (idade>=8 && idade<=10){
		printf("\ncategoria e juvenil");
	}
	else if (idade>=11 && idade<=15){
		printf("\ncategoria e adolescente");
	}
	else if (idade>=16 && idade<=30){
		printf("\ncategoria e adulto");
	}
	else if (idade>30){
	printf("\ncategoria e senior");
	}
}
else {
	printf("\ncategoria invalida");
}
	
	return 0;
}


