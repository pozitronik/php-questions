# PHP

## Версии и особенности PHP
- [ ] Чем вы руководствуетесь при выборе версии PHP?
- [ ] Назовите основные изменения между PHP 7 и PHP 8
- [ ] Что вам понравилось из нововведений в PHP 8?
- [ ] Какие фичи PHP 7.4 вы использовали?
- [ ] Как вы относитесь к тенденциям развития PHP?
- [ ] Что последнего вводилось в PHP?

## Типы данных и операции
- [ ] Чему равен strlen('Вася')? (Объясните, почему результат может отличаться от ожидаемого)
- [ ] Как посчитать количество символов в строке UTF-8?
- [ ] Как устроен массив в PHP?
- [ ] Что такое zval и как он устроен? Как zval работает с разными типами данных?
- [ ] Если в переменной $a лежит массив и я присваиваю его переменной $b, изменится ли выделенная память и почему?

## Ключевые слова и конструкции
- [ ] Чем отличается self от static?
- [ ] В каких контекстах может использоваться ключевое слово static?
- [ ] Когда нужно использовать ключевое слово final?
- [ ] Какая проблема есть при использовании final?
- [ ] Зачем в PHP нужна директива strict_types? Какая у неё область действия?

## ООП в PHP
- [ ] Какие магические методы есть в PHP?
- [ ] Как работают генераторы в PHP?
- [ ] Что такое трейты? В чем их плюсы и минусы?
- [ ] Может ли абстрактный класс существовать без реализованных методов?
- [ ] Когда бы вы использовали интерфейс, а когда абстрактный класс?
- [ ] Что такое композиция и чем она лучше наследования?
- [ ] Как можно реализовать множественное наследование в PHP?
- [ ] Объясните концепции абстракции, инкапсуляции и полиморфизма.
- [ ] Какие проблемы есть у наследования?

## Продвинутые концепции
- [ ] Что такое рефлексия в PHP?
- [ ] Что такое позднее и раннее связывание?
- [ ] Что такое SPL? Какие классы в нем есть?
- [ ] Где мы могли бы использовать Iterator?
- [ ] Что такое замыкания (closures) в PHP?

## Общие вопросы
- [ ] Зачем нужна обработка ошибок в PHP?
- [ ] Расскажите, где хранятся сессии в PHP?
- [ ] Если мы пытаемся записать файл на диск в PHP, какие могут случиться ошибки?

## Углубленные вопросы по PHP
- [ ] Как работает сборщик мусора в PHP? Какие алгоритмы он использует?
- [ ] Что такое FFI в PHP? В каких ситуациях его использование может быть оправдано?
- [ ] Как работает механизм поздней статической привязки (Late Static Binding) в PHP?
- [ ] Что такое атрибуты (Attributes) в PHP 8? Приведите пример их использования.
- [ ] Какие есть проблемы при использовании static и какие ему есть альтернативы?
- [ ] Как работает оператор задания значения по умолчанию (Null Coalescing) ?? в PHP? Чем он отличается от тернарного оператора?
- [ ] Что такое Spaceship operator?
- [ ] Что такое финализаторы (finalizers) в PHP? Когда их следует использовать?

## Расширения PHP
- [ ] Какие расширения PHP вы использовали в своих проектах?
- [ ] Как написать собственное расширение для PHP? С какими трудностями можно столкнуться?
- [ ] Что такое PECL? Какие популярные расширения из PECL вы знаете?

## Управление памятью
- [ ] Как работает выделение и освобождение памяти в PHP?
- [ ] Что такое циклические ссылки и как они влияют на сборку мусора?

## Обработка ошибок и исключений
- [ ] Какие уровни ошибок существуют в PHP? Как настроить обработку разных уровней?
- [ ] В чем разница между ошибками и исключениями в PHP?
- [ ] Как создать собственный обработчик исключений/ошибок?

## Управление жизненным циклом приложения
- [ ] Что такое Graceful Shutdown и чем он отличается от обычного завершения?
- [ ] Какие шаги вы предпринимаете для реализации Graceful Shutdown в PHP-приложении?
- [ ] Как обеспечить корректное завершение долгоиграющих процессов при остановке приложения?
- [ ] Какие проблемы могут возникнуть при неправильном завершении PHP-приложения?
- [ ] Как реализовать механизм перезапуска PHP-приложения без потери текущих запросов?

# Производительность и оптимизация

