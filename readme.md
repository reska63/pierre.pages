#include <stdio.h>
#include <stdlib.h>

int main()
{
int nombre1;
int nombre2;
char signe;
int resultat;

printf("Entrez le premier nombre:");
scanf("%s\n",&nombre1);
printf("Entrez le second nombre:");
scanf("%s\n",&nombre2);
printf("Entrez un signe(+,-,*,/):");
scanf("%c\n",&signe);
if (signe == "+");
{
resultat == nombre1 + nombre2;
printf("Le résultat est de:",resultat);
}

if(signe == "-");
{
resultat == nombre1 - nombre2;
printf("Le résultat est de:",resultat);
}

if(signe == "*")
{
resultat == nombre1 * nombre2;
printf("Le résultat est de:",resultat);
}
}

