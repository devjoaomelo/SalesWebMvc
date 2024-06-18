# SalesWebMvc

SalesWebMvc é um projeto de aprendizado em ASP.NET Core, focado no desenvolvimento de uma aplicação web para gerenciamento de vendas.

## Funcionalidades

- Cadastro de vendedores
- Cadastro de departamentos
- Registro de vendas
- Relatórios de vendas

## Requisitos

Para executar o projeto, é necessário ter os seguintes pré-requisitos instalados:

- .NET Core SDK 3.1 ou superior
- Visual Studio 2019 ou superior
- SQL Server (ou outra base de dados compatível)

## Como executar

1. Clone o repositório:
    ```sh
    git clone https://github.com/devjoaomelo/SalesWebMvc.git
    ```

2. Navegue até o diretório do projeto:
    ```sh
    cd SalesWebMvc
    ```

3. Restaure as dependências do projeto:
    ```sh
    dotnet restore
    ```

4. Atualize o banco de dados:
    ```sh
    dotnet ef database update
    ```

5. Execute a aplicação:
    ```sh
    dotnet run
    ```

A aplicação estará disponível em `https://localhost:5001`.

## Tecnologias Utilizadas

- ASP.NET Core
- Entity Framework Core
- SQL Server
- Bootstrap
