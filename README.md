# Разработка пользовательских интерфейсов

## Содержание

1. [Лидерборд](https://docs.google.com/spreadsheets/d/1M-I0suwDAB-sjGJGteHfa0wlMtnl1hFJ/edit?usp=sharing&ouid=114980174016056670914&rtpof=true&sd=true)
1. [Roadmap](#roadmap)
1. [Как выполнять задания](#как-выполнять-задания)
1. [Документация](#документация)
1. [Полезное](#полезное)

## Roadmap

Все, что находится выше `Мы здесь` должно быть у вас для успешного прохождения дисциплины

### 1. Git

[Презентация по Git](https://ktkv-presentations.github.io/algos-8/)

### 2. Основы HTML верстки

- [HTMLAcademy (все 5 модулей)](https://htmlacademy.ru/courses/299)

- [Лабораторная работа №1](https://github.com/21isr/uidev-lab1)

- [HTML Academy Recap (только модуль с HTML](https://htmlacademy.ru/courses/297)

- [Лабораторная работа №2](https://github.com/21isr/uidev-lab2)

- [CSS Diner (CSS селекторы)](https://flukeout.github.io/)

- [Лабораторная работа №3](https://github.com/21isr/uidev-lab3)

### 3. Основы CSS

#### Flexbox

- [Flexbox Froggy](https://flexboxfroggy.com)

- [Лабораторная работа №4](https://github.com/21isr/uidev-lab4)

#### Grid

- [Grid Garden](https://cssgridgarden.com/#ru)

- [Лабораторная работа №5](https://github.com/21isr/uidev-lab5)

- [Лабораторная работа №6](https://github.com/21isr/uidev-lab6)

- [Лабораторная работа №7](https://github.com/21isr/uidev-lab7)

- [Лабораторная работа №8](https://github.com/21isr/uidev-lab8)

- [Лабораторная работа №9](https://github.com/21isr/uidev-lab9)

- [Лабораторная работа №10](https://github.com/21isr/uidev-lab10)

- [Лабораторная работа №11](https://github.com/21isr/uidev-lab11)

- [Лабораторная работа №12](https://github.com/21isr/uidev-lab12)

#### Адаптивность

⬇ Мы здесь

- [Лабораторная работа №13](https://github.com/21isr/uidev-lab13)

- [Лабораторная работа №14](https://github.com/21isr/uidev-lab14)

#### JavaScript

...

#### Astro

...

## Как выполнять задания

В каждом репозитории описано как выполнять задание. В случае, если не указано, то работать по следующему принципу:

### Как начать выполнять

1. Создайте fork репозитория в организации [21ISR](https://github.com/21ISR) под названием `uidev-lab{N}-{фамилия}`
    - `N` - номер лабораторной работы

2. Переключитель на ветку `dev` (левый-верхний угол)

3. Запустите Codespace (Code => Codespace)

_Либо запускайте сразу на нужной ветке, либо переключайтесь в терминале кодспейса_

### Как сохранять работу

Для отправки ветки `dev` на репозиторий GitHub необходимо:

- Добавить все измененные файлы в следующий коммит `git add .`

_Обратите внимание, что `.` это текущая папка. Соответственно, если вы находитесь в какой-либо папке внутри репозитория, то будут добавлены изменения только из папки_

- Создайте коммит `git commit -m "{Что делали}"`

_В кавычках постарайтесь описать что вы делали в текущем коммите, особенно если работа у вас заняла больше 1 коммита_

- Отправить коммит на GitHub `git push -u origin dev`

_Обратите внимание на последнее слово - это название вашей ветки_

### Как сдавать

При успешном выполнении задания:

- Делайте коммит
- Захостите работу с помощью [Github Pages](#как-хостить-работу)
- Добавляйте [pull request](#как-делать-pull-request) из `dev` в `main` в **вашем репозитории**
- Указывайте меня ([ktkv419](https://github.com/ktkv419)) как reviewer

При успешной сдаче задания pull request будет закрыт и последним сообщением перед закрытием реквеста будут написаны мои комментарии и оценка

### Как делать pull request

_Обратите внимание, что это делается в **вашем** репозитории, где вы работали_

1. Откройте вкладку Pull requests

<p align="center">
    <img src="./.repo/images/pr-1.png" width="80%" />
</p>

2. Создайте новый PR

<p align="center">
    <img src="./.repo/images/pr-2.png" width="80%" />
</p>

3. Перепроверье, что изменения сливаются из ветки `dev` (справа) в ветку `main` (слева) и создайте новый PR

<p align="center">
    <img src="./.repo/images/pr-3.png" width="80%" />
    <img src="./.repo/images/pr-4.png" width="80%" />
</p>

В случае успешной сдачи работы вы увидите мои комментарии по поводу работы, оценку и что реквест был слит с веткой main

### Как хостить работу

_Обратите внимание, что это делается в **вашем** репозитории, где вы работали_

1. Откройте настройки проекта и вкладку `Pages`

<p align="center">
    <img src="./.repo/images/host-1.png" width="80%" />
</p>

<p align="center">
    <img src="./.repo/images/host-2.png" width="80%" />
</p>

2. Укажите ветку в которой вы выполняли работу и нажмите сохранить

_чаще всего это либо `dev`, либо `wip`_

<p align="center">
    <img src="./.repo/images/host-3.png" width="80%" />
</p>

3. Удостоверьтесь, что работа была захосчена успешно

_об этом будет сигнализировать галочки у последнего коммита и в категории `Deployments`, также удостоверьтесь, что работа доступна по ссылке внутри деплоя `github-pages`_

<p align="center">
    <img src="./.repo/images/host-4.png" width="80%" />
</p>

<p align="center">
    <img src="./.repo/images/host-5.png" width="80%" />
</p>

## Установка ПО

???

## Документация

## Полезное

- [MDN](https://developer.mozilla.org/ru/docs/Web/)
- [Git шпаргалка](https://github.com/cyberspacedk/Git-commands)
