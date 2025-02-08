# Desafio: Criando um Sistema Bancário com Python

Este desafio faz parte de uma atividade do **Bootcamp** que estou realizando na plataforma da [DIO (Digital Innovation One)](https://www.dio.me/), em parceria com a empresa **Suzano**.

## Objetivo do Projeto

Fomos contratados por um grande banco para desenvolver o seu novo sistema. Esse banco deseja modernizar suas operações e, para isso, escolheu a linguagem Python. Para a primeira versão do sistema, devemos implementar apenas 3 operações: **depósito**, **saque** e **extrato**.

## Operação de Depósito

- Deve ser possível depositar valores positivos para a conta bancária.
- A versão 1 (v1) do projeto trabalha apenas com 1 usuário, portanto, não é necessário identificar o número da agência e conta bancária.
- Todos os depósitos devem ser armazenados em uma variável e exibidos na operação de extrato.

## Operação de Saque

- O sistema deve permitir realizar **3 saques diários**, com um limite máximo de **R$ 500,00 por saque**.
- Caso o usuário não tenha saldo em conta, o sistema deve exibir uma mensagem informando que não será possível sacar o dinheiro por falta de saldo.
- Todos os saques devem ser armazenados em uma variável e exibidos na operação de extrato.

## Operação de Extrato

- Essa operação deve listar todos os depósitos e saques realizados na conta.
- No fim da listagem, deve ser exibido o saldo atual da conta.
- Os valores devem ser exibidos utilizando o formato **R$ xxx.xx**, por exemplo:
  - `1500.45` = **R$ 1500.45**

---

Este projeto é a primeira versão de um sistema bancário simples, desenvolvido em Python, com foco nas operações básicas de depósito, saque e extrato. Ele foi desenvolvido como parte do Bootcamp da DIO em parceria com a Suzano, com o objetivo de aprimorar minhas habilidades em programação Python e lógica de programação.