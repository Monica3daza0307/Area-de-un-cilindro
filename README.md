#include <stdio.h>
#include <math.h>

int main() {
    
   float radio, altura, areaB, areaL, areaT;
    
    printf("Para hallar el área de un cilindro, por favor ingresa la altura");
    scanf("%f", &altura);
    printf("Para hallar el área de un cilindro, por favor ingresa el radio");
    scanf("%f", &radio);
    
    
    areaL = (2 * 3.1416 * radio * altura);
    areaB = (3.1416 * 2 * radio);
    areaT = (2 * areaL + areaB);
    
    
    
    printf("El área total es: %.2f", areaT);
    
    return 0;
}
