# Desafio de Controle de Fluxo

## Descrição

Este projeto é um exercício para aplicar conceitos de controle de fluxo em Java. O sistema deve receber dois parâmetros via terminal que representarão dois números inteiros e, com base nesses números, realizar uma série de interações (loops) para imprimir números incrementados. 

## Requisitos

1. O sistema deve receber dois parâmetros via terminal que representarão dois números inteiros.
2. O sistema deve calcular a quantidade de interações (usando um loop `for`) e realizar a impressão no console (`System.out.print`) dos números incrementados.
    - Exemplo: Se os números fornecidos forem 12 e 30, o sistema deve realizar 18 interações e imprimir: 
      ```
      Imprimindo o número 1
      Imprimindo o número 2
      ...
      Imprimindo o número 18
      ```
3. Se o primeiro parâmetro for maior que o segundo parâmetro, o sistema deve lançar uma exceção customizada chamada `ParametrosInvalidosException` com a mensagem: "O segundo parâmetro deve ser maior que o primeiro".

## Estrutura do Projeto

O projeto deve conter as seguintes classes:

- `Contador.java`: Classe principal que contém a lógica para receber os parâmetros, realizar as interações e imprimir os números.
- `ParametrosInvalidosException.java`: Classe que representa a exceção customizada para o caso de o primeiro parâmetro ser maior que o segundo.

## Instruções para Execução

1. Clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/GabSalata/DesafioControleFluxo

