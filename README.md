# HandsOn#4 - GamaXP#43 - Parrot

A rede social Parrot é um sistema white label (ou seja, um sistema modelo criado poruma empresa que pode ser 
reutilizado por outras, apenas modificando informações como logo e marca) do qual condomínios podem contratar 
para incentivar a interação entre os moradores.
A plataforma permite que os usuários façam publicações que ficam visíveis para toda comunidade.


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

    - Criar um arquivo na raiz do projeto com o nome ".env", com o seguinte conteúdo (substitua pelas suas informações sem as aspas):</br>

        DB_HOST="local onde está rodando o servidor, para servidor local usar localhost"
        DB_PORT="3443"
        DB_USER="nome do seu usuario no mysql"
        DB_PASS="senha do seu usuario no mysql"
        DB_NAME="parrot"
  
        JWT_PASS="criar senha com caracteres validos"

    
    - Criar banco de dados dentro do MySql com o seguinte nome: parrot e deixar o banco vazio.
    - No terminal, rodar os comandos, todos sem aspas:
    - "npm run migration:generate" e em seguida "npm run migration:run" para gerar as tabelas com as migrations;
    - "npm run seed" para popular o banco com um usuário ADMIN com login: admin@admin.com e senha admin.
    - Para iniciar o servidor da API via script, acesse o terminal e execute o seguinte comando: npm run dev.
    
    
## 📦 Documentação da API
        
 **API PARROT NO POSTMAN ** - [API Parrot no Postman](https://documenter.getpostman.com/view/21642567/VVBUySTW)
        
## ✒️ Autores deste projeto de BackEnd<br>

*⌨️ **Amanda Hammes** - [Amanda Hammes](https://github.com/amandahammes/)<br>
*⌨️ **Daniel Junior** - [Daniel Junior](https://github.com/DanielAntunes-dev/)<br>



