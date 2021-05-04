# <p align="center">Fullcyle :rocket:  </p>

<h1 align="center">
    <img alt="FullCycle" src="./public/assets/logo.png" width="231px" /><br>
    <b>FullCycle PFA</b> 💈
</h1>


### Challenge :triangular_flag_on_post:

- Crie o docker-compose.yaml com 3 serviços, um para cada tecnologia. Você deverá configurar os seguintes pontos:
- O serviço do MySQL não poderá ter um Dockerfile personalizado, é necessário usar diretamente a imagem oficial do MySQL e deverá existir um volume para persistir o banco de dados no projeto, o nome da pasta será dbdata. Deverá usar o entrypoint-initdb.d para já criar um banco e popular dados no banco de dados padrão.
-  O serviço da sua linguagem favorita deverá continuando a listar dados através da WEB vindo do MySQL. Antes do container iniciar ele deverá verificar se o MySQL já está pronto para conexão, sugerimos usar o Dockerize para fazer esta verificação.
- O serviço do Nginx continuará sendo um proxy reverso para a sua aplicação da linguagem favorita e deverá expor a porta 8000 para acessar a aplicação no browser. Este serviço deverá iniciar somente quando o da sua aplicação da linguagem favorita for iniciado e deverá ser reiniciado automaticamente caso a aplicação da linguagem favorita não esteja rodando ainda.
- Os serviços do MySQL e da linguagem favorita devem ter uma rede compartilhada que o Nginx não enxergue e linguagem favorita e Nginx devem ter uma rede compartilhada que o MySQL não enxergue.


## :bulb: Recursos

-   [Docker](https://www.docker.com/)
-   [Node.js](https://nodejs.org/en/)
-   [Nginx](https://www.nginx.com/)
-   [MySQL](https://www.mysql.com/)
-   [Node MySQL2](https://www.npmjs.com/package/mysql2)
-   [Dockerrize](https://github.com/jwilder/dockerize)





### Crie o arquivo Docker Compose



## :pushpin: Rodando o Docker Composer


```sh
docker-compose up
```



Access http://localhost:8000/



