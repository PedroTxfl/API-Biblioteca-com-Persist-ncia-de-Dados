# API Biblioteca com Persistência de Dados

Este projeto consiste no desenvolvimento de APIs RESTful com persistência de dados para uma aplicação de biblioteca, utilizando PostgreSQL.

## Funcionalidades

- **CRUD de Livros**: Gerenciamento completo de livros na biblioteca.
- **CRUD de Autores**: Gerenciamento de autores.
- **Relacionamento entre Entidades**: Manipulação de livros e autores, incluindo restrições de chave estrangeira.
- **Persistência de Dados**: Armazenamento e gerenciamento de dados usando PostgreSQL.
- **Autenticação**: Implementação de autenticação JWT.
- **Tratamento de Erros**: Gestão de erros e exceções.

## Tecnologias Utilizadas

- **Linguagem**: JavaScript
- **Framework**: Express
- **Banco de Dados**: PostgreSQL
- **Autenticação**: JWT
- **Ferramentas de Teste**: Postman


## Instalação e Uso

1. Clone o repositório:
   ```sh
   git clone https://github.com/pedrotxsenac/API_biblioteca_Com_BD.git
   ```
2. Navegue até o diretório do projeto:
   ```sh
   cd API_biblioteca_Com_BD
   ```
3. Instale as dependências.
4. Configure o banco de dados no arquivo `config.js`.
5. Crie as tabelas no banco de dados utilizando o arquivo `schema.sql`:
   ```sh
   psql -U seu_usuario -d seu_banco_de_dados -f schema.sql
   ```
6. Execute a aplicação:
   ```sh
   npm start
   ```


