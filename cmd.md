# Подсказки по командной строке


Команда смены директории
```sh
cd c:\code_project
```

Команда отображения текущей директории
```sh
pwd
```

Листинг следующей директории
```sh
dir
```

Удаление файла:
```sh
rm <filename> - MacOS
```

```sh
del <filename> - Windows
```

Проверить статус репозитория:
```sh 
git status
```

Сохранение изменений в папке/ветке:
```sh
git add <filename>
git add . 
```

Оставить коммит:
```sh
git commit -m "Message"
```

Взаимодействие с коммитами:
```sh
git log -p -показывает разницу (выводит патч), внесённую в каждый коммит.

git log --oneline -выводит именно короткий хэш
```

Переключение на другие ветки:
```sh
git checkout <branch_name>
```

Просмотр текущей ветки:
```sh
git branch
```

Удаление ветки:
```sh
git branch -d <name_branch>
```

Узнать различия между файлами:
```sh
git diff
```

Слить две ветки:
```
git merge <branch_name>

Делаем из ветки мастер, указываем ту ветку, с которой будем сливать
```

Клонировать репозиторий пользователя:
```sh
git clone <ссылка>
```

Отправка изменений в удаленный репозиторий:
```sh
git push
```

Внести изменения и слить ветки с удаленного репозитория на локальный:
```sh
git pull
```