## Оптимизация кода
- [ ] Представьте, что у нас есть массив чисел типа float. Как его можно просуммировать, чтобы потери точности были наименьшими?
- [ ] Какая алгоритмическая сложность у функций in_array(), array_key_exists(), array_unique()?
- [ ] Как бы вы реализовали array_unique()?
- [ ] Что такое цикломатическая сложность?
- [ ] Как работает пул соединений (connection pooling) в PHP? Какие библиотеки для этого существуют?
- [ ] Что такое горячий и холодный пути выполнения кода? Как это влияет на оптимизацию?

## Производительность PHP
- [ ] Как реализовать кэширование на уровне байткода PHP? Какие инструменты для этого существуют?
- [ ] За счет чего улучшили производительность в PHP 7.x по сравнению с PHP 5.x?
- [ ] Знаете ли вы, как работает JIT-компиляция в PHP? Что должно быть в коде, чтобы она работала эффективно?
- [ ] Какие настройки PHP.ini вы бы изменили для повышения производительности высоконагруженного веб\-приложения?
- [ ] Как работает OpCache в PHP? Какие преимущества он дает?
- [ ] Что такое preloading в PHP 7.4+? Как его настроить и в каких случаях использовать?

## Профилирование
- [ ] Какие инструменты профилирования PHP-кода вы использовали? Какие у них преимущества и недостатки?
- [ ] Как профилировать потребление памяти в PHP-пёриложении и отслеживать её утечки? 

- [ ] Что такое flame graphs? Как их использовать для анализа производительности PHP-приложения?
- [ ] Как настроить мониторинг производительности PHP-приложения в production-среде?
- [ ] Какие метрики важно отслеживать для оценки здоровья PHP-приложения?

# Базы данных

## Реляционные базы данных
- [ ] С какими реляционными СУБД вы работали?
- [ ] Что бы вы выбрали между MySQL и PostgreSQL? Почему?

### Индексы

- [ ] Как работают индексы? Какие они бывают, их плюсы и минусы?
- [ ] Что такое кластерные/некластерные индексы (они же первичные/вторичные ключи)?
- [ ] Индексы делают запросы быстрее или медленнее?
- [ ] Как посмотреть, какие индексы задействованы в конкретной таблице?
- [ ] Какое максимальное количество индексов может быть задействовано в рамках одного запроса для одной таблицы?
- [ ] Представьте, у нас есть таблица на миллион записей, в ней колонка с типом bool. Нужен ли индекс для неё и почему?
- [ ] Сколько индексов можно создать на таблицу?
- [ ] Создаются ли какие-то индексы по умолчанию на таблицу?
- [ ] В чем отличие индексов от уникальных индексов?
- [ ] Расскажите про индексы в MySQL, какие бывают и какая у них структура?
- [ ] Какой порядок полей должен быть в составном индексе?
- [ ] Как работает B-tree индекс?

### Ключи и связи

- [ ] В чем отличие primary key от foreign key?
- [ ] Что такое foreign key? Для чего это? Плюсы и минусы?
- [ ] При создании foreign key, что добавляется ещё автоматически?
- [ ] В чем отличие primary key от unique?

### Транзакции

- [ ] Зачем нужны транзакции?
- [ ] Какие уровни изоляции транзакций существуют?
- [ ] Как запустить транзакцию в транзакции? Есть ли обходной способ?
- [ ] Каким четырем признакам (ACID) должны соответствовать транзакции?
- [ ] Какие способы начать и завершить транзакцию вы знаете?
- [ ] Можно ли не делать явно commit и rollback?
- [ ] Автокоммит — это хорошо или плохо?
- [ ] Можно ли использовать БД без транзакций?
- [ ] В какой момент вы принимаете решение, что нужно использовать транзакцию?
- [ ] Обработка исключений в транзакциях
- [ ] Когда предпочтительнее использовать явное управление транзакциями?

### Блокировки

- [ ] Что такое lock и что такое deadlock?
- [ ] При какой ситуации может возникнуть deadlock?
- [ ] Происходит ли блокировка при изменении индекса?

### Оптимизация и анализ запросов

- [ ] Как найти и ускорить медленные запросы в MySQL?
- [ ] Как проанализировать запрос?
- [ ] Что покажет EXPLAIN?
- [ ] Есть таблица с несколькими индексами, в EXPLAIN используется не тот индекс, который нам нужен. Можно ли как-то исправить эту ситуацию?

### Репликация, шардирование, миграции

- [ ] Расскажите кратко про термины: шардирование, партиционирование, репликация.
- [ ] Подробнее о шардировании
- [ ] Принципы различных типов репликации?
- [ ] Как решать проблемы отставания реплик?
- [ ] Одновременно прилетают два запроса в master-master БД, возникает конфликт. Какие способы есть разрешения этой проблемы? На каком уровне должны приниматься решения по этой проблеме? Как бы вы разрешали эту проблему на уровне приложения?
- [ ] Знакома ли вам software-репликация?
- [ ] Какие подходы вы знаете для миграции схемы базы данных без простоя в работе приложения?

