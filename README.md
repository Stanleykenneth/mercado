# Projeto de Mercado em Python

Este projeto é uma aplicação de mercado construída em Python. A aplicação permite cadastrar produtos, listar produtos, adicionar produtos ao carrinho, visualizar o carrinho e fechar pedidos. Através deste projeto, aplicamos diversos conceitos e técnicas de programação em Python.

## Funcionalidades

- **Cadastro de Produtos:** Permite ao usuário cadastrar novos produtos com nome e preço.
- **Listagem de Produtos:** Exibe todos os produtos cadastrados.
- **Compra de Produtos:** Permite adicionar produtos ao carrinho.
- **Visualização do Carrinho:** Exibe os produtos atualmente no carrinho e suas quantidades.
- **Fechar Pedido:** Calcula o total do pedido e limpa o carrinho.

## Tecnologias Utilizadas

- **Python:** Linguagem de programação principal utilizada no projeto.
- **Módulos Padrões:** Utilização de módulos como `typing`, `time` para tipagem e controle de tempo.
- **Orientação a Objetos:** Estruturação do código utilizando classes e objetos para representar produtos e suas operações.

## Estrutura do Projeto

```plaintext
mercado/
├── mercado.py         # Arquivo principal da aplicação
├── models/
│   └── produto.py     # Definição da classe Produto
└── utils/
    └── helper.py      # Funções auxiliares, como formatação de moeda
