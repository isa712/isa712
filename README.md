**TUTORIAL DO PASSO A PASSO PARA INSTALAÇÃO E CONFIGURAÇÃO DO DOCKERFILE PARA UTILIZAR O WIKI.JS**


*>Primeiro passo:*

Instalar o docker utilizando o comando: APT INSTALL DOCKER

*>Segundo passo:*

Criar dois arquivos no GitHub, um com o nome de docker-compose.yaml e outro com nome de README.md
1. No README.md é onde está escrito todo o tutorial de como ter acesso ao wiki.js
2. No docker-compose.yaml é onde esta todo o código de funcionamento

![codigo](https://user-images.githubusercontent.com/85373388/120943453-5f25aa80-c705-11eb-937a-f74454cd26bc.PNG)

***ALGUMAS DAS INFORMAÇÕES IMPORTANTES CONTIDAS NO CÓDIGO:***

 1. DB_TYPE : Tipo de Banco de dados, no caso Postgres
 2. DB_HOST : Nome do host ou IP do banco de dados
 3. DB_PORT : Porta do banco de dados
 4. DB_USER : Nome de usuário para conectar ao banco de dados
 5. DB_PASS : Senha para conectar ao banco de dados
 6. DB_NAME : nome do banco de dados


*>Terceiro passo:*

  Entrar na pasta do wiki.js pelo o comando: CD WIKIJS
  
*>Quarto passo:* 

  Clonar os containers através do link do GitHub: GIT CLONE <LINK>
  
*>Quinto passo:*
  
  Subir os containers com o comando: DOCKER-COMPOSE UP
  
*>Sexto passo:*
  
  Para acessar basta digitar no navegador o IP que a máquina estiver utilizando com a porta ":9090"
  
  ![wiki](https://user-images.githubusercontent.com/85373388/120944211-a57d0880-c709-11eb-8710-c402e5d3dc12.PNG)