### Оптимизация БД

- [ ] Представьте, БД не справляется с нагрузкой, мы много пишем и читаем из неё. Как можно улучшить эту ситуацию?
- [ ] Какие знаете способы масштабирования БД?
- [ ] Для чего полезна денормализация данных в БД?
- [ ] Мы выполняем в большой высоконагруженной таблице ALTER, какие проблемы могут возникнуть и как их можно избежать?
- [ ] Какие приемы вы используете для оптимизации сложных SQL-запросов?
- [ ] Как реализовать эффективную пагинацию для больших наборов данных в PHP?
- [ ] Как оптимизировать запросы с использованием подзапросов?
- [ ] Что такое query plan? Как его анализировать и оптимизировать?

## NoSQL базы данных
- [ ] С какими NoSQL базами данных вы работали?
- [ ] Что можете рассказать про Redis?
- [ ] В чем разница между обычным Redis и кластерным?
- [ ] Какие типы данных могут быть в Redis?
- [ ] Какое максимальное значение может иметь ключ в Redis?
- [ ] Как в Redis хранятся данные? Возможно ли в нем делать индексы?
- [ ] Какие преимущества и недостатки у MongoDB?
- [ ] Какая структура в MongoDB?
- [ ] Можно ли в MongoDB делать Join? Какие есть способы реализовать это в приложении?
- [ ] Использовали ли ClickHouse и как? Какие движки использовали?
- [ ] В чем особенности ClickHouse?
- [ ] В каких случаях вы бы предпочли использовать NoSQL базу данных вместо реляционной в PHP-проекте?
- [ ] Как работать с MongoDB в PHP? Какие преимущества дает использование MongoDB?
- [ ] Как реализовать кэширование данных с использованием Redis в PHP-приложении?

## Распределенные базы данных
- [ ] Что такое CAP-теорема? Как она применима к распределенным базам данных?
- [ ] Какие стратегии распределения данных вы знаете? В чем их преимущества и недостатки?
- [ ] Как обеспечить консистентность данных в распределенной системе?

## Elasticsearch
- [ ] Как интегрировать Elasticsearch в PHP-приложение?
- [ ] Какие преимущества дает использование Elasticsearch для полнотекстового поиска по сравнению с поиском в MySQL?
- [ ] Как оптимизировать индексацию и поиск в Elasticsearch для PHP-приложения?

# Паттерны проектирования и архитектура ПО

## ООП
- [ ] Что такое ООП?
- [ ] Что такое GRASP?

## SOLID
- [ ] Что такое SOLID? Расшифруйте каждую букву аббревиатуры.
- [ ] Как вы применяете принцип единственной ответственности (SRP) в PHP-коде?
- [ ] Приведите пример применения принципа открытости/закрытости (OCP) в PHP.
- [ ] Как реализовать принцип подстановки Барбары Лисков (LSP) в PHP?
- [ ] Как реализовать принцип разделения интерфейса (ISP) в PHP-приложении?
- [ ] Как реализовать принцип инверсии зависимостей (DIP) в PHP-приложении?
- [ ] Какие преимущества дает использование фабрики в контексте принципов SOLID?
- [ ] Что такое YAGNI, DRY, KISS, SOLID? Можете расшифровать?
- [ ] Какие принципы SOLID способствуют уменьшению связанности?
- [ ] Какие есть причины для передачи объектов через интерфейс?
- [ ] Как бы вы сформулировали SRP (Принцип единственной ответственности), если бы к вам пришел джуниор и сказал "не понимаю"?
- [ ] Подумай о особенностях тестирования системы, построенной с применением принципов SOLID. Что тут можно выделить?

## Паттерны GoF

### Порождающие паттерны: абстрагирование инстанцирования

- [ ] Фабричный метод (Factory Method)
- [ ] Абстрактная фабрика (Abstract Factory)
- [ ] Строитель (Builder)
- [ ] Прототип (Prototype)
- [ ] Одиночка (Singleton)
- [ ] Разница между Фабрикой, Создающим методом, Статическим фабричным методом, Простой фабрикой, Фабричным методом, Абстрактной фабрикой?
- [ ] В чем разница между фабрикой и оператором new?

### Структурные паттерны: удобная в поддержке иерархия

