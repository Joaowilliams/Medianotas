int main(int argc, char** argv) {
	float nota1;
	float nota2;
	float media;
	
	printf("Nota1 \n");
	scanf("%f", &nota1);
	
	printf("Nota2 \n");
	scanf("%f", &nota2);
	
	media = (nota1 + nota2) /2;
	printf("\n Media = %.1f", media);
		
	
	return 0;
}
