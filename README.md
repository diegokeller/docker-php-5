# docker-php-5
Ambiente de desenvolvimento em PHP usando docker. 

Para subir o ambiente execute:
```
docker-compose up
```

Se você fizer alguma alteração na configuração do php.ini, pare o container e execute o comando abaixo para que ele construa o container com a nova configuração.
```
docker-compose up --build app_web app_db
```