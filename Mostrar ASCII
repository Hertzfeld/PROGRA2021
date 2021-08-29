#include <stdio.h>
#include <stdlib.h>

/**
Ejercicio:

Imprimir por pantalla, en 4 columnas, y bien alineado, las letras mayúsculas,
las letras minúsculas, y los números de la tabla ASCII, indicando el símbolo,
el valor decimal y el valor hexadecimal de cada uno.

Ejemplo:

A | 65 | 41
B | 66 | 42
C | 67 | 43
D | 68 | 44
E | 69 | 45
*/

void mostrarASCII(const char,const char); //datos constantes,
                                          //función retorna void

int main()
{
    mostrarASCII('A','Z');
    mostrarASCII('a','z');
    mostrarASCII('0','9');
    return 0;
}

/**
    %x          = imprime el valor en hexa
    %#x         = muestra por delante "0x"
    %0[NUMERO]x = 0[NUMERO] indica la cant de dígitos a mostrar,
                  completando con 0

*/
void mostrarASCII(const char inicio, const char fin)
{
    //recibe condición de inicio y fin para ciclo for
    char caracter; //código ASCII a mostrar
    printf("\n ASCII\t| DECIMAL\t| HEXA\n");
    for(caracter=inicio; caracter<=fin; caracter++)
    {
        printf(" %c\t| %d\t\t| %X\n", caracter, caracter, caracter);
    }
}
