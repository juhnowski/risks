# 1. Требования
## а. Стабильность
Меняются ли требования даже когда продукт в разработке?
### [1] Стабильны ли требования?
#### (1.a) Как это влияет на систему? 
- Качество
- Функциональность 
- График 
- Интеграция 
- Дизайн 
- Тестирование
### [2] Изменяются ли внешние интерфейсы?

## б. Полнота
Требования отсутствуют или не полностью определены?
### [3] Есть ли в спецификациях какие-либо уточнения?
### [4] Есть ли требования, о которых вы знаете, что они должны быть в спецификации, но их нет?
#### (4.a) Сможете ли вы ввести эти требования в систему?
### [5] Есть ли у клиента неписаные требования/ожидания?
#### (5.a) Есть ли способ учесть эти требования?
### [6] Полностью ли определены внешние интерфейсы?
## в. Ясность
Являются ли требования неясными или нуждаются в интерпретации?
### [7] Способны ли вы понять требования в том виде, в котором они написаны?
#### (7.a) Удовлетворительно ли разрешаются неоднозначности?
#### (7.b) Нет неясностей или проблем с интерпретацией?
## д. Период действия
Приведут ли требования к продукту, который имеет в виду клиент?
### [8] Существуют ли какие-либо требования, которые могут не указывать, чего на самом деле хочет заказчик?
#### (8.a) Как вы решаете эту проблему?
### [9] Вы и заказчик понимаете под требованиями одно и то же?
#### (9.a) Существует ли способ определить это?
### [10] Как вы проверяете требования?
- Прототипирование
- Анализ 
- Моделирование
## е. Осуществимость
Являются ли требования невыполнимыми из
аналитическая точка зрения?
### [11] Существуют ли какие-либо требования, которые технически трудно реализовать?
#### (11.а) Какие они?
#### (11.b) Почему их сложно реализовать?
#### (11.c) Были ли выполнены технико-экономические обоснования этих требований?
#### (11.c.1) Насколько вы уверены в предположениях, сделанных в исследованиях?
## ф. Прецедент
Указывается ли в требованиях что-то, что никогда не делалось раньше? что еще не сделано?
### [12] Существуют ли современные требования?
- Технологии 
- Методы
- Языки 
- Оборудование
#### (12.a) Есть ли что-то из этого новое для вас?
#### (12.b) Обладают ли программисты достаточными знаниями в этих областях?
#### (12.b.1) Есть ли план приобретения знаний в этих областях?
## г. Шкала
Указаны ли в требованиях опыт к компании требующий более крупной организация,чем наша
### [13] Вызывают беспокойство размер и сложность системы?
#### (13.a) Делали ли вы раньше что-то такого масштаба и сложности?
#### [14] Требует ли размер организации большей организации, чем обычно для нашей компании?

# 2. Дизайн
## а. Функциональность
Есть ли потенциальные проблемы с соблюдением функциональных требований?
### [15] Существуют ли определенные алгоритмы, которые могут не удовлетворять требованиям?
#### (15.a) Являются ли какие-либо алгоритмы или схемы маргинальными с точки зрения удовлетворения требований?
### [16] Как вы определяете осуществимость алгоритмов и проектов?
- Прототипирование
- Моделирование
- Анализ 
- Моделирование

## б. Сложность
[Будет ли сложно достичь дизайна и/или реализации?]
### [17] Зависит ли какой-либо план от нереалистичных или оптимистичных предположений?
### [18] Существуют ли какие-либо требования или функции, которые сложно разработать?
#### (18.a) Есть ли у вас решения для всех требований?
#### (18.b) Каковы требования?
- Почему они трудны?

## в. Интерфейсы
Хорошо ли определены и контролируются внутренние интерфейсы (аппаратное и программноеобеспечение)?
### [19] Хорошо ли определены внутренние интерфейсы?
- Программное обеспечение для программного обеспечения
- Программно-аппаратное обеспечение
### [20] Существует ли процесс определения внутренних интерфейсов?
#### (20.a) Существует ли процесс контроля изменений для внутренних интерфейсов?
### [21] Аппаратное обеспечение разрабатывается параллельно с программным обеспечением?
#### (21.a) Изменяются ли технические характеристики оборудования?
#### (21.b) Все ли интерфейсы к программному обеспечению определены?
#### (21.c) Будут ли модели инженерного проектирования, которые можно использовать для проверки
программного обеспечение?

