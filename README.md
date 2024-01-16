## Информация по развёртыванию приложения используя docker (docker-compose)

Для gRPC сервера и gRPC клиента (вместе с HTTP сервером) созданы два раздельных docker-образа. 

```https://hub.docker.com/repository/docker/ivankozlov03/test_grpcclient/general```

```https://hub.docker.com/repository/docker/ivankozlov03/test_grpcserver/general```

Файл docker-compose.yml содержит в себе все необходимые настройки и параметры для развёртывания приложения на удалённом сервера. Пример реально запущенного приложения можно посмотреть [этой ссылке](http://31.129.44.151:8083/)
