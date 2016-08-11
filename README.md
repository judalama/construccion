# construccion
ing sistemas
#include <stdio.h> // entrada y salida datos
#include "iostream" // flujo de entrada datos
using namespace std; // Permite al programador tener acceso a todos los miembros del 4 namespace
 int main()
{
int suma=0; // declaracion de varible pára la suma de los numeros pares
	
for (int i=1;i<=1000;i++)
{
	if(i % 2==0){
	suma=suma+i;// asigna a suma lo que tiene suma más lo que tiene la varible i  	
	  }	
	}	
	
		printf("La suma de los numeros para es : %d ",suma);
 }
