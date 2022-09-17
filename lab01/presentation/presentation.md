---
## Front matter
lang: ru-RU
title: Шифры простой замены
author: Каримов Зуфар \inst{1}

institute: RUDN University, Moscow, Russian Federation

date: 2022 Moscow, Russia

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# Цель работы

## Цель лабораторной работы

Приобретение навыков программной реализации простых шифров подстановки и замены.

# Задание

## Задания к лабораторной работе  

1. Реализовать шифр Цезарья с произвольным ключом k.

2. Реализовать шифр Атбаш.


# Реализация

## Реализация шифра Цезаря

Функция caesar для шифрования и расшифровки текста. (рис. -@fig:001)

![Функция для кодирования текста шифром Цезаря ](https://github.com/zikarimov/math-security/blob/master/lab01/image/1.png?raw=true){ #fig:001 width=70% }

##  Реализация шифра Атбаша

Функция atbash для шифрования и расшифровки текста. (рис. -@fig:002)

![Функция для кодирования текста шифром Атбаша](https://github.com/zikarimov/math-security/blob/master/lab01/image/2.png?raw=true){ #fig:002 width=70% }

##  Процесс выполнения

Описан блок выбора нужного метода и ввода текста. (рис. -@fig:003)

![Код для выбора метод шифрования и ввода текста](https://github.com/zikarimov/math-security/blob/master/lab01/image/3.png?raw=true){ #fig:003 width=60% }

# Результат

## Результат

![Получение шифрования и расшифровки текста методом Цезаря ](https://github.com/zikarimov/math-security/blob/master/lab01/image/4.png?raw=true){ #fig:004 width=70% }

## Результат

![Получение шифрования и расшифровки текста методом Цезаря ](https://github.com/zikarimov/math-security/blob/master/lab01/image/5.png?raw=true){ #fig:005 width=70% }

## Результат

![Получение шифрования текста методом Атбаша](https://github.com/zikarimov/math-security/blob/master/lab01/image/6.png?raw=true){ #fig:006 width=70% }

# Вывод

Приобрел навыки программной реализации простых шифров подстановки и замены.
