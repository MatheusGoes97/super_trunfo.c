Explicação do código:
Declaração de variáveis:

Para cada carta, declarei variáveis para armazenar todos os campos solicitados. Usei char para o estado, arrays de char para strings, 
int para números inteiros e float para números decimais.

Entrada de dados:
Usei scanf para ler cada valor digitado pelo usuário, para strings com espaços (como o nome da cidade), usei %[^\n] para ler até encontrar uma quebra de linha,
O espaço antes do %c em scanf(" %c", ...) evita problemas com caracteres de nova linha pendentes.

Saída de dados:
Foram exibidos os dados de cada carta em formato organizado, com printf, para valores float, usei %.2f para mostrar 2 casas decimais