- [ ] Адаптер (Adapter)
- [ ] Мост (Bridge)
- [ ] Компоновщик (Composite)
- [ ] Декоратор (Decorator)
- [ ] Фасад (Facade)
- [ ] Легковес (Flyweight)
- [ ] Заместитель (Proxy)

### Поведенческие паттерны: эффективное взаимодействие

- [ ] Цепочка обязанностей (Chain of Responsibility)
- [ ] Команда (Command)
- [ ] Итератор (Iterator)
- [ ] Посредник (Mediator)
- [ ] Снимок (Memento)
- [ ] Наблюдатель (Observer)
- [ ] Состояние (State)
- [ ] Стратегия (Strategy)
- [ ] Шаблонный метод (Template Method)
- [ ] Посетитель (Visitor)
- [ ] Какие поведенческие паттерны проектирования вы часто используете в PHP? Приведите примеры.
- [ ] В каких ситуациях вы бы предпочли использовать паттерн Стратегия вместо простых условных операторов?
- [ ] Можете ли вы привести пример реального использования паттерна Наблюдатель в PHP?

## Внедрение зависимостей (Dependency Injection)
- [ ] Что такое Dependency Injection (DI)?
- [ ] В чем разница между внедрением зависимости и инверсией зависимости?
- [ ] Если бы не было DI, то чем бы его можно было заменить?
- [ ] Зачем нужен DI?

## Паттерны для работы с базами данных
- [ ] Какие основные паттерны ORM вам известны? В чем между ними разница?
- [ ] Расскажите о паттерне Repository.
- [ ] Можете сравнить ActiveRecord и Data Mapper? Преимущества и недостатки.
- [ ] В чем недостатки ActiveRecord?
- [ ] В чем сложность тестирования ActiveRecord?
- [ ] Что такое жадная и ленивая загрузки?
- [ ] Может ли жадная загрузка делать больше запросов, чем ленивая?
- [ ] Какие проблемы могут возникнуть при использовании вложенных транзакций в ORM, и как их можно решить?
- [ ] Каковы минусы использования ORM в сравнении с ручным написанием запросов?

## Антипаттерны
- [ ] Основные проблемы плохого кода
- [ ] Какие принципы SOLID нарушает singleton?
- [ ] Чем заменить синглтон?

## Паттерны для работы с legacy-кодом
- [ ] Что такое паттерн "Strangler Fig"? Как его можно применить для рефакторинга legacy-приложений?
- [ ] Как применить паттерн "Adapter" для интеграции современного кода с устаревшими системами?
- [ ] Что такое "Feature Toggle"? Как этот паттерн может помочь в работе с legacy-кодом?

# Архитектура приложений

## Типы архитектур
- [ ] Сравните между собой три вида архитектуры — монолит, микросервисная, модульная. Какие есть недостатки и преимущества у каждой из них?
- [ ] Что такое микросервисы, плюсы-минусы?
- [ ] Какие проблемы видите в распределенных системах?

## Архитектура и проектирование
- [ ] Что такое архитектурный стиль CQRS (Command Query Responsibility Segregation)? В каких случаях его применение оправдано?
- [ ] Как реализовать событийно-ориентированную архитектуру (Event-Driven Architecture) в PHP? Какие библиотеки могут в этом помочь?
- [ ] Что такое паттерн "Спецификация" (Specification Pattern)? Приведите пример его использования в PHP.
- [ ] Как применить принципы Domain-Driven Design (DDD) в PHP-проекте? Какие сложности могут возникнуть?
- [ ] Что такое архитектурный стиль Порты и Адаптеры (Ports and Adapters, или Hexagonal Architecture)? Как его реализовать в PHP?
- [ ] Что такое Clean Architecture? Как ее можно применить в PHP-проекте?
- [ ] Что такое Event Sourcing? Как его можно реализовать в PHP?
- [ ] Расскажите о "чистой архитектуре", "луковичной архитектуре" и "гексагональной архитектуре".
- [ ] В чем разница между многослойной и гексагональной архитектурой? Когда бы вы выбрали одну вместо другой?
- [ ] Какие есть альтернативы событийной модели для отделения сервисов друг от друга?

## Микросервисная архитектура
- [ ] Какие способы взаимодействия микросервисов вы знаете?
- [ ] Какие паттерны микросервисной архитектуры вы можете назвать?
- [ ] Что такое API Gateway?
- [ ] Какие виды паттерна saga есть?
- [ ] Знаете, что такое Circuit Breaker?
- [ ] Что такое идемпотентность?
- [ ] Как бы вы спроектировали коммуникацию между микросервисами на PHP?
- [ ] Какие паттерны отказоустойчивости вы бы применили в микросервисной архитектуре на PHP?
- [ ] Как реализовать распределенное трассирование в микросервисной архитектуре на PHP?

