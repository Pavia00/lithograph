## Чем мы занимаемся и кто мы?
Проектируем литограф под тех.процесс **28 нм** и под любой существующий размер пластин от **100 мм до 450 мм**. Мы - это просто группа в телеграмме, в которой присутствуют как специалисты, так и просто интересующиеся микроэлектроникой участники. Вы тоже можете стать частью этой группы. Основные проектировщики:
**Денис Шилов** и **Missclick Очепятка**
## Возможно ли это в принципе?
Да. Спроектировать литограф - возможно. Есть миллиард сложностей на этом пути и проектирование литографа это только одно маленькое звено из всей цепочки сложного превращения песчинки кремния в высокотехнологичный процессор, но у нас нет другого выхода.
## Знаем ли мы что такое вообще производство?
Да. Мы все знаем, что такое чистые комнаты, манипуляторы, бизнес-планы, стены. Мы, конечно, все миллионы раз обсуждали, что нужен даже специальный порошок для стиральных машин, которые стирают рабочую одежду специалистов. Мы знаем, что необходим софт, которым в нынешних условиях невозможно пользоваться, мы все с кем-то когда то работали и работаем и с сумасшедшими гениями и с раздолбаями и с нечистыми на руку и с прекрасными специалистами и с теми кто учил нас или кого учили мы.
## Понимаем ли мы, что стоимость фабрики миллиарды долларов и что это невозможно сделать в условиях полной изоляции? 
Да, мы все тут умные, но бедные. Мы понимаем сложность (если выразить сложность по десятибальной шкале - это будет 15 из 10, мы все, конечно, смотрели [различные обзоры](https://www.youtube.com/watch?v=9CNH8vus0h8) возможностей российской микроэлектроники.
## Вы знаете, что помимо литографа нужен еще чистый кремний, его нарезка и доставка до фабрики?
Да, мы знаем, но на данном моменте мы сфокусированы на постройке литографа. В России делают чистый кремний (9N) в булях диаметром до 150 мм (методом зонной плавки), мы знаем печальную историю завода Нитол по производству поликремния.

## А что я получу, если вложу свои знания, опыт или финансы?
Мы не знаем.

## Что есть на данный момент?
Мы публикуем "[Этапы проектирования](/lithograph#этапы-проектирования)" — каждый элемент этапа обладает своей страницей с более подробной информацией. Возможно мы добавим [PlantUML](https://github.com/grassedge/generate-plantuml-action/blob/master/example/sample.md), но в связи с тем, что возможен переход с GitHub ( c Google Actions) на собственных хостинг - будем думать о визуализации.

## Материалы по теме
Интересные статьи, видео, записи конференций, в общем все то, что может помочь, мы выкладываем на [этой странице](/resources/SOURCES.MD)

## Я все понял, что мне делать то?
Если вы специалист по какому то этапу проектирования, производитель оборудования, поставщик, инженер, схемотехник, алкоголик, шпион или просто интересующийся этой темы - напишите об этом в нашей группе в [Телеграм](https://t.me/nirpg_ru)

## Как пользоваться GitHub?
Это очень просто - необходим аккаунт в github (вы можете воспользоваться при регистрации вашим google-account, например) - переходите в раздел [issue](https://github.com/TsarS/lithograph/issues), нажмите **New Issue** и пишите то, что вас интересует. Например "Добавьте в список производителей линз - ООО "Ромашка" на странице по EUV (ссылка на страницу), контакт такой-то.". Внутри каждого issue может идти обсуждение, после чего администратором делается **pull request** и информация, если она необходима, добавится на страницу. Так же информация, конечно, просто может быть добавлена администратором из чата в Телеграм.
Все изменения (как и предыдущие варианты) будут видны в [Pull Request](https://github.com/TsarS/lithograph/pulls)

### Эскиз литографа
![Эскиз литографа Missclick Очепятка](/resources/files/lithograph-13-05-2022.png)

## Технологический процесс литографа
![Технологический процесс Missclick Очепятка](/resources/files/idef-0-1.png)
Файл существует в формате VISIO - [здесь](/resources/files/IDEF0.vsd)

## Этапы проектирования 
### Разработка несущей рамы под литограф
- [x] Несущая поверхность для магнитной пластины
- [ ] Несущая рама для установки двух систем осей XY
- [ ] Разработка отсечки на магнитопроводящего материала вакуумной части от рабочей части
- [ ] Крепления кинематики по ШВП прецизионной точности под 6000 Н м\с 
- [ ] Разработка крепления манито-удерживающего крепления со штангой 
- [ ] Разработка отвода на раме под сканер 
### Разработка демпфирующих подвесов под всю установку.
- [ ] Торсионная механика демпфирования 
- [ ] Разработка механизма пневматической системы для рамы гашения остаточных внешних вибраций.
- [ ] Разработка подключения механизма регулирования работы пневмомеханики с балансом под инерцию столика с автоматикой регулирования под горизонтальный уровень.

### [Разработка прямоточного источника жесткого излучения ультрафиолета](stages/EUV.md) 
 - [ ] Определить необходимого расстояния
-  [ ] Сформировать световод и конусное схождение от источника к офсетному динамическому зеркалу
