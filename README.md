# «Объектно-ориентированное программирование и проектирование»
## Домашнее задание по курсу "Java для тестировщиков"
## Тема: «3.1. «Объектно-ориентированное программирование и проектирование», задание «Радиоман»

### Задача
Статистика - очень важный компонент любого бизнеса. У вас есть набор данных о продажах конкретного предприятия по месяцам: [8, 15, 13, 15, 17, 20, 19, 20, 7, 14, 14, 18].
Вам поручили написать небольшой сервис (программисты все заняты), который умеет по предоставленному ему массиву месячных продаж рассчитывать:
- Сумму всех продаж
- Среднюю сумму продаж в месяц
- Номер месяца, в котором был пик продаж (осуществлены продажи на максимальную сумму)
- Номер месяца, в котором был минимум продаж (осуществлены продажи на минимальную сумму)
- Кол-во месяцев, в которых продажи были ниже среднего
- Кол-во месяцев, в которых продажи были выше среднего

Что сделано:
- Создан проект на базе Maven;
- Подключенны зависимости JUnit Jupiter & Surefire Plugin;
- Создан класс с необходимыми методами;
- Созданы авто-тесты (по одному на метод).

### Предварительные требования
- На компьютере пользователя должна быть установлена Intellij IDEA

### Установка и запуск
1. Склонировать проект на свой компьютер
	- открыть терминал Intellij IDEA
	- ввести команду 
		```
		git clone https://github.com/AndryRusff/Java_2-4-2
		```
1. Открыть склонированный проект в Intellij IDEA
1. Запустить авто-тесты (это можно сделать с помощью команды mvn clean test)
