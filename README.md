# Modelando um sistema de estacionamento usando C#

Desafio de Código DIO -> Akad - Fullstack Developer

Este projeto é um sistema de estacionamnto simples, implementado em C#. O sistema permite o registro e a remoção de carros, alem de clacular o valor a ser pago pelo motorista com base no tempo em que o carro ficou no estacionamnto.

## Funcionalidades

- **Criação do carros**: Permite cadastrar um carro novo, apenas com a placa
- **Listagem dos carros**: Permite ver todos os carros que estão no estacionamento
- **Remoção de carros**: representa que um veiculo foi retirado do estacionamento. Calcula o valor que o cliente precisa pagar pelo tempo em que usou o estacionmento

## Estrutura do Projeto

O projeto é modularizado em três partes principais, cada uma responsável por um aspecto do sistema:

1. **Estacionamento.cs**: Define a classe `Estacionamento`, que armazena informações dos carros estacioandos.
2. **Program.cs**: Contem o main da aplicação e também implemnta o menu de seleção
