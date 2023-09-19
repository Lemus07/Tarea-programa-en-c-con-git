//Tarea-programa-en-c-con-git
#include <stdio.h>
void main (void)
{
	int ancho, alto, izqx, upy, derx, downy;
	float altoprcn, anchoprcn, x, y;
	scanf_s("%i", &ancho);
	scanf_s("%i", &alto);
	scanf_s("%f", &x);
	scanf_s("%f", &y);
	scanf_s("%f", &anchoprcn);
	scanf_s("%f", &altoprcn);
	izqx = x * ancho;
	upy = y * alto;
	derx = izqx + anchoprcn * ancho;
	downy = upy + altoprcn * alto;
	printf("%i ", ancho);
	printf("%i", alto);
	printf("%6.2f", x);
	printf("%6.2f", y);
	printf("%6.2f", anchoprcn);
	printf("%6.2f ", altoprcn);
	printf("%i ", izqx);
	printf("%i ", upy);
	printf("%i ", derx);
	printf("%i", downy);
}
