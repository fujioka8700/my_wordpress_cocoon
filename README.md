# My_WordPress

## 前書き
docker-composeを使用してシンプルな WordPress 開発環境を構築します。  
使用用途は、主にレンタルサーバ用の開発です。
<br>
<br>
## 使用方法
```
$ git clone git@github.com:fujioka8700/my_wordpress.git
$ cd my_wordpress
$ docker-compose up -d
```
WordPress  
http://localhost/

phpMyAdmin  
http://localhost:1080/
<br>
<br>

## コンテナの詳細
* wordpressコンテナ
    * WordPress
    * php7.4
* mysqlコンテナ
    * mysql5.6
* phpMyAdminコンテナ
    * phpMyAdmin