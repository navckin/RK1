## РК1



## Tutorial
1. 

```bash
Можно использовать несколько команд
cd ..
cd и полный путь до файла (те /home/user)
так как у нас самая начальная папка, то можно использовать cd
```
2.

```bash
Определяем в каких файлах не содержиться подстрока:
*grep -v "str" уп-наем путь до файла
```

3.

```bash
созадем каталог mkdir test уже находясь на нужном нам пути. по заднию эта папка создаться в workspace
переходим в папку через команду cd в test
создаем файл через touch test.txt
```

4.

```bash
 создаем архив:
 tar -cf archive.tar.gz путь до файла тест /home/user/workespase/test
```
5.

```bash
Ищем все файлы текующего каталога-->

работает вот эта:
grep -rl "aaa" | grep -l "bbb"

```
6.

```bash
определяем кол-во только каталогов в тек. каталоге:
ls -d --> выдаст все файлы в тек. каталоге,
для поиска каталогов используем:
ls -l | grep -c ^d

```
7.

```bash
Определяем самые большие по размеру каталоги в системе относительно /
(те относительно корня системы)
(те относительно home)
du -a /home | sort -nr | head -n 10
Выдаст 10 самых большых каталогов
```
8.

```bash
Определяем команды  как получить локальный репозиторий гит
git innit 
git pull
git clone (копирует)
```

9.

```bash
Если выполнить перечисленные команды, версия какого файла будет зафиксирована?
Будет сообщение о том, что комитеть нечего, тк нет изменений в рабочем каталоге
```

10.

```bash
Будет такой переход:
patch1 ---> master
```
11.

```bash
Будет такой переход:
patch1 ---> master
```

12.

```bash
Полуиться так, что оба коммита от-тя, оба коммита зафиксируются, но отобразиться коммит того человека, который послденим запушил. 
```
13.

```bash
как выгляд. кофликты слияния?
вот так выглядит: 
«««< HEAD
" строки одного файла"
=======
"строки другого файла"
»»»> branch
```
14.

```bash
какой файл должен присутсвовать в каталоге для сборке смэйк?
CMakeList.txt

```



```
Copyright (c) 2015-2020 The ISC Authors
```
