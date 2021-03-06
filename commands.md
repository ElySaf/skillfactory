[< к содержанию](./readme.md)

## git add

**git add *[файл]*** - добавляет файл в индекс. 

Чтобы добавить все файлы в индекс (кроме игнорируемого), используйте команду:
```bash=
git add .
```

## git status

**git status** - показывает состояния файлов в рабочей директории и индексе: какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе. Вдобавок к этому выводятся подсказки о том, как изменить состояние файлов.

## git commit

**git commit** - берёт все данные, добавленные в индекс с помощью `git add`, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок.


## git rm

**git rm** - используется в Git для удаления файлов из индекса и рабочей копии. Она похожа на `git add` с тем лишь исключением, что она удаляет, а не добавляет файлы для следующего коммита