## Принципы проектирования
- [ ] Знаете ли, что такое GRASP?

## Проектирование API
- [ ] Что такое REST API?
- [ ] Использовали ли GraphQL?
- [ ] Знаете, что такое gRPC и Protocol Buffers?
- [ ] Чем документируете API?
- [ ] Как бы вы подошли к интеграции вашего PHP-приложения с внешним API?
- [ ] Какие библиотеки вы предпочитаете использовать для работы с HTTP-запросами в PHP?
- [ ] Как обрабатывать ошибки и исключения при работе с внешними API?

## Очереди и брокеры сообщений
- [ ] Что такое брокеры сообщений/брокеры очередей?
- [ ] Зачем нужны системы очередей? Чем они лучше простого запроса?
- [ ] Сколько воркеров максимально может быть на одной очереди?
- [ ] Какие свойства есть у очереди?
- [ ] Можно ли запустить задачу в очереди не сразу, а через какое-то время?
- [ ] Опишите путь движения задачи в очереди.
- [ ] Какие проблемы могут быть с воркерами?
- [ ] Как можно бороться с утечкой памяти в воркерах?
- [ ] Можно ли отключить режим сна у воркера?
- [ ] В RabbitMQ есть acknowledge, а в Redis что используется для этого механизма?
- [ ] Что такое Symfony Messenger?
- [ ] В чем отличие RabbitMQ от Kafka?
- [ ] Что такое ребаланс в Kafka, зачем он нужен?
- [ ] Какие стратегии ребаланса бывают в Kafka?
- [ ] В чем отличие Zookeeper от Kraft в контексте Kafka?
- [ ] В каких случаях вы бы использовали систему очередей сообщений в PHP-приложении?
- [ ] Сравните различные системы очередей (например, RabbitMQ, Apache Kafka). Какую бы вы выбрали для PHP-приложения и почему?
- [ ] Как обеспечить надежную доставку сообщений в распределенной системе на PHP?

## Кэширование
- [ ] Какие уровни кэширования вы знаете? Как бы вы реализовали многоуровневое кэширование в PHP-приложении?
- [ ] Что такое cache stampede? Как можно предотвратить это явление?
- [ ] Как реализовать версионирование кэша? В каких ситуациях это может быть полезно?
- [ ] Как определить эффективность кэширования?
- [ ] Какие проблемы у кэширования есть?
- [ ] Как решаются проблемы актуальности кэша?
- [ ] Как бы вы подошли к реализации системы кэширования в крупном распределенном PHP-приложении?

## Многослойная архитектура
- [ ] Что такое многослойная архитектура? Какие слои обычно выделяют?
- [ ] Как обеспечить независимость слоев друг от друга?
- [ ] В чем преимущества и недостатки многослойной архитектуры?

## Событийно-ориентированная архитектура
- [ ] Что такое событийно-ориентированная архитектура (Event-Driven Architecture)?
- [ ] Какие паттерны используются в событийно-ориентированной архитектуре?
- [ ] Как реализовать событийную шину (Event Bus) в PHP?
- [ ] Минусы событийной модели?

## Масштабирование приложений
- [ ] Какие стратегии масштабирования PHP-приложений вы знаете?
- [ ] Как реализовать горизонтальное масштабирование PHP-приложения?
- [ ] Какие проблемы могут возникнуть при масштабировании сессий в PHP и как их решать?

# Тестирование

## Виды тестирования
- [ ] Зачем писать тесты?
- [ ] Какие типы тестов вы писали?
- [ ] Какие инструменты для написания юнит тестов вы использовали?
- [ ] Как вы считаете, что сложнее писать: unit-тесты или интеграционные?
- [ ] Влияют ли тесты на архитектуру?
- [ ] Что такое мутационное тестирование? Какие инструменты для этого существуют в PHP?
- [ ] Как реализовать непрерывную интеграцию (CI) и непрерывное развертывание (CD) для PHP-проекта?
- [ ] Как применять принципы TDD (Test-Driven Development) в PHP-разработке? Какие преимущества и недостатки у этого подхода?
- [ ] Как обеспечивать независимость тестов?

## Unit-тестирование
- [ ] Что такое мок-объект?
- [ ] Что такое фикстура?
- [ ] Удобно ли покрывать статические методы unit-тестами?

## Автоматизированное тестирование
- [ ] Какие виды автоматизированных тестов вы обычно пишете для PHP-проектов?
- [ ] Какие инструменты вы используете для измерения покрытия кода тестами в PHP?
- [ ] Как затестить сервис, который обращается в БД?

