# Calculadora de Partidas Rankeadas - Bootcamp GFT Start #6

Este repositório apresenta a resolução do desafio "Calculadora de Partidas Rankeadas" do Bootcamp **GFT Start #6 - Lógica de Programação** da [Digital Innovation One (DIO)](https://www.dio.me/).

## Descrição do Desafio

O desafio consiste em criar uma função que recebe como parâmetros a quantidade de vitórias e derrotas de um jogador e, com base no número de vitórias, determina o nível do jogador conforme a tabela abaixo:

- **Ferro**: Vitórias menores que 10
- **Bronze**: Vitórias entre 11 e 20
- **Prata**: Vitórias entre 21 e 50
- **Ouro**: Vitórias entre 51 e 80
- **Diamante**: Vitórias entre 81 e 90
- **Lendário**: Vitórias entre 91 e 100
- **Imortal**: Vitórias acima de 101

Além disso, a função deve calcular o saldo de vitórias, subtraindo as derrotas do número de vitórias, e exibir uma mensagem com o saldo e o nível do jogador.

## Solução Implementada

A solução para o desafio é composta por três funções:

1. `calcularSaldo(vitorias, derrotas)`: Calcula o saldo de vitórias subtraindo as derrotas.
2. `determinarNivel(vitorias)`: Determina o nível do jogador com base no número de vitórias.
3. `exibirResultado(vitorias, derrotas)`: Retorna uma mensagem que exibe o saldo de vitórias e o nível correspondente.


## Exemplo de Saída:

```bash
O Herói tem um saldo de 30 vitórias e está no nível Prata
```

## Como Executar

1. Clone este repositório:

```bash
git clone https://github.com/karinaburguez/dio-gtf-start-6-calculadora-de-partidas-rankeadas.git
```

2. Abra o arquivo `index.js` e execute o código em um ambiente Node.js ou diretamente no console do navegador para ver o resultado.

## Observação

Ao implementar a função, percebi que o enunciado do desafio apresenta uma questão no intervalo de vitórias. Ele menciona que vitórias menores que 10 correspondem ao nível **Ferro**, e vitórias entre 11 e 20 são **Bronze**, deixando o caso de exatamente 10 vitórias indefinido. Sugiro que a regra para o nível **Ferro** seja corrigida para "Vitórias menores ou iguais a 10".

---

Espero que este repositório ajude a esclarecer a lógica utilizada na resolução do desafio.

--- 

Karina Burguez