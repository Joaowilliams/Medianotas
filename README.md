int main(int argc, char** argv) {
	char nome[30];
	char endereco[30];
	int idade;
	
	printf("Nome \n");
	scanf("%s", &nome);
	
	printf("Endereco \n");
	scanf("%s", &endereco);
	
	printf("Idade \n");
	scanf("%d", &idade);
	
	printf("\n Digite seu nome: %s", nome);
	printf("\n Digite seu endereco: %s", endereco);
	printf("\n Digite sua idade: %d", idade);
		
	
	return 0;
}
