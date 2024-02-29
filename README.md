
# Simulador de Herança

Este programa simula a herança genética do tipo sanguíneo em uma árvore genealógica ao longo de três gerações. O tipo sanguíneo de cada indivíduo é determinado pelos alelos herdados de seus pais.

A saída exibirá uma árvore genealógica com a geração e o tipo sanguíneo de cada membro da família. Os membros mais "velhos" da árvore terão seu tipo sanguíneo definido aleatóriamente, já as próximas gerações terão seus tipos baseados em seus pais.

## Estrutura do código

- `struct person`: Define uma pessoa com dois pais e dois alelos.
- `create_family(int generations)`: Cria uma nova família com um número especificado de gerações. A função aloca memória para cada pessoa e atribui seus alelos do tipo sanguíneo com base nos alelos dos pais.
- `free_family(person \*)`: Libera a memória alocada para uma pessoa e seus ancestrais.
- `print_family(person \*, int generation)`: Imprime uma árvore genealógica com a geração e o tipo sanguíneo de cada membro da família.
- `random_allele()`: Escolhe aleatoriamente um alelo do tipo sanguíneo (A, B ou O).

## Aprendizados

O exercício tem como objetivo focar no aprendizado de listas encadeadas e funções recursivas.
