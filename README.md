# VitalHubApi - API com CRUD Completo 🛠️

VitalHubApi é um projeto desenvolvido para aprender os conceitos e práticas de criação de APIs. O projeto implementa um CRUD completo (Create, Read, Update, Delete) usando C# e MySQL como banco de dados, com o Visual Studio Community como IDE.

## Tecnologias Utilizadas 🛠️

- **C#**: Linguagem de programação utilizada para o desenvolvimento da API.
- **MySQL**: Banco de dados relacional utilizado para armazenar os dados.
- **Visual Studio Community**: IDE utilizada para o desenvolvimento da aplicação.
- **ASP.NET Core**: Framework utilizado para criar a API RESTful.

## Funcionalidades 🔧

- **Create**: Adicionar novos registros ao banco de dados.
- **Read**: Consultar dados existentes no banco de dados.
- **Update**: Atualizar informações de registros existentes.
- **Delete**: Excluir registros do banco de dados.

## Como Rodar o Projeto 🚀

1. **Clone o repositório**:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd <DIRETORIO_DO_PROJETO>
   
## Exemplos de Endpoints 📡

1. **Criar um novo registro**

   - **Método**: `POST`
   - **URL**: `/api/entidade`
   - **Corpo**:
     ```json
     { 
       "campo1": "valor1", 
       "campo2": "valor2" 
     }
     ```

2. **Consultar todos os registros**

   - **Método**: `GET`
   - **URL**: `/api/entidade`

3. **Atualizar um registro**

   - **Método**: `PUT`
   - **URL**: `/api/entidade/{id}`
   - **Corpo**:
     ```json
     { 
       "campo1": "novoValor1", 
       "campo2": "novoValor2" 
     }
     ```

4. **Excluir um registro**

   - **Método**: `DELETE`
   - **URL**: `/api/entidade/{id}`

## Contribuição 🌟

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Contato 📧

Para dúvidas ou sugestões, entre em contato:
- **E-mail**: thiagorafael2005@gmail.com
