# Projeto Java com JDBC - Departamentos e Vendedores

Este é um projeto simples em Java que utiliza JDBC (Java Database Connectivity) para interagir com um banco de dados relacional. O projeto consiste em duas entidades principais: Departamentos e Vendedores (Sellers).

## Configuração do Banco de Dados

Este projeto assume que você possui um banco de dados relacional configurado. Certifique-se de que o JDBC driver para o seu banco de dados específico esteja incluído no classpath do projeto. Além disso, atualize as configurações de conexão com o banco de dados no arquivo `config.properties`.

## Estrutura do Banco de Dados

Este projeto pressupõe uma estrutura básica do banco de dados com as seguintes tabelas:

### Tabela `departamentos`

- `id` (chave primária)
- `nome`

### Tabela `vendedores`

- `id` (chave primária)
- `nome`
- `email`
- `salario_base`
- `data_nascimento`
- `id_departamento` (chave estrangeira referenciando a tabela `departamentos`)

## Funcionalidades

Este projeto oferece as seguintes funcionalidades básicas:

- CRUD (Create, Read, Update, Delete) para departamentos e vendedores.
- Operações de busca, adição, atualização e exclusão de registros em ambas as tabelas.

## Como usar

1. Configure o banco de dados e atualize as configurações de conexão em `config.properties`.
2. Compile o projeto Java.
3. Execute a aplicação Java.

## Dependências

Este projeto depende do seguinte:

- Java 8 ou superior
- JDBC Driver para o seu banco de dados específico

## Contribuição


Contribuições são bem-vindas! Sinta-se à vontade para abrir issues para reportar bugs ou propor novas funcionalidades.

## Licença
Esse projeto foi desenvolvido durante o curso Java COMPLETO Programação Orientada a Objetos + Projetos ministrado pelo Professor Nélio Alves segue abaixo o link do curso (NÃO é uma propaganda/parceria/publicidade).
https://www.udemy.com/course/java-curso-completo/

Este projeto está licenciado sob a Licença MIT.
