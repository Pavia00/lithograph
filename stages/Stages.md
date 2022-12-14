# Черновик этапов проектирования

## Степпер

###  Разработка столика для подложек
 - [ ]  Расчет магнитных соленоидов и сердечников из электротехнической стали для столика для подложек
- [ ]  Разработка положения соленоидов для магнитной левитации столика для подложек
 - [ ]  Спроектировать камеры для охлаждения столика для подложки
 - [ ]  Проектирование датчиков давления воды для охлаждение столика для подложек 
 - [ ]  Проектирование вакуумной фиксации на поворотном столике для подложки
 - [ ]  Расчет и разработка системы управления левитацией столика для подложек


 ### Разработка электротехнического оборудования для литографа
- [ ]  Установка и разработка вакуумной системы (ресивер, система управления, вакуумный насос)
- [ ]  Проектирование разводки электропитания степпера
- [ ]  Установка ВУТ систем и стабилизирующих по питанию систем 
- [ ]  Разработка систем гашения блуждающей ЭДС и обратной ЭДС в системе

###  Разработка несущей рамы под нанофотолитограф
 - [ ] Проектирование несущей рамы 
  - Несущая поверхность для магнитной пластины рамы
     - [ ] Проектирование характеристик и расположения каскадов магнитных соленоидов
     - [ ] Проектирование поверхности пластины (отверстия, крепеж, деформация)
 - Несущая рама для установки трех систем осей XY 
     - [ ] Правая рама штанги
     - [ ] Левая рама штанги
     - [ ] Нижняя рама штанги
 - [ ] Разработка отсечки на магнито проводящих материалов (фторопласт) вакуумной части от рабочей части
  - [ ] Крепления кинематики по ШВП прецизионной точности под 6000 Н м\с 
 - [ ] Разработка крепления манито-удерживающего крепления со штангой 
 - [ ] Разработка отвода на раме под фокальный сканер 
 - [ ] Разработка отвода под матричное, офсетное зеркало под механику точной настройки.
 - [ ] Разработка отвода загрузочного / выгружаемого лотка с мини камерой

 
 ### Разработка демпфирующих подвесов под всю установку
 - [ ] Торсионная механика демпфирования 
 - [ ] Разработка механизма пневматической системы для рамы гашения остаточных внешних вибраций
- [ ]  Разработка подключения механизма регулирования работы пневмомеханики с балансом под инерцию столика с автоматикой регулирования под горизонтальный уровень

-----------

 ### Разработка офсетного зеркала динамической матрицы
-  Разработка фокусного расстояния всей матрицы 
-  Разработка оборудования для изготовления линзы матрицы.
-  Разработка крепления электронной кинематики управления под пьезоэлектрические актюаторы
-  Разработка подложки крепления электронной кинематики 
-  Разработка крепления основы зеркала для крепления к раме с возможностью точной юстировки.
-  Расчет и разработка зеркала вогнутого офсетного промежуточного 
-  Разработка электронной сегментной подложки для управления прерываниями матрицы.



 - Разработка микрокамеры обменника 
- Разработка переходного механизма 
-  Разработка позиционирования подложки на столике в самой камере RX RY 
-  Настройка столика в безконтактной среде.
-  Очистка подложки с фоторизистом инертным газом от инородных частиц.
-  Механизм снятия подложки с закрепленным рисунком на фоторезисте.


### Разработка элетронно-управляющего комплекса  
-  Разработка схем управляющих контролеров периферийным оборудованием: демпферные систем, насосы, переходные камеры
-  Разработка управляющей схемы работы с столиком под подложку.
- Разработка блок управления по перемещения по полю столика под подложку с обратной связью 
-  Разработка блока работающего активацией сканера и передачи информации от него вычислительный комплекс
-  Подобрать центральный вычислительный модуль

### Разработка механизма позиционирования по сканеру 
-  Дисперсионного излучателя и дифракционного приемника

## EUV

### Разработка прямоточного источника жесткого излучения ультрафиолета с длиной волны 13,6 нм.
-  Определение необходимого расстояния  
-  Сформировать световод и конусное схождение от источника к офсетному динамическому зеркалу
- Разработать метод термического испарения олова в паровую основу 
-  Разработать матричную систему туннельных плазмогенераторов током высокой частоты.
-   Подобрать диффузной линзы паровыделителя под плазмогенератор 
-  Разработать систему охлаждения стержня 
-  Разработка охлаждения внешних стенок камеры
-  Разработка МДГ туннеля фильтра и ионного ветра с направлением к отсосу 


### Разработка ПО.
-  Проработать ПО прямого управления через ЦВМ всеми периферийными устройствами.
-  Проработать пользовательский Интерфейс управляющий комплексом.
-  Спрограммировать комплекс подсистем управлением с синхронизации стабильного демфинга 
-  Разработать программу координирования вафельного столика после позиции сканера.
-  Модуль для проверки всех температурных датчиков 
-  Программа сканирования на температурную зависимость подложки и управляющий модуль 
-  Программа управления высоты по Z  столика для подложек через контроллер.
-  Программа управления всей переходной миникамеры 

## Фабрика (фундамент, здание и т.д.)

### Разработать стабилизирующий фундамент под оборудование
 - Установка требований к помещениям, зданию и оборудованию
-  Разработать кольцо отсечки по периметру основного блока установки
-  Создать механизм гашения вертикальных вибраций (стойки, отсыпки, подложки)
-  Разработать универсальную подвеску гашения инерциальных вибраций горизонтальных вибраций и вол.
-  Разработать раму фундамент под нанофотолитограф под вес 50 т
