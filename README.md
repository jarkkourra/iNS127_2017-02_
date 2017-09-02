# iNS127_2017-02_
Laboratorio 1 taller
#include<stdio.h>
int main() 
{ 
int i, num, pares[40], impares[40], sumapar=0, sumaimp,tot; 

printf("Ingrese cuantos numeros va a evaluar: ");
scanf("%d",&tot);

for(i=1; i<=tot; i++) 
{ 
printf("Introduce un numero: ", i); 
scanf("%d", &num); 
if( num % 2 == 0) 
{ 
pares[sumapar]=num; 
sumapar++; 
} 
else{ 
impares[sumaimp]=num; 
sumaimp++; 
} 
} 

printf("\n Los numeros pares son: "); 
for(i=0; i<sumapar; i++)printf(" %d ", pares[i]); 

printf("\n Los numeros impares son: "); 
for(i=0; i<sumaimp; i++)printf(" %d ", impares[i]); 

 
}