## Тестирование производительности
- [ ] Какие инструменты вы использовали для нагрузочного тестирования PHP-приложений?
- [ ] Как проводить профилирование производительности во время нагрузочных тестов?
- [ ] Что такое A/B тестирование? Как его можно применить для оптимизации производительности?

## Тестирование безопасности
- [ ] Какие инструменты автоматизированного тестирования безопасности вы знаете?
- [ ] Как проводить тестирование на уязвимости к SQL-инъекциям?
- [ ] Что такое фаззинг (fuzzing)? Как его можно применить для тестирования PHP-приложений?

## Статический анализ кода
- [ ] Что такое статический анализ кода? Какие инструменты статического анализа вы использовали в PHP-проектах?
- [ ] Как интегрировать статический анализ кода в процесс разработки?
- [ ] Какие типичные проблемы может выявить статический анализ в PHP-коде?

# Инструменты разработки

## Системы контроля версий
- [ ] Расскажите о процессе работы с Git (gitflow).
- [ ] Чем в Git отличается merge от rebase?

## Composer
- [ ] Чем отличается composer install от composer update?
- [ ] Для чего нужен Composer?
- [ ] Как работает автолоадинг в PHP?

## Docker
- [ ] Работали ли с Docker? Что это такое?
- [ ] Что такое Docker image?
- [ ] Что значит строка FROM в Dockerfile?
- [ ] Что такое Docker container?
- [ ] Из чего состоит Docker image?
- [ ] Что такое Docker Swarm? Работали ли где\-то с ним?
- [ ] Как исключить папки из образа Docker?

## Анализ кода и документация
- [ ] Какие анализаторы кода использовали?
- [ ] Чем задаются основные стандарты PHP разработки?

## Мониторинг и логирование
- [ ] Что использовали для сбора логов и метрик?
- [ ] Есть ли опыт работы с Telemetry, Grafana, Prometheus?

## DevOps и инфраструктура
- [ ] Был ли опыт в DevOps?
- [ ] Как настроить автоматическое масштабирование PHP-приложения в облачной среде?
- [ ] Что такое инфраструктура как код (Infrastructure as Code)? Как применить этот подход к PHP-проектам?
- [ ] Как организовать логирование и мониторинг в распределенной PHP-системе?
- [ ] Что такое синие/зеленые развертывания (Blue/Green Deployments)? Как их реализовать для PHP-приложения?
- [ ] Как обеспечить отказоустойчивость PHP-приложения? Какие паттерны и практики следует применять?

## Поисковые движки
- [ ] Использовали ли поисковые движки? Какие?

## CI/CD
- [ ] Какие инструменты CI/CD вы использовали в PHP-проектах?
- [ ] Как настроить автоматическое развертывание PHP-приложения?
- [ ] Что такое "Continuous Deployment" и чем оно отличается от "Continuous Delivery"?

## Контейнеризация и оркестрация
- [ ] Какие преимущества дает использование Docker в PHP-разработке?
- [ ] Как организовать многоконтейнерное PHP-приложение с помощью Docker Compose?
- [ ] Что такое Kubernetes? Как его можно использовать для управления PHP-приложениями?

## PHP-FPM и взаимодействие с ним
- [ ] Что такое PHP-FPM и для чего он нужен?
- [ ] Как происходит общение между Nginx и PHP-FPM?
- [ ] Какие ограничения есть у PHP-FPM?
- [ ] Что происходит с FPM, когда запросов слишком много?
- [ ] Какие настройки веб\-сервера (например, Nginx или Apache) важны для оптимальной работы PHP-приложения?
- [ ] Как настроить кэширование на уровне веб\-сервера для PHP-приложения?
- [ ] Какие методы балансировки нагрузки вы знаете и как их можно применить в контексте PHP-приложения?

# Сетевые протоколы
- [ ] Чем отличается TCP от UDP?
- [ ] Для чего нужны таймауты в приложениях?
- [ ] Я ввел google.com в браузер, что происходит в этот момент? (Опишите процесс от ввода URL до отображения страницы)

## HTTP/2 и HTTP/3
- [ ] Какие преимущества дает использование HTTP/2? Как его поддержать в PHP-приложении?
- [ ] Что нового в HTTP/3? Как подготовить PHP-приложение к работе с HTTP/3?
- [ ] Как реализовать Server Push в PHP-приложении с использованием HTTP/2?

## WebSocket
- [ ] В чем преимущества WebSocket перед long polling?
- [ ] Как реализовать WebSocket-сервер на PHP?
- [ ] Какие проблемы могут возникнуть при использовании WebSocket в масштабируемых приложениях?