## д. Производительность
Существует ли жесткое время отклика или
требования к пропускной способности?

### [22] Есть ли проблемы с производительностью?
- Пропускная способность 
- Планирование асинхронных событий в реальном времени 
- Реагирование в реальном времени 
- Сроки восстановления 
- Время отклика 
- Ответ базы данных, конфликт или доступ
### [23] Был ли проведен анализ производительности?
#### (23.a) Каков ваш уровень уверенности в анализе эффективности?
#### (23.b) Есть ли у вас модель для отслеживания производительности посредством проектирования и реализации?

## е. Тестируемость
Продукт сложный?  или невозможно проверить?

### [24] Будет ли легко тестироваться программное обеспечение?
### [25] Включает ли дизайн функции, облегчающие тестирование?
### [26] Участвуют ли тестировщики в анализе требований?

## ф. Аппаратные ограничения
[Есть ли жесткие ограничения на целевое оборудование?] 
### [27] Ограничивает ли аппаратное обеспечение вашу способность выполнять какие-либо требования?
- Архитектура
- Объем памяти 
- Пропускная способность 
- Реагирование в режиме реального времени 
- Время отклика 
- Сроки восстановления 
- Производительность базы данных
- Функциональность 
- Надежность 
- Доступность

## г. Программное обеспечение, не связанное с разработкой
Есть ли проблемы с программным обеспечением, используемым в программе, но не разработанным программой?

При повторном использованииили существует переработанное программное обеспечение

### [28] Вы повторно используете или переделываете программное обеспечение, не разработанное для программы?
#### (28.a) Предвидите ли вы какие-либо проблемы?
- Документация 
- Производительность 
- Функциональность 
- Своевременная доставка
- Индивидуальная настройка

### [29] Существуют ли какие-либо проблемы с использованием COTS (коммерческого готового программного обеспечения)?
- Недостаточно документации для определения интерфейсов, размера или производительности. 
- Низкая производительность.
- Требует большой доли памяти или хранилища базы данных.
### [30] Предвидите ли вы какие-либо проблемы с интеграцией обновлений или версий программного обеспечения COTS?

# 3. Код и модульное тестирование

## а. осуществимость
Является ли реализация проекта сложной или
невозможной?
### [31] Существуют ли какие-либо части реализации продукта, не полностью определенные дизайном? Спецификация?
### [32] Легко ли реализовать выбранные алгоритмы и схемы?

## б. Тестирование
Являются ли указанные уровень и время адекватными для модульного тестирования?
### [33] Начинаете ли вы модульное тестирование перед проверкой кода относительно проекта?
### [34] Было ли указано достаточное модульное тестирование?
### [35] Достаточно ли времени для выполнения всех модульных тестов, которые, по вашему мнению, должны быть выполнены?
### [36] Будут ли компромиссы в отношении модульного тестирования, если возникнут проблемы с расписанием?

## в. Кодирование/реализация
Естьли проблемы с кодированием и реализацией?
### [37] Являются ли спецификации дизайна достаточно подробными для написания кода?
### [38] Меняется ли дизайн во время написания кода?
### [39] Существуют ли системные ограничения, затрудняющие написание кода?
- Синхронизация
- Память 
- Внешнее хранилище
### [40] Подходит ли язык для создания программного обеспечения этой программы?
### [41] Используются ли в программе несколько языков?
#### (41.a) Существует ли совместимость интерфейса между кодом, созданным разными компиляторами?
### [42] Является ли компьютер разработки таким же, как целевой компьютер?
#### (42.a) Существуют ли между ними различия в компиляторах?

** Если используется экспериментальное оборудование **

### [43] Соответствуют ли технические характеристики оборудования программному обеспечению?
### [44] Изменяются ли спецификации оборудования во время написания кода?

