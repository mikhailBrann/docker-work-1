# Домашнее задание к лекции «Docker»

## Задание 1

По аналогии с практикой из лекции создайте свой docker image с http сервером nginx. Замените страницу приветсвия Nginx на своё

открываем терминал и по порядку вбиваем слудующее:

1) docker build -t my-nginx ./

2) docker run --name my-nginx-server -d -p 83:80 my-nginx

смотрим результат по адресу:
[nginx-hello](http://localhost:83)