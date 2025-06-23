# 🛒 Order Management Console App

Este é um programa de console desenvolvido em **C#** que simula um sistema básico de gestão de pedidos. O usuário pode cadastrar um cliente, criar um pedido, adicionar múltiplos itens e, ao final, visualizar um resumo completo da compra.

## 🚀 Funcionalidades

- Cadastro de dados do cliente:
  - Nome
  - E-mail
  - Data de nascimento
- Criação de um pedido com:
  - Data atual
  - Status do pedido (Ex.: Pending, Processing, Shipped, Delivered)
- Adição de múltiplos itens no pedido:
  - Nome do produto
  - Preço do produto
  - Quantidade
- Geração de um resumo detalhado do pedido, incluindo:
  - Dados do cliente
  - Data e status do pedido
  - Lista de itens, preços individuais, quantidades e subtotal
  - Valor total do pedido

## 🛠️ Tecnologias Utilizadas

- Linguagem: **C#**
- .NET Console Application
- Manipulação de Enums para status do pedido
- Programação Orientada a Objetos (POO)

## 📦 Estrutura do Projeto

O projeto segue o paradigma de Programação Orientada a Objetos, contendo as seguintes classes:

- `Client`: Representa o cliente (nome, e-mail e data de nascimento)
- `Product`: Representa um produto (nome e preço)
- `OrderItem`: Representa um item de pedido (quantidade, preço e produto)
- `Order`: Representa o pedido (data, status, cliente e lista de itens)
- `OrderStatus`: Enumeração que define os possíveis status do pedido

  ## 📚 Aprendizados
Este projeto aborda conceitos fundamentais como:

- Criação e manipulação de objetos

- Utilização de Enumerações (enum)

- Encapsulamento de dados

- Composição entre classes


## 🏗️ Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/ElieteCampos/Exercicio-CSharp.git

## Exemplo de uso

Enter client data:
Name: Maria Silva
Email: maria@gmail.com
Birth Date DD/MM/YYYY: 15/03/1985

Enter order data:
Status: Processing

How many items to this order? 2

Enter #1 item data:
Product name: Notebook
Product price: 3500.00
Quantity: 1

Enter #2 item data:
Product name: Mouse
Product price: 150.00
Quantity: 2

ORDER SUMMARY:
Order moment: 23/06/2025 18:45:12
Order status: Processing
Client: Maria Silva (15/03/1985) - maria@gmail.com
Order items:
Notebook, $3500.00, Quantity: 1, Subtotal: $3500.00
Mouse, $150.00, Quantity: 2, Subtotal: $300.00
Total price: $3800.00




