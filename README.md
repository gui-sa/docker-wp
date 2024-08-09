# docker-wp

Repositorio para guardar configurações base para **DESENVOLVIMENTO LOCAL** de wordpress no ambiente DOCKER


## DNS FLUSH
Para limpar o cache DNS:
~~~
ipconfig /flushdns
~~~


### Clear Docker volumes
~~~
docker volume rm $(docker volume ls -qf dangling=true)
~~~

## Referencias
 - https://www.digitalocean.com/community/tutorials/how-to-install-wordpress-with-docker-compose