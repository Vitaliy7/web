# web  
### Домашнее задание по теме _Динамический веб_  
> Развертывание веб приложения  
> Варианты стенда:  
nginx + php-fpm (laravel/wordpress) + python (flask/django) + js(react/angular);  
nginx + java (tomcat/jetty/netty) + go + ruby;  
можно свои комбинации.  
Реализации на выбор:  
на хостовой системе через конфиги в /etc;  
деплой через docker-compose.  
Для усложнения можно попросить проекты у коллег с курсов по разработке  
К сдаче принимается:  
vagrant стенд с проброшенными на локалхост портами  
каждый порт на свой сайт  
через нжинкс Формат сдачи ДЗ - vagrant + ansible
>

### Решение ДЗ.  
Задание сделано согласно методички, выбран стенд _nginx + php-fpm (wordpress) + python (django) + js(node.js)_ с деплоем через _docker-compose_  
Выполняется автоматически, при помощи _vagrant + ansible_  
После разворачивания виртуальной машины и старта докера для проверки выполнения  
на хосте в браузере заходим на адреса:   
https://localhost:8081

![](https://github.com/Vitaliy7/web/blob/main/screenshots/8081.png?raw=true)

https://localhost:8082 

![](https://github.com/Vitaliy7/web/blob/main/screenshots/8082.png?raw=true)

и https://localhost:8083

![](https://github.com/Vitaliy7/web/blob/main/screenshots/8083.png?raw=true)
