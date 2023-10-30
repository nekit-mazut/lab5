# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Дюпин Никита Александрович
- РИ220936
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 0.
- Визуализация проделанной работы.
- Задание 1.
- Найдите внутри C# скрипта “коэффициент корреляции ” и сделать выводы о том, как он влияет на обучение модели.
- Задание 2.
- Изменить параметры файла yaml-агента и определить какие параметры и как влияют на обучение модели. Привести описание не менее трех параметров.
- Задание 3.
- Приведите примеры, для каких игровых задачи и ситуаций могут использоваться примеры 1 и 2 с ML-Agent’ом. В каких случаях проще использовать ML-агент, а не писать программную реализацию решения?
- Выводы.
- ✨Magic ✨

## Цель работы
Ознакомиться с основными операторами зыка Python на примере реализации линейной регрессии.
## Задание 0. Визуализация.

https://github.com/nekit-mazut/lab5/assets/145917921/ad474c6b-55c6-4c0a-bf0c-392202dd40f5

Архив с видео из Симулятора добычи ресурсов.
[economic.zip](https://github.com/nekit-mazut/lab5/files/13198586/economic.zip)

![image](https://github.com/nekit-mazut/lab5/assets/145917921/e1b9e95d-b068-4626-b48c-188a6faf1873)

## Задание 1
### Найдите внутри C# скрипта “коэффициент корреляции ” и сделать выводы о том, как он влияет на обучение модели.

![image](https://github.com/nekit-mazut/lab5/assets/145917921/d9d6aea2-18ef-409c-b4ab-607be412199f)

Коэффициент корреляции влияет на точность совпадения эталонных значений, которых мы хотим добится по итогу обучения, и действительных значений которые мы получаем по итогу обучения, в данном случае чем больше значение коэфа 1.42, тем менее точно агенты будут придерживаться эталонному результату, награды для агентов будут больше, чем меньше значение коэфа, тем более точно будут работать агенты, тем меньше они будут получать награду за свои действия.


## Задание 2
### Изменить параметры файла yaml-агента и определить какие параметры и как влияют на обучение модели. Привести описание не менее трех параметров.

trainer_type: ppo
Тип обучения, в данном случае с поощрением.
max_steps
Максимальное количество ходов(steps).
time_horizon
Максимальное, выделенное для работы, время

## Задание 3
### Приведите примеры, для каких игровых задачи и ситуаций могут использоваться примеры 1 и 2 с ML-Agent’ом. В каких случаях проще использовать ML-агент, а не писать программную реализацию решения?

1ый пример, Поиск агентом объекта на сцене, можно использовать для поиска выхода из случайно сгенерированного лабиринта, к примеру в игре, где игроку нужно выбраться из лабиринта, на некоторое время будет появляться некоторое существо которое будет двигаться в сторону выхода из лабиринта, подобная механика реализована в игре terraria, где игрок может случайно найти фею, которая покажет где сундук с сокровищами.

2ой пример, Симулятор добычи ресурсов, как метод некоторого бота, можно использовать почти в любой онлайн rpg, для создания видимости большого онлайна в игре.

ML агентов проще использовать тогда, когда необходимо реализовывать методы реалистично, обычный программный код будет работать как машина, в играх такое поведение выглядит странно, а вот ML агенты способны обучаться и выглядить естественно, даже принимать сложные решения.

## Выводы

По итогу данной работы я научился работать с ML агентами и визуализировать данные полученные во время их обучения.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
