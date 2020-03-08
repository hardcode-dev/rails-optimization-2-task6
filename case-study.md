# Case-study задания

## Задание

Необходимо уменьшить объем загружаемого `JS-а`. Необходимо сократить объем, так что бы он укладывался в заданный бюджет: `460000` байт.

## Выполнение

### Подготовка к выполнению

Для начала я добавил файл с указанием бюджета(`budget.json`) и проверил что на данный момент сборка не укладывается в заданный бюджет.

Моя сборка на `development` укружении заняла `1 MB`.

### Выполнение задания

Для начала я установил `webpack-bundle-analyzer` плагин для визуализации потребляемого объема пространства различными библиотеками.

Полученный [результат](http://joxi.ru/v29GXj8Tz9oKvr)

Как видно по результатам теория о том, что `moment.js` грузится полностью, что влечет за собой большой обхем подтвердилась.