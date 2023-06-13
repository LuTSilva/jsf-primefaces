# jsf-primefaces
Meus primeiros passos com JSF Primefaces!

Pra criar o container:
docker run --name cursojsfprimefaces -e MYSQL_DATABASE=cursojsfprimefaces -e MYSQL_ROOT_PASSWORD=senha -p 3306:3306 -d mysql:latest

Pra rodar comandos no MySQL container:
docker exec -it (hash_do_container) bash

Pra fazer login via Bash (CMD ou Powershell):
mysql --user=root --password=senha --database=cursojsfprimefaces

Pra ver o banco e as tabelas, usar o HeidiSQL Portable (usando dll mariadb):
MySQL - cursojsfprimefaces - root - senha


Estou aprendendo seguindo os passos presentes em: https://github.com/algaworks/curso-jsf-primefaces-essencial/tree/master / https://www.youtube.com/watch?v=ezwgBvsd6Ps
Porém estou usando Docker para eliminar a necessidade de instalar programa de banco de dados.
