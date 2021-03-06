# «Объектно-ориентированное программирование и проектирование»
## Домашнее задание по курсу "Java для тестировщиков"
## Тема: «3.1. «Объектно-ориентированное программирование и проектирование», задание «Радиоман»

### Задача
Создайте класс Radio, в котором храните следующие поля:

- Номер текущей (прослушиваемой) радиостанции
- Громкость звука

Требования к работе с радиостанциями:
Номер текущей радиостанции изменяется в пределах от 0 до 9
Если текущая радиостанция - 9 и клиент нажал на кнопку next (следующая) на пульте, то текущей должна стать 0-ая; в остальных случаях радио переключается просто на следующую станцию. (создайте отдельный метод для этой операции)
Если текущая радиостанция - 0 и клиент нажал на кнопку prev (предыдущая) на пульте, то текущей должна стать 9-ая; в остальных случаях радиопереключается просто на предыдущую станцию/ (создайте отдельный метод для этой операции)
Клиент должен иметь возможность выставлять номер радиостанции через прямое указание её номера (сделайте сеттер с проверкой на допустимость номера станции)

Требования к работе с уровнем громкости звука:
Клиент должен иметь возможность увеличивать и уменьшать уровень громкости звука (в пределах от 0 до 10)*
Если уровень громкости звука достиг максимального значения, то дальнейшее нажатие на + не должно ни к чему приводить (создайте отдельный метод для этой операции, см. ниже пример)
Если уровень громкости звука достиг минимального значения, то дальнейшее нажатие на - не должно ни к чему приводить (создайте отдельный метод для этой операции)

Что сделано:
- Подключен и настроен плагин Surefire так, чтобы сборка падала в случае отсутсвия тестов;
- Подключен плагин JaCoCo в режиме генерации отчётов;
- Созданы авто-тесты, 100% покрытие по branch'ам;
- Подключена CI на базе Github Actions.

### Предварительные требования
- На компьютере пользователя должна быть установлена Intellij IDEA

### Установка и запуск
1. Склонировать проект на свой компьютер
	- открыть терминал Intellij IDEA
	- ввести команду 
		```
		git clone https://github.com/AndryRusff/Java_3-1/
		```
1. Открыть склонированный проект в Intellij IDEA
1. Запустить авто-тесты (это можно сделать с помощью команды mvn clean test)
