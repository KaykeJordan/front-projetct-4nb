# README - Frontend da Aplicação Livraria

## Descrição
Este projeto é o **frontend** de uma aplicação de livraria que permite:
- Registro de usuários.
- Login de usuários.
- Cadastro de livros com os seguintes campos:
  - Nome do Livro.
  - Nome do Autor.
  - Preço do Livro.

O frontend interage com o backend da aplicação, sendo necessário que o servidor backend esteja em execução para que as funcionalidades sejam acessíveis.

## Pré-requisitos
- Navegador atualizado para visualizar as páginas HTML.
- Servidor backend configurado e rodando.
  - Repositório do backend: [https://github.com/KaykeJordan/kaykejordan-4nb](link).
- Arquivo `request.http` para realizar requisições HTTP diretamente ao backend.

## Estrutura do Projeto

### Páginas principais:
- **bookstore.html**: Página para cadastro de livros.
- **login.html**: Página de login.
- **register.html**: Página para registro de novos usuários.

### Estilos e Scripts:
- **CSS**: Arquivos de estilo organizados por página para personalizar a aparência.
- **JavaScript**: Scripts responsáveis por gerenciar a interação entre o frontend e o backend.

## Passo a Passo para Utilização

1. **Inicializar o backend**:
   - Clone o repositório do backend a partir do link acima.
   - Configure o ambiente e inicialize o servidor (porta padrão: 3000).

2. **Abrir o frontend**:
   - Abra os arquivos HTML no navegador para visualizar as páginas.
   - Utilize as páginas para realizar ações como registro de usuários, login e cadastro de livros.

3. **Requisições HTTP**:
   - Utilize o arquivo `request.http` (caso disponível) para testar as requisições diretamente para o backend.
   - Certifique-se de que o servidor está rodando antes de realizar as requisições.

## Funcionalidades

### Registro de Usuários:
- Acesse `register.html`.
- Preencha os campos Nome, Email e Senha.
- Clique no botão **Registrar** para salvar o usuário.

### Login de Usuários:
- Acesse `login.html`.
- Preencha os campos de Email e Senha.
- Clique no botão **Entrar** para autenticar.

### Cadastro de Livros:
- Acesse `bookstore.html` (após login).
- Preencha os campos Nome do Livro, Autor e Preço.
- Clique no botão **Cadastrar** para salvar o livro.

## Conclusão
Este frontend foi projetado para interagir com o backend e fornecer uma interface fácil de usar para o cadastro de usuários e livros. Certifique-se de que o servidor backend esteja em execução para que todas as funcionalidades funcionem corretamente.
