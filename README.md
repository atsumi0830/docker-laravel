# docker-laravel

## 環境
php: 7.3 <br>
web server: nginx-alpine<br>
MySQL: 8.0
 
## 環境構築
1. git clone 
1. docker-compose.yml配下にてdocker-compose up -d --build
1. docker-compose exec app ash
1. composer create-project --prefer-dist "laravel/laravel=6.*" .

## URL
http://127.0.0.1:10080/
