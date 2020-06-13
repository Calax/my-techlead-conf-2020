# Максим Аршинов
# Как запустить MVP и не превратить его в техдолг

## Быстро или качественно?
- Делаем быстро: support hell.
- Делаем долго и дорого: пользователь не готов столько платить

Компромисс: Надо делать быстро и достаточно качественно.

Что такое качество:

![Quality](/resources/ISO_9126_quality.png)

## Быстро и достаточно качественно
| Критерий          | MVP                    | Стадия роста                                 | Требования бизнеса             |
| ----------------- | ---------------------- | -------------------------------------------- | ------------------------------ |
| Сроки             | Вчера          | Сегодня-завтра                       | писать быстро                  |
| Цель              | Тестировать гипотезу   | новая функциональность                       | менять быстро                  |
| Качества продукта | Нравится пользователям | Нравится программистам (удобно сопровождать) | UI\UX и удобство сопровождения |

1. Пишем быстро
    1. Требования
        1. FeatureCut - оставляем только самое основное. Пользуемся техниками:
            1. Impact Mapping
            1. Spec By Example
            1. Event Storming
        1. Предельное упрощение всех требований
    1. Технологии и инструменты
        1. Выбираем знакомые команде технологии.
        1. Отдаем предпочтение тем, у которых более развиты сообщество и инфраструктура.
    1. С лучшей доступной командой
        1. In-house vs outsource. Иногда стартовать через outsource дешевле, т.к. там готовая команда, а свою еще собирать.
1. Менять быстро
    1. Короткий цикл обратной связи (раз в день)
        1. Трассировка по целям (Impact Mapping).
    1. Не боимся выбрасывать
        1. Используем конструктор
        1. Используем фреймворк.
        1. Кодогенератор.
        1. Генератор тестовых данных.
1. Удобство сопровождения.
    1. Организация кода по фичам, а не по слоям.
    1. Feature Toggle.


## Итог
![Summary](/resources/mvp-in-short.png)


## Полезная литература
- Практика:
    - Gojko Adzic - [Specification by Example](https://gojko.net/books/specification-by-example/)
    - Alberto Brandolini - [Event Storming](https://www.eventstorming.com/book/)
    - Gojko Adzic - [Impact Mapping](https://gojko.net/books/impact-mapping/)
- Теория + Практика:
    - Eric Evans - [Domain-Driven Design: Tackling Complexity in the Heart of Software](https://www.goodreads.com/book/show/179133.Domain_Driven_Design)
    - [CQRS Journey](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/jj554200(v=pandp.10))
    - Scott Wlaschin - [Domain Modeling Made Functional: Tackle Software Complexity with Domain-Driven Design and F#](https://www.goodreads.com/book/show/34921689-domain-modeling-made-functional)
- Теория:
    - Robert L. Glass - [Факты и заблуждения профессионального программирования](https://www.goodreads.com/book/show/11489804)
    - Frederick P. Brooks Jr. - [The Mythical Man-Month: Essays on Software Engineering](https://www.goodreads.com/book/show/13629.The_Mythical_Man_Month)
    - Steve McConnell - [Software Estimation: Demystifying the Black Art](https://www.goodreads.com/book/show/93891.Software_Estimation)
- Лютая теория:
    - Георгий Щедровицкий - [Оргуправленческое мышление: идеология, методология, технология](https://www.goodreads.com/book/show/19083659)