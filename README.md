# Rubizza Survival Camp: Summer 2018

![](https://s3.eu-central-1.amazonaws.com/rubizza/rubizza-logo.png)


# [Как сдавать задания](#how-to-submit)

Алгоритм примерно следующий:

* Для сдачи всех заданий каждому нужно будет [форкнуть](http://lmgtfy.com/?q=%D1%84%D0%BE%D1%80%D0%BA%D0%BD%D1%83%D1%82%D1%8C) этот репозиторий.
* Каждый курсант ( он же участник курсов ) должен в этом репозитории создать папку со своим личным номером ( например __2522__ ).
* Каждое задание должно выполняться в отдельной [ветке](http://lmgtfy.com/?q=github+fork) и для него необходимо создать отдельную папку, которая будет отражать номер задания. ( например для задания 0 - __2522/0/__ )
* После завершения задания - нужно выслать [pull request](http://lmgtfy.com/?q=pull+request) ( он же далее PR ) в master-ветку этого репозитория. Формат названия PR должен быть __персональный номер__ - __номер задания__ ( например 2522 - 0 ). Обратите внимание что при отправки нужно заполнить все поля в шаблоне.
* PR после отправки всегда будет проверять шальная собака на соответствие человеческим стилям. Если стиль кода ей не понравится - она будет ругаться.
* Только если собака довольна - на вашу задачу будет назначен ментор, который уже будет просматривать код и принимать задание.
* После того как ментор решил что задание выполнено полностью и ему все нравится - он зальет ваше задание в основной репозиторий. Именно этот момент и будет считаться временем сдачи задания.


# Задание 0

В рамках первого задания всем нужно было настроить окружение ( *nix, rvm/rbenv, ruby ) и поднять на своей локальной машине redmine. Так как к моменту написания этого задания большая часть бойцов уже с ним справилась, то более подробно описывать его не имеет смысла. Напомню только что самые дерзкие ( мы всех взяли на карандаш ) обещали также обернуть redmine в docker, за что получат дополнительную звездочку.

P.S. Мы проверили, звездочки на складе закончились, будем выдавать банки тушенки.


### Как доказать что я справился

Для того, чтобы сдать данное задание необходимо:

* По алгоритму [выше](#how-to-submit) нужно пройти все шаги и сделать настройку.
* В нужной папке и ветке нужно создать файлик `1.rb` с кодом в нем `puts 'Chunky bacon'` ( лайк и подписка если понял о чем я )
* Этот файлик нужно прикрепить и отправить по той же инструкции выше.
* В видео, которое необходимо припкрепить к PR ( он же pull request ) нужно отразить что у тебя есть на машине ruby, rvm/rbenv, и работает локально redmine.
* Если делал задачу со звездочкой - то в папку помимо 1.rb нужно положить все, что касается настройки докеров. И также это отразить на видео.

### Дедлайн

2018-07-07 18:00:00 UTC+3

# Задание 1

После первого задания вы получили работающую систему, и настало время ей воспользоваться! Чтобы показать все прелести языка Ruby вам придется пройти через сложный путь к просветлению. На выходе вы получите незабываемые впечатление и навыки написания кода согласно тому, как все привыкли его видеть! Запомните, что каждое следующее задание должно строго следовать букве закона и быть на стиле!

0. Форкаем [репозиторий](https://github.com/edgecase/ruby_koans).
1. Фиксим все коэны. (см. инструкцию к репу ruby_koans)
2. ...
4. Profit!

### Как доказать, что я справился

* Все решения ( вместе с кодом решения ) должны быть залиты в папку, которая отражает номер текущего задания.
* Видео, прикрепленное к PR, обязательно должно показывать, что все koans пройдены.

### Дедлайн
2018-07-11 18:00:00 UTC+3
