# lesson27

***Домашнее задание***

В материалах приложены ссылки на вагрант для репликации и дамп базы bet.dmp

Базу развернуть на мастере и настроить так, чтобы реплицировались таблицы:

| bookmaker | </br>
| competition | </br>
| market | </br>
| odds | </br>
| outcome </br>
Настроить GTID репликацию </br>
варианты которые принимаются к сдаче </br>
рабочий вагрантафайл </br>
скрины или логи SHOW TABLES </br>


Согласно методичке были развернуты две ВМ master и slave, так же установлена база данных

Далее в скринах показана проделанная работа

Настройка на master

![image](https://github.com/movik242/lesson27/assets/143793993/11ea26b6-44bb-4e5b-a3bc-c6b7314b723a)

![image](https://github.com/movik242/lesson27/assets/143793993/fa6852b1-e7bf-4cac-9319-5027e9d227c3)

Выгрузил БД

![image](https://github.com/movik242/lesson27/assets/143793993/ae738889-709b-4e61-9351-d312911045df)


Настройка на slave

![image](https://github.com/movik242/lesson27/assets/143793993/e020f5cf-9aee-42f8-b808-428985f8d25d)

![image](https://github.com/movik242/lesson27/assets/143793993/2bd990ed-a0b4-4e3e-be04-dfc996f786ac)

Start slave

![image](https://github.com/movik242/lesson27/assets/143793993/830b7fd7-1664-4c04-bae5-9ac17ac79f53)

На master

![image](https://github.com/movik242/lesson27/assets/143793993/18b2a33f-1d49-42e8-979f-9ef1e7d0ead1)

На slave

![image](https://github.com/movik242/lesson27/assets/143793993/01678e5c-9ee7-41ce-aea8-5da5c09cf703)


![image](https://github.com/movik242/lesson27/assets/143793993/38adc98b-0db3-468b-970c-87809372b7cf)

