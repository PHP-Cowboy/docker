``docker study note``

``docker run -d -p 3306:3306 --restart=always -v /Users/mysql/conf:/etc/mysql/conf.d -v /Users/mysql/data:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=123456 --name mysql01 mysql:5.7
``