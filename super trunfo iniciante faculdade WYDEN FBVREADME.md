# Nível Iniciante.
Explicação do código:
Declaração de variáveis:

Para cada carta, declarei variáveis para armazenar todos os campos solicitados. Usei char para o estado, arrays de char para strings, 
int para números inteiros e float para números decimais.

Entrada de dados:
Usei scanf para ler cada valor digitado pelo usuário, para strings com espaços (como o nome da cidade), usei %[^\n] para ler até encontrar uma quebra de linha,
O espaço antes do %c em scanf(" %c", ...) evita problemas com caracteres de nova linha pendentes.

Saída de dados:
Foram exibidos os dados de cada carta em formato organizado, com printf, para valores float, usei %.2f para mostrar 2 casas decimais

# Nível intermediario

O Que o Código Faz? Define os dados das cartas: Pernambuco: População, área, PIB, pontos turísticos e densidade, João Pessoa: Os mesmos atributos, mas com valores diferentes.

Menu interativo: Você escolhe qual atributo comparar (1 a 5), Se digitar 0, o jogo encerra.

Comparação: O programa verifica qual carta tem o maior valor no atributo escolhido, exceto para Densidade Demográfica, onde o menor valor vence.

Resultado: Mostra qual carta venceu ou se houve empate.

Como Executar o Código? Compilação (no Linux/Windows com GCC): Salve o código em um arquivo (ex.: supertrunfo.c). Abra o terminal e digite: sh gcc supertrunfo.c -o supertrunfo

Execute: sh ./supertrunfo No Windows (usando Dev-C++ ou Code::Blocks): Copie o código, cole em um novo projeto e execute. Online (em compiladores como OnlineGDB): Cole o código e clique em "Run".

# Super trunfo avançado:

Como Funciona o Programa: Dados das Cartas: Armazena as informações de Pernambuco e João Pessoa (população, área, PIB, etc.).

Menu Interativo: Primeiro escolhe um atributo (1-5), depois escolhe um segundo atributo diferente, o menu é dinâmico - o segundo menu não mostra o atributo já escolhido.

Comparação: Para cada atributo compara os valores, densidade Demográfica é especial: menor valor vence, os outros atributos: maior valor vence.

Resultados: Mostra a comparação de cada atributo separadamente, soma os valores dos dois atributos para cada carta, a carta com maior soma vence, se a soma for igual é empate.

Tratamento de Erros: Não permite escolher o mesmo atributo duas vezes, verifica se as opções são válidas.

Como Executar: Copie o código para um arquivo super_trunfo_avancado.c Compile com: gcc super_trunfo_avancado.c -o super_trunfo Execute com: ./super_trunfo
