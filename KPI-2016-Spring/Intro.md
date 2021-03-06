## Введение в Node.js

Дата: 2016-06-06  
Группы: ИП-51, ИП-52, ИП-53, ИП-54  

Добрый день,

1. Презентации, которые я показывал на двух предыдущих лекциях можно найти тут:
https://github.com/HowProgrammingWorks/Letters/blob/master/Docs/NODEJS/node-kpi-2016.pdf
Видео к слайдам есть ниже в этом письме.

2. Многие писали мне с просьбой прислать лабораторные работы, но я спросил у Максима и
Ирины Павловны, оказалось, что у вас не хватает для этого пар. Могу сделать объяснения
лабораторных в среду на 2 паре, отведя для этого половину лекции, а сами работы вы
сделаете дома.

3. Или есть другой вариант, в любом случае будет летняя школа по JavaScript и Node.js,
это уже после всех экзаменов и все смогут уже спокойно ее посещать, расписание
сообщу дополнительно.

4. Структура нашего курса на следующий год будет скоро опубликована,
но пока вы можете посмотреть структуру краткого курса по переподготовке Node.js
разработчиков из JavaScript программистов, из нее видно основной набор знаний по Node.js,
который актуален сейчас и будет включен частью нашего большого курса:
https://github.com/HowProgrammingWorks/Letters/tree/master/Docs/NODEJS
До Node.js мы конечнобудем подробнее изучать JavaScript, паттерны программирования
для JavaScript и Node.js, архитектуру и парадигмы, потому, что JavaScript это
мульипарадигменный язык, в котором можно смешивать подходы: структурное, функциональное,
объектное, прототипное, асинхронное, реактивное, декларативное программирование и
метапрограммирование. Все это будет входить в программу курса вместе с примерами.

5. Кому интересно посмотреть вопросы на экзамен по Архитектуре и проектированию
программного обеспечения для 2 курса, их можно найти тут:
https://github.com/HowProgrammingWorks/Letters/tree/master/Docs/SOFTARCH

6. Кто хочет самостоятельно подучить JavaScript или обновить свои знания, то есть
две электронные книги: https://learn.javascript.ru/ и http://gabdrahimov.ru/javascript-uchebnik

7. Несколько моих лекций по Node.js и докладов на конференциях тут:
  * Архитектура программных систем на Node.js  
  https://www.youtube.com/watch?v=Try7lmWikao
  * Вводная лекция по Node.js (с коллегами)  
  https://www.youtube.com/watch?v=0oIiPJtfUpw
  * Примеры быстрой разработки API на масштабируемом сервера приложений  
  https://www.youtube.com/watch?v=f6McffaVq78

8. Несколько моих статей можно почитать тут:
  * Impress Application Server простыми словами  
  https://habrahabr.ru/post/247543/
  * Метапрограммирование (с примерами на JavaScript)  
  https://habrahabr.ru/post/227753/
  * Назад, к технологиям верхнего палеолита, от любимых всеми REST, STATEless, CRUD, CGI, FastСGI и MVC  
  https://habrahabr.ru/post/204958/
  * А MVC ли это?  
  https://habrahabr.ru/post/117791/
  * Как исправить ошибку в NodeJS и нечаянно поднять производительность в 2 раза  
  https://habrahabr.ru/post/264851/

9. Как установить Node.js и подготовить среду для разработки:
  * Все есть на первой странице https://nodejs.org/
  * Ставьте версию 6.2.1 (или последнюю на текущий момент)
  * или вот тут лежат у меня скрипты установки для разных версий Ubuntu, Debian, CentOS  
  https://github.com/tshemsedinov/impress/tree/master/deploy  
  Скрипт ставит полный набор, MongoDB, Node.js, Impress и вспомогательные вещи.  
  Из скрипта можно взять только команды для установки ноды.  
  Например, для установки на Ubuntu сразу бинарников:
  ```
  sudo apt-get -y install build-essential openssl libssl-dev pkg-config python
  curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
  sudo apt-get install -y nodejs
  ```
  Скрипты, которые `*-src.sh` это для установки из исходников, т.е. для сборки,
  это работает долго, но можете попробовать, если хотите, для опыта.

С уважением,  
~Тимур Шемсединов
