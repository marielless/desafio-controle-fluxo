# Desafio Controle de Fluxo

Este projeto consiste em um programa Java que recebe dois números inteiros como entrada e realiza uma contagem baseada na diferença entre eles. Caso o primeiro número seja maior que o segundo, o programa lança uma exceção customizada.

## Tecnologias Utilizadas

- Java
- `Scanner` para entrada de dados
- Estrutura de controle de fluxo
- Exceções personalizadas

## Estrutura do Projeto

O projeto contém as seguintes classes:

1. Classe `Contador.java` para realizar toda a codificação do nosso programa.
2. Classe `ParametrosInvalidosException` que representará a exceção de negócio no sistema.

## Funcionamento

1. O usuário insere dois números inteiros via terminal.
2. O programa verifica se o primeiro número é maior que o segundo:
- I. Se for, uma exceção ParametrosInvalidosException é lançada com a mensagem: "O segundo parâmetro deve ser maior que o primeiro".
- II. Caso contrário, o programa realiza uma contagem com base na diferença dos números e imprime no console.
