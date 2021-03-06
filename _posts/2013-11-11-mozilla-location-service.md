---
title: "Mozilla Location Service: MozStumbler vs. Aurora"
---

Mozilla Location Service официально [представлен][новость]. Но я стал юзать его
ещё до  того, как это  стало мейнстримом!  Приятно осознавать, что  стал первым
подключившимся к  проекту в своём  регионе и одним  из первых в  стране. Данный
пост  о  том,  почему  мобильной лисички  недостаточно,  чтобы  помочь  Mozilla
Location Service в полной мере.

[![](/images/mozilla-location-service.png)][map]

Вкратце  -  Мозилла  устала  от   зависимости  от  несвободных  источников  для
геопозиционирования (а  именно - Google  Location Service; им же,  за неимением
собственных данных, пользуется и Опера) и  решила запилить свой, с блэкджеком и
открытостью - потому  как свободные аналоги скудны и рядом  с несвободными даже
не валялись.

Как  я узнал  об этом  проекте ещё  до того,  как тот  был представлен?  Просто
обратил  внимание  на  галочку  в  pre-beta  версии  (которая  зовётся  Аврора)
мобильного Файрфокса в настройках того, какие данные передавать Мозилле с целью
сделать продукт в частности и мир в  общем лучше. Помимо прочих там был пункт и
по  поводу  MLS  с  описанием "Помогите  улучшить  сервисы  геопозиционирования
Открытого  Веба,  позволив Авроре  собирать  и  отправлять анонимные  данные  о
сотовых вышках".  Я заинтересовался и спросил  у гугла, о чем  вообще разговор.
Гугл мне ответил  ссылкой на [MozStumbler][], согласно ридми  которого он делал
то же самое, что и Аврора.

Появился закономерный вопрос - а  зачем сторонняя софтина, если самый известный
продукт Мозиллы (путь и его бета-версия) уже включает данный функционал? Ответа
я нигде не  нашёл, кроме IRC. А  там мне сказали очень доходчиво,  что Аврора -
пассив,  а  MozStumbler  -  актив. Иначе  говоря,  Аврора  при  соответствующей
включённой опции  собирает данные  только когда  пользователь заходит  на сайт,
использующий геопозиционирование, а MozStumbler - всегда, когда включён.

Таким образом, чтобы помочь сделать мир лучше, поставить галочку в Авроре мало,
особенно  если  на  сайты  с фичами  геопозиционирования  заходишь  практически
никогда, как я, например.

Кстати, FYI, термины [геолокация][] и геопозиционирование не синонимы.



[новость]: http://blog.mozilla.org/services/2013/10/28/introducing-the-mozilla-location-service/
[map]: https://location.services.mozilla.com/map
[MozStumbler]: https://github.com/mozilla/MozStumbler/releases
[геолокация]: http://ru.wikipedia.org/wiki/Геолокация
