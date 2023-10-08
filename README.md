#include <stdio.h>

void linhas_com_exclamacoes(int n) {
    for (int i = 1; i <= n; i++) {
        for (int j = 1; j <= i; j++) {
            printf("!");
        }
        printf("\n");
    }
}

int main() {
    int n;

    printf("Digite um valor inteiro: ");
    scanf("%d", &n);

    linhas_com_exclamacoes(n);

    return 0;
}
