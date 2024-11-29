# Loja Eletrônicos - Sistema de Gestão de Produtos e Compras

Este projeto é um sistema básico para a gestão de produtos, fornecedores e compras de uma loja de eletrônicos. Ele utiliza SQL para criação e manipulação de tabelas e inclui consultas para visualizar dados e gerar relatórios.

## Estrutura do Banco de Dados

O banco de dados contém as seguintes tabelas:

- **Produtos**: Armazena informações sobre os produtos, como nome, preço e estoque.
- **Fornecedores**: Contém os dados dos fornecedores, como nome e contato.
- **Compras**: Registra as compras realizadas junto aos fornecedores.
- **ItensCompra**: Relaciona as compras aos produtos adquiridos, incluindo a quantidade comprada.

## Scripts Incluídos

- **Criação do Banco de Dados e Tabelas**: Scripts para criação das tabelas e configuração inicial do banco de dados.
- **Inserção de Dados**: Exemplos de dados para popular as tabelas.
- **Consultas**:
  - Listar todos os produtos com seus respectivos fornecedores.
  - Mostrar o total de itens comprados por fornecedor.

## Como Usar

1. **Configuração**:
   - Certifique-se de ter um servidor MySQL ou MariaDB configurado.
   - Execute o script SQL no seu cliente de banco de dados para criar e popular as tabelas.

2. **Execução**:
   - Use as consultas fornecidas para visualizar os dados e gerar relatórios úteis para a gestão da loja.

## Pré-requisitos

- MySQL ou MariaDB
- Um cliente de banco de dados como MySQL Workbench, DBeaver ou phpMyAdmin

## Estrutura do Repositório

- `scripts/`: Contém os arquivos SQL para criação e manipulação do banco de dados.
- `.gitignore`: Lista de arquivos e diretórios a serem ignorados no controle de versão.
- `LICENSE`: Licença do projeto (MIT License).

## Licença

Este projeto está licenciado sob a [MIT License](./LICENSE).
