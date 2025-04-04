# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #4 выполнил(а):
- Таланкин Игорь Львович
- РИ230946

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | # | 20 |
| Задание 3 | # | 20 |


Работу проверили:


## Цель работы
Изучить алгоритм обучения Перцептрона, посмотреть на своих примерах.

## Задание 1
### Задачи:
в проекте Unity реализовать перцептрон, который умеет производить вычисления:
OR | дать комментарии о корректности работы
AND | дать комментарии о корректности работы
NAND | дать комментарии о корректности работы
XOR | дать комментарии о корректности работы

Ход работы:
- Подкрепив скрипт к путому объекту и указав входные данные через юнити напрямую, вручную, мы смогли просимулировать OR, AND, NAND. Однако прецептрон не смог научиться XOR, сколько бы эпох мы не устанавливали. XOR выдаёт 4 из 4 ошибок каждую эпоху и не может научится применять эту логическую функцию.
- Предпологаемые выводы(всё кроме XOR совпало):
- OR:   00 0 | 01 1 | 10 1 | 11 1 |     [Скриншот](https://github.com/TalankinIgor/AiGamedev/blob/main/Zadanie4_1_OR.png)
- AND:  00 0 | 01 0 | 10 0 | 11 1 |     [Скриншот](https://github.com/TalankinIgor/AiGamedev/blob/main/Zadanie4_2_AND.png)
- NAND: 00 1 | 01 1 | 10 1 | 11 0 |     [Скриншот](https://github.com/TalankinIgor/AiGamedev/blob/main/Zadanie4_3_NAND.png)
- XOR:  00 0 | 01 1 | 10 1 | 11 0 |     [Скриншот](https://github.com/TalankinIgor/AiGamedev/blob/main/Zadanie4_4XOR_ERROR.png)
- Можно посмотреть выводы всех OR, AND и NAND в соответствующих файлах.


## Вывод: Мы проверили работоспособность прецептрона на примере простых логических операций и увидели его работоспособность, зависимость от количества эпох и реальную способность обучению.



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
