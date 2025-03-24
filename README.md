1. Fazer um teste de mesa do algoritmo abaixo, deixando explícito os valores de saída em console e a estrutura da pilha
Pilha p = new Pilha();
int[] vetor = {100, 200, 1, 50, 39, 44, 25, 16, 99, 45, 33, 18, 102, 92};
int tamanhoVetor = vetor.length;
Para (i = 0 ; i < tamanhoVetor ; i++) {
Se (pilhaVazia() == verdadeiro) {
p.push(vetor[i] - 10);
} Senao Se (vetor[i] mod 5 == 0) {
p.push(vetor[i] / 5);
} Senao Se (vetor[i] mod 3 == 0) {
p.push(vetor[i] * 3);
} Senao {
int v1 = p.pop();
escreva (v1 / 2);
}
}
