## JBook
Сейчас это разрозненные заметки, мысли, конспекты о `Java`.

В дальнейшем планируется перевести это в небольшой курс - бесплатный для всех, кто хочет учиться.
Сейчас же это все просто разрозненные статьи.

Любой feedback приветствуется!

### Почему это пишется?
> Изучил что-то — пробуй это объяснить, пока не поймёшь сам.

### Как отблагодарить?

Если вы нашли материал этого проекта полезным или он вам помог - поставьте, пожалуйста, звездочку - это придает мотивации продолжать развивать проект и служит маячком того, что я не зря делаю это.

### Путеводитель
> Путеводитель, как и проект, в стадии разработки и может быть **изменен**.
>
> Не все статьи внесены в путеводитель.

* [Начинающим](start)

  Советы для тех, кто только начинает изучать `Java`.
  1. [Когда надо и когда не надо использовать `static`](start/static_java.md)

* Общие правила

  Общие правила, советы по тому, что в `Java` делать можно, а чего не стоит.
    1. Оформление кода
      * [Как надо и как не надо писать код](start/code_style.md)
      * [Как оформить класс для хранения константных значений](start/classes_for_static.md)
    2. [Общие советы](start/advices.md)


* [Объектно-ориентированное программирование - ООП](oop)

  Заметки про `ООП`, зачем нужно, что включает в себя и как это использовать.
  1. [Введение](oop/intro.md)
  2. [Инкапсуляция](oop/encapsulation.md)
  3. [Наследование](oop/inheritance.md)
  4. [Полиморфизм](oop/polymorphism.md)
  5. [Абстракция](oop/abstraction.md)
  6. [SOLID](oop/SOLID.md)


* [Object в Java](object)

  `java.lang.Object` - корень иерархии классов в `Java`. Все о главном классе в `Java` и его методах.
  1. [Введение](object/intro.md)
  2. [ToString](object/toString.md)
  3. [Equals](object/equals.md)
  4. [Hashcode](object/hashcode.md)
  5. [Clone](object/clone.md)
  6. [Finalize](object/finalize.md)
  7. [getClass](object/getClass.md)


* [Исключения в Java](exceptions)

  Обработка исключительных ситуаций.
    1. [Исключения в Java](exceptions/exceptions.md)


* [Коллекции в Java](collections)

    Все про коллекции в `Java`. `Generics`.
    1. [Введение](collections/intro.md)
    2. [List](collections/list/List.md)
      * [ArrayList](collections/list/ArrayList.md)
      * [LinkedList](collections/list/LinkedList.md)
    3. Общие советы.
      * [Что делать, когда вам нужна пустая коллекция](collections/EmptyCollections.md)

* [Сериализация](serialization)

  Сериализация в `Java`. Виды, использование, примеры.

* [Системы сборки проекта](build)

  Системы сборки проекта в мире `Java`, структура и использование.


* [Надо знать или иметь представление](common)
  1. [Ссылки в Java](common/references.md)
  2. [Overloading и Overriding](common/over-load-ride.md) - // todo ПЕРЕПИСАТЬ

* [Паттерны](patterns)

  Паттерны в `Java` и их использование.

* [Дата и время в Java](other/date)
  1. [Введение](other/date/intro.md)
  2. [java.util.Date и java.util.Calendar](./date_and_calendar.md)

    Старое `Time Api`. Входит в состав `JDK`. Из-за большого количества недочетов рекомендуется использовать либо новое `Time Api`, либо сторонние реализации, например, `joda-time`.
  3. [Java 8 DateTime API](./TimeAPI.md)

    Новое `Time Api`. Входит в в состав `JDK`. Рекомендуется для использования.
  4. [joda-time](./joda-time.md)

    Одна из самых распространенных сторонних библиотек в `Java` для работы с временем.

* [Структура проекта на Java](build)
  1. [Работа с ресурсами приложения](build/resources.md)


* [Алгоритмы и Структуры данных](algorithms)

    Все что касается алгоритмов и их реализации на `Java`, с подробным описанием.
  1. [Алгоритмы поиска](algorithms/search)
    * [Бинарный поиск](algorithms/search/binary.md)
  2. [Алгоритмы сортировки](algorithms/sorting)
    * [Сортировка пузырьком](algorithms/sorting/bubble.md)