# Асинхронность и параллелизм

## Многопроцессорность в PHP
- [ ] Чем отличается асинхронное выполнение от параллельного?
- [ ] Как работают корутины (coroutines) в PHP? В чем их преимущества перед обычными функциями?
- [ ] Что такое реактивное программирование? Как его можно применить в PHP?
- [ ] Что такое модель акторов (Actor model)? Есть ли реализации этой модели для PHP?
- [ ] Как работает event loop в асинхронных PHP-фреймворках (например, ReactPHP или Swoole)?
- [ ] Как реализовать многопроцессорную обработку в PHP?
- [ ] В каких сценариях параллельность может быть предпочтительнее асинхронности?
- [ ] Расскажи о семафорах, мьютексах, мониторах, блокировках, дедлоках. Какими средствами они могут быть реализованы в PHP?

## Fiber в PHP 8.1
- [ ] Что такое Fiber в PHP 8.1? Какие проблемы они решают?
- [ ] Как использовать Fiber для реализации асинхронного кода?
- [ ] В чем отличие Fiber от генераторов?

# Практические задачи

## Оптимизация производительности
- [ ] Вы обнаружили, что ваше PHP-приложение работает медленно. Опишите шаги, которые вы предпримете для диагностики и решения проблемы.
- [ ] Как бы вы оптимизировали PHP-приложение, которое обрабатывает большие объемы данных?
- [ ] Опишите архитектуру высоконагруженного PHP-приложения, способного обрабатывать миллионы запросов в день.

## Интеграция систем
- [ ] Вам нужно интегрировать устаревшую PHP-систему с современным микросервисным приложением. Какой подход вы выберете?
- [ ] Как бы вы реализовали систему реального времени на PHP, например, чат или систему уведомлений?
- [ ] Опишите архитектуру системы, которая должна обрабатывать данные из различных источников (API, базы данных, файлы) и агрегировать их.

## Общие задачи
- [ ] У вас есть номер телефона, и вам нужно отправить SMS-код. Приложение интегрировано с разными SMS-провайдерами. Если один провайдер не отвечает, это не должно влиять на другие провайдеры. Опишите архитектуру этого приложения.
- [ ] Что делать в случае отказа одного провайдера? Что делать с таймаутами?
- [ ] Приложение работает с очередью. Оно берет запись из очереди, потом падает, запись возвращается обратно в очередь, потом приложение поднимается, и ситуация повторяется. Что можно сделать?

# Хороший код и практики разработки

## «Хороший код?»
- [ ] Очень часто все говорят, что нужно писать "хороший код", а что такое "хороший код"? Если говорить, что мы работаем над проектом, который регулярно меняется и расширяется, в рамках монолита, и у нас пока нет высоких нагрузок. Команда до 20 backend-разработчиков. Мы говорим разработчикам, что нужно писать "хороший код", а они внезапно забывают, что это такое, но все еще умеют кодить, почти как ChatGPT. Какие подходы и правила им нужно соблюдать, чтобы код был "хорошим"?
- [ ] Как понять, насколько сильно разделять логику в коде на куски?
- [ ] Почему DTO должна быть иммутабельной?
- [ ] К нам приходят коллеги и говорят, что иммутабельные DTO — это круто, но они хотят продолжать получать значения свойств через стрелочки. Какими вариантами это можно достичь, не нарушая иммутабельность?
- [ ] Можно ли покрыть обращение по стрелочкам, но с запретом записи через Psalm? Как бы вы это реализовали?
- [ ] Как вы относитесь к толстым моделям, которые хранят бизнес-логику? Какие плюсы и минусы у этого подхода?
- [ ] На что смотрите, когда делаете код-ревью?

## Рефакторинг
- [ ] Какие признаки указывают на необходимость рефакторинга кода?
- [ ] Опишите процесс рефакторинга большого legacy-приложения. С чего бы вы начали?
- [ ] Какие инструменты вы используете для автоматизации рефакторинга в PHP?

## Архитектурные решения
- [ ] Как бы вы спроектировали систему плагинов для PHP-приложения?
- [ ] Опишите архитектуру системы, которая должна поддерживать несколько версий API одновременно.
- [ ] Как бы вы реализовали систему управления правами доступа в крупном PHP-приложении?

# Инструменты командной строки
- [ ] Как через консоль посмотреть последние 40 строчек в файле?
- [ ] Как посмотреть первые 40 строчек в файле?
- [ ] Какие инструменты вы используете для автоматизации рутинных задач в PHP-разработке?
- [ ] Как написать эффективный скрипт для обработки большого лог-файла?
- [ ] Как бы вы реализовали систему автоматического резервного копирования базы данных с использованием PHP?

