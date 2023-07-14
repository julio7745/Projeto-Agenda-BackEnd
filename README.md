# Projeto de Agenda Online no Backend

## Descrição do Projeto

O objetivo principal deste projeto é desenvolver uma agenda online que ofereça aos usuários a capacidade de criar uma conta e acessar a agenda de qualquer lugar. Com esta aplicação, os usuários poderão cadastrar contatos, incluindo números de telefone e endereços de e-mail, além de gerenciar esses contatos de forma eficiente.

## Funcionalidades Principais

- Criação de conta: Os usuários podem criar uma conta pessoal para acessar a agenda online.
- Cadastro de contatos: Os usuários podem adicionar contatos à sua agenda, fornecendo informações como nome, número de telefone e endereço de e-mail.
- Edição de Contatos: Os usuários têm a possibilidade de editar os detalhes de um contato existente em sua agenda.
- Exclusão de contatos: Os usuários têm a opção de remover contatos da agenda.
- Armazenamento seguro: Todos os dados da agenda são armazenados de forma segura no MongoDB, evitando a sobrecarga de memória no dispositivo do usuário.

## Tecnologias Utilizadas

- Node.js: Utilizamos o ambiente de execução Node.js para desenvolver o backend da aplicação.
- MongoDB: Utilizamos o MongoDB como banco de dados para armazenar e gerenciar os dados da agenda.
- EJS: Utilizamos o EJS como mecanismo de renderização para exibir as páginas web dinamicamente.
- Express: Utilizamos o framework Express para facilitar o desenvolvimento e a criação de rotas na aplicação.
- Outras ferramentas.

## Como Executar o Projeto Localmente

1. Certifique-se de ter o Node.js instalado em seu sistema.
2. Clone este repositório em sua máquina local.
3. Navegue até o diretório raiz do projeto no terminal.
4. Execute o comando `npm install` para instalar as dependências.
5. Crie um projeto no banco de dados MongoDB.
6. Configure as variáveis de ambiente necessárias:
   1. Crie um arquivo ".env", na pasta "Projeto-Agenda" e edite-o com um editr de texto.
   2. Coloque o seguinte texto: <br>
      ```
      LOGIN = 'string de conexão mongoDB'
      SECRET = 'Qualquer Coisa'
      ```
   3. Substitua 'string de conexão mongoDB' e 'Qualquer Coisa' por seus respectivos dados.
7. Execute o comando `npm start` para iniciar o servidor backend.
8. Acesse a aplicação em seu navegador no endereço `http://localhost:3001`.
