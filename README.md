# Печенье и плиты: модель пекарни

## Введение
*I ❤️ Cookies* - это пекарня, специализирующаяся на приготовлении вкусного печенья. Пекарня быстро растет и ей становится сложно удовлетворять спрос. Некоторые программы управления пекарней должны помогать достигать поставленных целей. Ваша задача - создать программу, которая поможет управлять пекарней.

Вот несколько пожеланий пользователей, которые помогут вам начать:

- Как пекарь, я хочу делать разные типы печенья (с арахисовым маслом, шоколадной крошкой и т. д.).
- Как пекарь, я хочу помещать партии печенья в духовку.
- Как пекарь, я хочу знать, когда партия печенья будет готова, чтобы достать её из духовки.

### Объектно-ориентированный подход. Проектирование
Цель этой задачи - переложить объекты, классы реального мира на объекты, классы вашей программы. Вот некоторые рекомендации, которым вы должны следовать.

* Создавайте четко определенные классы, которые отвечают за что-то одно.
* Внедряйте чистую и гибкую логику взаимодействия между объектами.


## Releases
### Pre-release: Понимание проблемы
Прежде чем вы начнете писать код, вам нужно подумать об этой проблеме критически. Затем опишите на простом русском языке как разработать эту программу. Рассмотрите следующие вопросы.

- Каковы основные классы?
- Какие атрибуты будет иметь каждый класс?
- Какой функционал будет предоставлять каждый класс?
- Как классы будут взаимодействовать друг с другом?
- Имеет ли смысл наследование? Композиция? Вы знаете что такое композиция?


### Release 0: Внедрение минимально жизнеспособного продукта
С некоторым представлением о том, какие компоненты составляют вашу программу, начните писать код. Постройте *минимальный жизнеспособный продукт* (MVP) – никаких нестандартных функций, только самые необходимые.

Основываясь на рассказах пользователя во *Введении*, вы должны иметь возможность готовить печенье, вы должны иметь возможность помещать печенье в печь и вытаскивать из нее. Если печенье находится в духовке, то вы должны испечь его и проверить статус его готовности.

У вас есть отличная возможность написать несколько тестов, описывающих работу ваших классов!


### Release 1: Дополнительные функции
Отлично! Вы написали MVP. Теперь пора расширить программу, добавив некоторые новые функции и, как всегда, протестировать их. Вы должны обязательно выполнить следующее:

- Сделать несколько типов печенья, каждый из которых отличается временем выпечки.
- Печенье имеет четыре возможных статуса в зависимости от того, как долго они пеклись: `doughy`,`almostReady`, `ready` и `burned`.

### Release 2: Рефакторинг
[Рефакторинг](https://bit.ly/2yVrgoV) является важной частью разработки. Сделайте шаг назад и посмотрите на код, который вы создали. Убедитесь, что он вам нравится и не хочется ничего оптимизировать. Хорошо ли вы понимаете ООП? Обратите внимание на следующие аспекты:

- Используете ли вы большее количество свойств и функций для объекта, чем это необходимо?
- Повторяете ли вы несколько раз одну и ту же логику в коде? Повторять не нужно.
- Являются ли ваши классы ортогональными? ([Ортогональный][Ортогональный])


### Release 3: Будьте креативны!
Поставьте себя на место пекаря и подумайте какие ещё функции могут вам пригодиться. Выберите наиболее полезную и выполнимую функцию и добавьте ее в вашу программу.

[Ортогональный]: http://stackoverflow.com/a/1527430
