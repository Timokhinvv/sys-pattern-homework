# Домашнее задание к занятию "`Git`" - `Тимохин Вячеслав`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

`Приведите ответ в свободной форме........`


1. `git clone https://github.com/Timokhinvv/sys-pattern-homework.git`
2. `git config --global user.name "Vyacheslav"`
3. `git config --global user.email summo@yandex.ru`
 

```
Поле для вставки кода...

git status
Текущая ветка: main
Эта ветка соответствует «origin/main».

Изменения, которые не в индексе для коммита:
  (используйте «git add <файл>...», чтобы добавить файл в индекс)
  (используйте «git restore <файл>...», чтобы отменить изменения в рабочем каталоге)
	изменено:      README.md

индекс пуст (используйте «git add» и/или «git commit -a»
....
....
tvv@tvv-VirtualBox:~/projects/sys-pattern-homework$ git push origin main
Перечисление объектов: 11, готово.
Подсчет объектов: 100% (11/11), готово.
Сжатие объектов: 100% (8/8), готово.
Запись объектов: 100% (8/8), 591.54 КиБ | 2.11 МиБ/с, готово.
Всего 8 (изменений 1), повторно использовано 0 (изменений 0), повторно использовано пакетов 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Timokhinvv/sys-pattern-homework.git
   7e21e2d..2cb64a0  main -> main....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота 1](ссылка на скриншот 1)`


[SC1] (https://github.com/Timokhinvv/img/SC1)
[SC2] (https://github.com/Timokhinvv/img/SC2)
[SC3] (https://github.com/Timokhinvv/img/SC3)
[SC4] (https://github.com/Timokhinvv/img/SC4)
[SC5] (https://github.com/Timokhinvv/img/SC5)

---
Ссылка:
https://github.com/Timokhinvv/sys-pattern-homework/commit/2cb64a00eb388c5fd066f2e2515c7fb754c55bbd


### Задание 2

`Приведите ответ в свободной форме........`

1. `nano .gitignore`
3. `git add .`
2. `git status`
3. `git commit -m "Two commit"`



```
Поле для вставки кода...
....
tvv@tvv-VirtualBox:~/projects/sys-pattern-homework$ nano .gitignore
tvv@tvv-VirtualBox:~/projects/sys-pattern-homework$ git status
Текущая ветка: main
Эта ветка соответствует «origin/main».

Изменения, которые не в индексе для коммита:
  (используйте «git add <файл>...», чтобы добавить файл в индекс)
  (используйте «git restore <файл>...», чтобы отменить изменения в рабочем каталоге)
        изменено:      README.md

Неотслеживаемые файлы:
  (используйте «git add <файл>...», чтобы добавить в то, что будет включено в коммит)
        .gitignore
        img/SC5.png

индекс пуст (используйте «git add» и/или «git commit -a»)
....
Изменения, которые не в индексе для коммита:
  (используйте «git add <файл>...», чтобы добавить файл в индекс)
  (используйте «git restore <файл>...», чтобы отменить изменения в рабочем каталоге)
        изменено:      .gitignore

Неотслеживаемые файлы:
  (используйте «git add <файл>...», чтобы добавить в то, что будет включено в коммит)
        img/SC6.png
        img/SC7.png

tvv@tvv-VirtualBox:~/projects/sys-pattern-homework$ git add .
tvv@tvv-VirtualBox:~/projects/sys-pattern-homework$ git status
Текущая ветка: main
Эта ветка соответствует «origin/main».

Изменения, которые будут включены в коммит:
  (используйте «git restore --staged <файл>...», чтобы убрать из индекса)
        новый файл:    .gitignore
        изменено:      README.md
        новый файл:    img/SC5.png
        новый файл:    img/SC6.png
        новый файл:    img/SC7.png

tvv@tvv-VirtualBox:~/projects/sys-pattern-homework$

```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота 2](ссылка на скриншот 2)`

[SC6] (https://github.com/Timokhinvv/img/SC6)
[SC7] (https://github.com/Timokhinvv/img/SC7)
[SC8] (https://github.com/Timokhinvv/img/SC8)
[SC9] (https://github.com/Timokhinvv/img/SC9)

---
Ссылка:
https://github.com/Timokhinvv/sys-pattern-homework/commit/23702775d50fcfd4a18fed77c5eeb37ed1c92d16

### Задание 3

`Приведите ответ в свободной форме........`

1. (https://github.com/Timokhinvv/sys-pattern-homework/network)`

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`

[SC10] (https://github.com/Timokhinvv/img/SC10)
[SC11] (https://github.com/Timokhinvv/img/SC11)
[SC12] (https://github.com/Timokhinvv/img/SC12)
[SC13] (https://github.com/Timokhinvv/img/SC13)
[SC14] (https://github.com/Timokhinvv/img/SC14)

