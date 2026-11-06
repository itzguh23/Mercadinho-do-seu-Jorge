# 🛒 Mercadinho do Seu Jorge

**Sistema de gerenciamento de produtos e estoque desenvolvido em Python.**

## 📌 Sobre o projeto

O Mercadinho do Seu Jorge é um programa desenvolvido em Python com o objetivo de facilitar o gerenciamento de produtos de um pequeno estabelecimento comercial.

O sistema permite cadastrar produtos, consultar o estoque, editar informações e remover produtos cadastrados.

Os dados são armazenados em um arquivo JSON, permitindo que as informações continuem salvas mesmo depois que o programa seja encerrado.

## ⚙️ Funcionalidades

O sistema possui as seguintes funcionalidades:

- **Cadastrar produtos:** permite adicionar produtos informando nome, tamanho, preço e quantidade disponível.
- **Listar produtos:** exibe todos os produtos cadastrados, seus preços e quantidades em estoque.
- **Editar produtos:** permite atualizar o preço e a quantidade de um produto.
- **Remover produtos:** permite excluir produtos cadastrados.
- **Verificação de duplicidade:** impede o cadastro de produtos com o mesmo nome e tamanho.
- **Controle de estoque:** identifica produtos que estão sem estoque.
- **Salvamento automático:** registra as alterações no arquivo JSON.
- **Carregamento automático:** recupera os produtos salvos ao iniciar o programa.

## 🧰 Tecnologias utilizadas

- **Python:** linguagem de programação utilizada no desenvolvimento.
- **JSON:** formato utilizado para armazenar os dados dos produtos.
- **Time:** biblioteca utilizada para criar o efeito de digitação no terminal.
- **Builtins:** utilizada para acessar as funções originais de entrada e saída do Python.

## 📂 Estrutura do projeto

```text
Mercadinho-do-Seu-Jorge/
│
├── main.py
├── estoque.json
└── README.md
```

- `main.py`: arquivo principal, contendo o código do sistema.
- `estoque.json`: arquivo responsável por armazenar os produtos cadastrados.
- `README.md`: documentação do projeto.

**Observação:** o arquivo `estoque.json` é criado automaticamente quando um produto é cadastrado pela primeira vez.

## ▶️ Como executar

1. Certifique-se de ter o Python instalado no computador.
2. Abra a pasta do projeto.
3. Execute o arquivo `main.py`.
4. Utilize o menu apresentado no terminal para navegar pelas funcionalidades.

## 📋 Menu principal

| Opção | Funcionalidade |
|---|---|
| 1 | Cadastrar produto |
| 2 | Listar produtos |
| 3 | Editar produto |
| 4 | Remover produto |
| 0 | Sair do programa |

## 💾 Armazenamento de dados

Os produtos são armazenados em um arquivo chamado `estoque.json`.

Cada produto possui quatro informações:

- Nome;
- Tamanho;
- Preço;
- Quantidade disponível.

As alterações são salvas automaticamente, evitando a perda dos cadastros ao fechar o programa.

## 🎓 Objetivo educacional

Este projeto foi desenvolvido como parte das atividades de Lógica de Programação, com o objetivo de praticar conceitos fundamentais da programação, como:

- Listas;
- Dicionários;
- Estruturas condicionais;
- Laços de repetição;
- Funções;
- Manipulação de arquivos;
- Tratamento de exceções;
- Manipulação de dados JSON.

## 🚀 Desenvolvido por

**Gustavo Marggrander**

*Projeto educacional — Mercadinho do Seu Jorge.*
