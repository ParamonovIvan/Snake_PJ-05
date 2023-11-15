# Проект «Мини-игра Змейка на JS» ![Snake mini](https://github.com/ParamonovIvan/Snake_PJ-05/assets/131868856/96135ac2-1868-495f-9bc8-80f32a526239)

### Задачи проекта:

+ Повторить и закрепить тему взаимодействия с DOM.

+ Потренироваться в написании кода на основе ES6 классов с использованием принципов ООП.

+ Попрактиковаться в использовании localStorage для сохранения прогресса игры.<br><br>

### Требования к интерфейсу:

+ На экране должно быть игровое поле размером 10 на 10 клеточек.

+ Над игровым полем должно быть окно, в котором показывается текущее количество очков игрока. На момент начала игры количество очков равно 0.

+ Под окном с количеством очков указан лучший результат (рекорд) данного пользователя. Если пользователь играет в игру в первый раз, лучший результат отображать не нужно.

+ После завершения игры появляется кнопка, которая позволяет перезапустить игру.

+ Дизайн игровых элементов любой: это может быть как минималистичная змейка в стиле ретро-игр, так и что-то более необычное.

### Функциональные требования:

+ Необходимо использовать классический JavaScript, без дополнительных библиотек.

+ Каждой клетке на поле должны быть присвоены две координаты: x (по горизонтали) и y (по вертикали). С помощью координат будет легко найти нужную клетку и внести необходимые изменения в коде.

+ Отображение змейки и яблока осуществляется за счёт назначения нужным клеткам определённых классов, меняющих внешний вид клеток: например, класс snake окрашивает клетку в зелёный цвет, а класс apple добавляет внутрь клетки красный круг.

+ Движение змейки осуществляется за счёт удаления/добавления соответствующих классов определённым клеткам.

+ Скорость движения змейки — одна клетка в 0.5 секунды или две клетки в секунду.

+ Если змейка наталкивается на «стену» (край поля), она проходит сквозь неё и выходит с другой стороны поля.

+ Яблоко появляется в случайном месте поля. Использовать генератор случайных чисел для определения его координат (но яблоко может появиться только на не занятой змейкой клетке).

+ Лучший результат (рекорд) должен храниться в localStorage. После завершения игры необходимо проверть, не побил ли игрок свой предыдущий рекорд, и, если это так, обновить значение в localStorage. При следующем запуске игры рекорд должен красоваться под полем с количеством заработанных очков.

+ Чтобы задать поведение основным объектам игры (поле, змейка, яблоко), использовать ES6 классы.

+ Внутри классов реализовать принцип инкапсуляции. Свойства и методы должны разделяться:
+ 
  &nbsp;&nbsp;&nbsp;  на внешние — те, что могут быть использованы извне,
  
  &nbsp;&nbsp;&nbsp;  и внутренние — те, что должны быть доступны только внутри класса.

+ Внутренние свойства нужно защитить от изменений извне.

### Правила игры:

+ В начале игры змейка располагается в середине поля. Её изначальная длина — две клетки.

+ Игра начинается при клике на любое место поля. В случайном месте поля появляется яблоко, и змейка начинает двигаться. Стрелками на клавиатуре можно двигать змейку в нужном направлении.

+ После того как голова змейки попадает на клетку с яблоком, яблоко считается съеденным: игрок получает одно очко, яблоко исчезает с данной клетки и появляется в другом месте, а размер змейки увеличивается на одну клетку.

+ Если голова змейки упирается в её собственное тело, игра заканчивается. Если игрок побил свой рекорд по очкам, значение рекорда перезаписывается. Также появляется кнопка, которая позволяет начать игру заново.

### Прочие требования:

+ Писать код аккуратно, с соблюдением форматирования и отступов.

+ Стараться давать классам, переменным и функциям осмысленные имена.

+ При написании кода стараться следовать принципам KISS (Keep It Short and Simple — не усложняй) и DRY (Don’t Repeat Yourself — не повторяйся).

### Дополнительное задание:

+ Запретить змейке проходить сквозь края поля. Если змейка «врезается в стену», игра заканчивается.

+ Немного увеличивайть скорость движения змейки с каждым набранным очком.

### Результат работы:

#### Ссылка на страницу с игрой:

+ https://paramonovivan.github.io/Snake_PJ-05/

#### Внешний вид страницы с игрой

![Snake1](https://github.com/ParamonovIvan/Snake_PJ-05/assets/131868856/610b9d90-9cd1-4fe9-9bb5-c4ab92ded159)


![Snake2](https://github.com/ParamonovIvan/Snake_PJ-05/assets/131868856/f39761c0-8e39-43bf-aaf6-efcd5e2a5ef3)


![Snake3](https://github.com/ParamonovIvan/Snake_PJ-05/assets/131868856/5cec66d6-6dff-4d7e-9611-bd8aca0c1b75)