# Безопасность

## Шифрование и хеширование
- [ ] Какие современные алгоритмы шифрования вы бы использовали в PHP-приложении? Почему?
- [ ] Что такое Salt и Pepper в контексте хеширования паролей? Зачем они нужны?

## Защита от атак
- [ ] Как защитить PHP-приложение от XSS-атак?
- [ ] Что такое CSRF и как от него защититься в PHP?
- [ ] Как реализовать защиту от брутфорс-атак в PHP-приложении?
- [ ] Как защитить PHP-приложение от SQL-инъекций?
- [ ] Что такое "эскейпинг" и почему он важен в контексте безопасности PHP?
- [ ] Как обеспечить безопасную загрузку файлов в PHP-приложении?

## Безопасность в PHP
- [ ] Что такое OWASP Top 10? Какие из этих уязвимостей наиболее критичны для PHP-приложений?
- [ ] Как реализовать двухфакторную аутентификацию в PHP-приложении?
- [ ] Что такое Content Security Policy (CSP)? Как его настроить для PHP-приложения?
- [ ] Как правильно хранить и проверять пароли в PHP? Какие алгоритмы хеширования следует использовать?
- [ ] Что такое CSRF-токены? Как их реализовать и использовать в PHP?
- [ ] Как правильно реализовать хранение паролей в PHP?
- [ ] Какие современные методы аутентификации вы бы реализовали в PHP-приложении?
- [ ] Как реализовать систему ролей и разрешений в PHP?
- [ ] Что такое JWT (JSON Web Tokens)? Как их использовать в PHP для аутентификации?

## Соответствие стандартам
- [ ] Что вы знаете о GDPR и как обеспечить соответствие PHP-приложения его требованиям?
- [ ] Какие меры безопасности нужно предпринять при работе с платежными данными в PHP-приложении?
- [ ] Как реализовать логирование действий пользователей с учетом требований безопасности и приватности?

# Работа с данными

## Обработка больших объемов данных
- [ ] Как оптимизировать PHP-скрипт для обработки очень большого CSV-файла?
- [ ] Какие подходы вы бы использовали для работы с большими объемами данных, не помещающимися в память?
- [ ] Как реализовать эффективную пакетную обработку данных в PHP?
- [ ] Как работать с большими объемами данных (Big Data) в PHP? Какие инструменты и подходы существуют?

## Работа с различными форматами данных
- [ ] Какие библиотеки вы используете для работы с XML в PHP? Какие у них преимущества и недостатки?
- [ ] Как эффективно работать с JSON в PHP? Какие проблемы могут возникнуть при обработке больших JSON-файлов?
- [ ] Как реализовать экспорт данных в различные форматы (PDF, Excel) в PHP-приложении?

## Другое
- [ ] Как реализовать полнотекстовый поиск в PHP-приложении? Какие инструменты можно использовать?
- [ ] Что такое Change Data Capture (CDC)? Как его можно реализовать с использованием PHP?
- [ ] Как реализовать многоязычность в PHP-приложении? Какие подходы существуют для хранения и управления переводами?

# Современные веб\-технологии

## API-дизайн
- [ ] Какие принципы вы соблюдаете при проектировании REST API?
- [ ] Как работать с GraphQL в PHP? Какие библиотеки существуют для этого?
- [ ] В чем преимущества и недостатки GraphQL по сравнению с REST?
- [ ] Как реализовать версионирование API в PHP-приложении?
- [ ] Как реализовать OAuth 2.0 аутентификацию в PHP-приложении?

## Реал-тайм веб
- [ ] Какие подходы вы знаете для реализации real-time функциональности в PHP-приложениях?
- [ ] Как реализовать push-уведомления в PHP-приложении?
- [ ] Какие проблемы масштабируемости могут возникнуть в real-time PHP-приложениях и как их решать?
- [ ] Как реализовать Server-Sent Events (SSE) в PHP? В каких сценариях это может быть полезно?
- [ ] Что такое WebSockets? Как реализовать поддержку WebSockets в PHP-приложении?
- [ ] Что такое Progressive Web Apps (PWA)? Как PHP может взаимодействовать с PWA?

## Другое
- [ ] Что такое сессионная афинность (Session Affinity)?

# Структуры данных
- [ ] Что такое hashmap, и как в нём разрешаются коллизии?
- [ ] Различия между Linked List и Hash Map
- [ ] Что такое B-tree?