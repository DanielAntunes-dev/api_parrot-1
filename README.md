# api_parrot

primeiro: npm install 

1 - Clonar o projeto em sua máquina;</br> 2 - Executar no terminal: npm install;</br> 3 - Criar um arquivo na raiz do projeto com o nome ".env", com o seguinte conteúdo (substitua pelas suas informações sem as aspas):</br>   DB_USER="nome do seu usuario no mysql"</br>   DB_PWD="senha do seu usuario"</br>   DB_NAME="nome que voce quer dar para o banco de dados"</br>   DB_HOST="local onde está rodando o servidor, para servidor local usar localhost"</br>   DB_PORT="porta utilizada"</br>   DB_DIALECT="qual é o banco de dados? nosso caso mysql"</br>   NODE_ENV=development</br>


para criar as migrations: npm run migration:generate

para rodar as migrations: npm run migration:run

para rodar a seeders: npm run seed




# HandsOn#4 - GamaXP#43 - Parrot

A rede social Parrot é um sistema white label (ou seja, um sistema modelo criado por
uma empresa que pode ser reutilizado por outras, apenas modificando informações
como logo e marca) do qual condomínios podem contratar para incentivar a interação
entre os moradores.
A plataforma permite que os usuários façam publicações que ficam visíveis para toda
comunidade.


## 🚀 Começando

Este projeto necessita de alguns passos para ser testado corretamente, conforme descrito abaixo:

    1. Banco de Dados Mysql instalado e configurado no ambiente a ser testado.
    2. Uma framework client para testes de API. Recomendado ( Insomnia ou Postman ), para interação com a API.
    3. Um editor de texto, para alteração do arquivo de conexão com o Banco de Dados ( Recomendado VSCODE).

### 📋 Pré-requisitos

De que coisas você precisa para instalar o software e como instalá-lo?

    1. MySql.
    2. Insomnia ou Postman.
    3. VsCode.

### 🔧 Instalação
    - Após clonar o repositório, acesse via terminal a pasta ./src/ executar o comando "npm install" para instalar todas as dependências do projeto.
    - Necessário alterar credenciais do banco de dados no arquivo .env
    - Criar banco de dados dentro do MySql com o seguinte nome: parrot e deixar o banco vazio.
    - No terminal, rodar os comandos, todos sem aspas:
    - "npm run migration:generate" e em seguida "npm run migration:run" para gerar as tabelas com as migrations;
    - "npm run seed" para popular o banco com um usuário ADMIN com login: admin@admin.com e senha admin.
    - Para iniciar o servidor da API via script, acesse o terminal e execute o seguinte comando: npm run dev.
    
    
## 📦 Documentação da API

      https://documenter.getpostman.com/view/21642567/VVBUySTW


## ✒️ Autores

*⌨️ com ❤️ por **Amanda Hammes** - *Node.JS - Documentação* - [Amanda Hammes](https://github.com/amandahammes/)
*⌨️ por **Daniel Junior** - *Node.JS - Documentação* - [Daniel Junior](https://github.com/)<br>


## 🎁 Expressões de gratidão

* Projeto realizado após muito esforço e dedicação, Esperamos que gostem! 📢
* Com o projeto concluído. Podemos Tomar uma 🍺 não é mesmo **Amanda Hammes**?
* Obrigado [Daniel Obara](https://github.com/DanielObara) Pelos ensinamentos, macetes e principalmente pela paciência em nos ensinar 🤓.
