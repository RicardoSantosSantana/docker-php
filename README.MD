# docker-php
Docker PHP Mysql phpmyadmin apache
# Esse projeto cria serviços docker apache, php, phpmyadmin, mysql
### Primeiro
> renomear o arquivo .env.examplo para .env e configurar as informações conforme seu desejo
### Segundo 
> docker-compose build
### Terceiro - rodar sem saída no terminal "-d"
> docker-compose up -d

## Atualizar PHP para 8.1
> sudo apt-get update && apt-get upgrade
> sudo apt-get install software-properties-common
> sudo add-apt-repository ppa:ondrej/php
> sudo apt-get update
> sudo apt-get install php8.1
> sudo apt-get install libapache2-mod-php8.1 php8.1-fpm libapache2-mod-fcgid php8.1-curl php8.1-dev php8.1-gd php8.1-mbstring php8.1-zip php8.1-mysql php8.1-xml


