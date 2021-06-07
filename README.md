**TUTORIAL DO PASSO A PASSO PARA INSTALAÇÃO E CONFIGURAÇÃO DO DOCKERFILE PARA UTILIZAR O WIKI.JS**


*>Primeiro passo:*

 Clonar o repositório através do link do GitHub: GIT CLONE

*>Segundo passo:*

Entrar na pasta do wiki.js pelo comando: CD WIKIJS

*>Terceiro passo:*

  Subir os containers com o comando: DOCKER-COMPOSE UP
  
*>Quarto passo:* 

 Para acessar basta digitar no navegador o IP que a máquina estiver utilizando com a porta ":9090"
 
![image](https://user-images.githubusercontent.com/85373388/120946016-6e125a00-c711-11eb-9f6c-5d35db57ccce.png)


  
  
  >docker-compose.yaml
  

![codigo](https://user-images.githubusercontent.com/85373388/120943453-5f25aa80-c705-11eb-937a-f74454cd26bc.PNG)

***ALGUMAS DAS INFORMAÇÕES IMPORTANTES CONTIDAS NO CÓDIGO:***

 1. DB_TYPE : Tipo de Banco de dados, no caso Postgres.
 2. DB_HOST : Nome do host ou IP do banco de dados.
 3. DB_PORT : Porta do banco de dados.
 4. DB_USER : Nome de usuário para conectar ao banco de dados.
 5. DB_PASS : Senha para conectar ao banco de dados.
 6. DB_NAME : nome do banco de dados.



  
 