# 4. Интеграция и тестирование
## а. Среда
Являются ли среда интеграции и тестирования адекватной?
### [45] Будет ли достаточно оборудования для адекватной интеграции и тестирования?
### [46] Есть ли проблема с разработкой реалистичных сценариев и тестовых данных для демонстрации? любые виды  требования? 
- Указанный трафик данных 
- Реагирование в режиме реального
времени 
- Асинхронная обработка событий
- Многопользовательское взаимодействие
### [47] Можете ли вы проверить производительность в вашем учреждении?
### [48] Облегчает ли тестирование аппаратное и программное обеспечение?
#### (48.a) Достаточно ли этого для всех испытаний?

## б. Продукт
Неадекватно ли определение интерфейса, неадекватны ли средства, недостаточно ли времени?
### [49] Будет ли целевое оборудование доступно при необходимости?
### [50] Согласованы ли критерии приемлемости для всех требований?
#### (50.a) Имеется ли официальное соглашение?
### [51] Определены ли внешние интерфейсы, документированы ли они?
### [52] Существуют ли какие-либо требования, которые будет сложно протестировать?
### [53] Была ли указана достаточная интеграция продукта?
### [54] Было ли выделено достаточно времени для интеграции и тестирования продукта?

** Если COTS **

### [55] Будут ли данные поставщиков приниматься при проверке требований, выделенных для COTS? для каких продуктов?
#### (55.a) Ясно ли это указано в контракте?

## в. Система
[Системная интеграция не скоординирована, определение интерфейса, плохое или неадекватные условия?]
### [56] Была ли указана достаточная системная интеграция?
### [57] Было ли выделено достаточно времени для системной интеграции и тестирования?
### [58] Все ли подрядчики входят в группу интеграции?
### [59] Будет ли продукт интегрирован в существующую систему?
#### (59.a) Существует ли параллельный переходный период с существующей системой?
#### (59.a.1) Как вы гарантируете правильную работу продукта при интеграции?
#### Будет ли происходить системная интеграция на сайте заказчика?

# 5. Инженерные специальности
## а. Ремонтопригодность
Будет ли реализация трудна для понимания и
поддержки?
### [61] Создают ли архитектура, дизайн или код какие-либо трудности в обслуживании?
### [62] Привлекаются ли специалисты по техническому обслуживанию на раннем этапе проектирования?
### [63] Подходит ли документация на продукт для обслуживания сторонней организацией?

## б. Надежность
Являются ли надежность или трудно выполнить требования доступности?
### [64] Распространяются ли требования надежности на программное обеспечение?
### [65] Распределены ли требования доступности к программному обеспечению?
#### (65.a) Есть ли проблемы со сроками восстановления?

## в. Безопасность
Являются ли требования безопасности невыполнимыми и недоказуемыми?
### [66] Распространяются ли требования безопасности на программное обеспечение?
#### (66.a) Видите ли вы какие-либо трудности в соблюдении требований безопасности?
### [67] Будет ли сложно проверить соблюдение требований безопасности?

## д. Безопасность
Являютсяли требования безопасности более строгими, чем текущее состояние программы или практики?
### [68] Существуют ли беспрецедентные или самые современные требования безопасности?
### [69] Это система ISO/IEC 15408?
### [70] Вы применяли этот уровень безопасности раньше?

## е. Человеческие факторы
Будетли система затруднена или неудобна в использовании из-за определения человеческого интерфейса?
### [71] Видите ли вы какие-либо трудности в выполнении требований человеческого фактора?
#### (71.a) Как вы обеспечиваете выполнение требований к человеческому интерфейсу?

**Если прототипирование**

### (71.a.1) Это одноразовый прототип?
### (71.a.1a) Вы занимаетесь эволюционным развитием?
### (71.a.1a.1) Есть ли у вас опыт такого развития?
### (71.a.1a.2) Предоставляются ли промежуточные версии?
### (71.a.1a.3) Усложняет ли это контроль за изменениями?

## ф. Технические характеристики
Достаточна ли документация для проектирования, внедрения и тестирования системы?
### [72] Соответствует ли спецификация требований к программному обеспечению проектированию системы?
### [73] Соответствуют ли спецификации аппаратного обеспечения разработке и внедрению программного обеспечения?
### [74] Хорошо ли определены требования к внешнему интерфейсу?
### [75] Являются ли спецификации теста достаточными для полного тестирования системы?
### [76] Соответствуют ли спецификации проекта реализации системы?
• Внутренние интерфейсы