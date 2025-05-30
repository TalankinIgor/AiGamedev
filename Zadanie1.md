# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Таланкин Игорь Львович
- РИ230946

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

Работу проверили:



- Данные о работе: Работа #1. Установка программного обеспечения, Таланкин Игорь Львович, АТ-01. Выполненные задания: 1, 2, 3.

## Цель работы
Установить необходимое программное обеспечение, которое пригодится для создания интеллектуальных моделей на Python. Рассмотреть процесс установки игрового движка Unity для разработки игр.

## Задание 1
### Написать программу Hello World на Python с запуском в Jupiter Notebook.

Ход работы:
- После установки и настройки Jpnotebook, в всплывшем окне браузера, создаю новый файл Helloworld.ipynb и прописываю скрипт:

```py

print("Hello World!");

```
- При выполнении задания возникла проблема с "не появляющейся кнопкой Run" для программы, но её удалось решить, проблема была в неправельном расширении создоваемого файла.
- [Скриншот](https://github.com/TalankinIgor/AiGamedev/blob/main/Zadanie1_1.png)

## Задание 2
### Написать программу Hello World на C# с запуском на Unity. 

- После установки и настройки Unity и Unity Hub, создаём новый проект, создаём скрипт и подкрепляем к, например, камере. Код:

```сs

using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class NewBehaviourScript : MonoBehaviour
{
    // При старте вызывается функция 1 раз
    void Start()  
    {
        print("hello world");
    }

}

```

- После применяем файл к объекту и запускаем проект, видим что консоль выводит: hello world
- [Скриншот](https://github.com/TalankinIgor/AiGamedev/blob/main/Zadanie1_2.png)

## Задание 3
### Оформить отчет в виде документации на github (markdown-разметка).

- Сам этот отчёт и является рещением этого задания, выполняем в соответствии с примером.


## Выводы: Мы установили необходимое програмное обеспечение и убедились в его работе, проверив на простом скрипте. Теперь мы можем работать дальше.

Абзац умных слов о том, что было сделано и что было узнано.

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
