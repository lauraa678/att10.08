# att10.08

#include <stdio.h>
#include <stdlib.h>

int main() {
	
	float fahrenheit;
		
	printf("Digite a temperatura em fahrenheit: ");
	scanf("%f", &fahrenheit);
	
	float celsius = (fahrenheit-32)/1.8;
		
	printf("\nEssa temperatura em graus celsius e: %f", celsius);
	
return 0;
}
