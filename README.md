# Создаём туториал по Git

## Добавление репозитория в проект

**Чтобы добавить версионность в проект, необходимо установить Git на компютер и прописать следующую команду инициализации в терминале:**
```
git init
```

## Как проверить состояние проекта

**Чтобы проверить состояние проекта, необходимо ввести в терминал следующую команду:**
```fix
git status
```

## Как добавить содержимое в рабочий каталог
**Чтобы добавить содержимое в рабочий каталог, необходимо ввести в терминал следющую команду:**
```
git add
```
## Как сохранить или зафиксировать информацию
**Чтобы сохранить или зафиксировать информацию, необходимо ввести в терминал следующую команду:**
```
git commit
```
## Как проверить изменения в журнале
**Чтобы проверить изменения в журнале, необходимо использовать следующую команду:**
```
git log
```
## Как переключиться между версиями
**Чтобы переключиться между версиями, необходимо использовать следующую команду:**
```fix
git checkout
```
## Как уточнить разницу между текущим файлом и сохранённым
**Чтобы определить разницу между текущим файлом и сохранённым, необходимо выполнить следующую команду:**
```
git diff
```
# Синтаксис языка Markdown. 
**Жирный текст**
```
**
```
**Курсивный текст**
```
*
```
**Зачеркнутый текст**
```
~
```
**Выделяют заголовки — # в начале строки**
**Показать уровень заголовка —
подчеркивание знаками = или (****)**

**Нумерованные Списки — обозначаются
обычными цифрами 1, 2, 3**

**Ненумерованные Списки — обозначаются (*) знаками в начале строки**

**Вложенные Списки — выполняем отступы**

# Туториал по разметке MarkDawn

## Добавление заголовков
Заголовки отмечаются диезом `#` в начале строки, от
одного до шести. Например:
# Заголовок первого уровня #
## Заголовок h2
### Заголовок h3
#### Заголовок h4
Заголовок первого уровня

Заголовок h2

Заголовок h3

Заголовок h4

Заголовок h5

ЗАГОЛОВОК H6

В декоративных целях заголовки можно «закрывать» с обратной
стороны.


## Добавление картинок
Картинка без `alt` текста
```
![](//placehold.it/150x100)
```
Картинка с альтом и тайтлом:
```
![Alt text](//placehold.it/150x100 "Можно задать title")
```
Картинки «сноски»:
```
![Картинка][image1]
[image1]: //placehold.it/250x100
```
Картинки-ссылки:
```
[![Alt text](//placehold.it/150x100)]
(http://example.com/)
```