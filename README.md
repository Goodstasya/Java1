 Начало и окончание тестирования: 22.06.2020
#### Тестирование:

- документации по установке и установка OpenJDK11
- документации по работе с KeyValidator
- функциональное тестирование

В результате тестирования выявлены следующие дефекты:

https://github.com/Goodstasya/Java1/issues/5#issue-648787703

https://github.com/Goodstasya/Java1/issues/6#issue-648790747

Описание

Шаги

1. Согласно прилагаемой документации по установке приложения проходим по ссылке https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md

2. Источником для установки программы OpenJDK11 является ссылка www.adoptopenjdk.net.
Выбираем версию Java - OpenJDK11 (LTS)
и JVM Java - HotSpot.

3. Приложение OpenJDK11 запускается и совместимо с Java 11
![](Ф1.png)

4. Далее скачать приложение KeyValidator.class по ссылке https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md

5. На проверку указаны 

5.1. Валидные ключи:

8f05e6a7-70e9-33d7-bfe7-b19eae0d8998

80b427f8-92cd-3aae-ba04-3927fbe17c6

b295bc63-9f03-3b4b-af80-969b39f8c262

387eedc6-12e9-3b32-9881-63b6b5e85317

c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

5.2. Невалидные ключи:

18252235-78e0-44a5-8720-556f0c7da17a

e66075b6-ddad-445e-baf6-161b3289522b

b6d53250-f07e-4352-a293-6102ddf7f1ca

c2bc778a-1cb9-46c6-b435-0489649d2a42

2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

#### Ожидаемый результат: 
руководство по запуску программы KeyValidator верное, все ключи в описании корректные

#### Фактический результат:

файл для запуска программы KeyValidator работает, ключи в описании с ошибками. Требуется исправление ключей. Ссылки на баги в Issues прилагаются.

Тестирование заняло 60 минут

Тестирование проводилось на Windows 10 / 64 бит

Java 11.0.7.
