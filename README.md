# Урок 2. Домашняя работа

```
git remote -v
git log --oneline
git branch
git switch -c testing_program
... commiting...
git checkout master
git merge testing_program
... создал другой удалённый репозиторий...
git remote remove origin
git remote -v
git remote add origin https://github.com/Grudzinsky1978/Git-Advanced-Lesson-2.git
git switch -c testing_the_program
... commiting...
git push -u origin testing_the_program
git checkout master
git merge testing_the_program
git push
git log --oneline
git diff 1dea07c 6f91396
git diff 6f91396 df98383
git revert df98383
git revert 6f91396
git revert 1dea07c
... последняя команда вызвала конфликт, был разрешён в редакторе конфликтов
git reset --soft 1dea07c
git restore --staged README.md
git restore --staged seminar_8-homework.py
git branch
git reset --mixed 6f91396
git restore --staged README.md
git restore --staged seminar_8-homework.py
git restore --staged README.md
git restore --staged phonebook.txt
git reset --hard df98383
git pull
git push
```




# Урок 1. Домашняя работа
Инициализирован локальный репозиторий
```
git init
git add .
git commit -m "Git Advanced. Lesson 1. Homework 1. initial commit"
```
Создан удалённый репозиторий с тем же именем, что и локальная папка
Добавлен путь для связи с удалённым репозиторием
```
git remote add origin https://github.com/Grudzinsky1978/git_hw_1.git
git remote -v
git branch -M master
git push -u origin master
```
Изменён файл удалённого репозитория
Выполнена команда `git pull` для передачи изменений в локальный репозиторий

*Попробуем изменить локальный файл, затем в том же месте файл удалённого репозитория*
**Вот здесь другой текст**

# Описание программы
## Телефонный справочник с возможностью импорта и экспорта данных в формате .txt.
* Фамилия, имя, отчество, номер телефона - данные, которые должны находиться в файле.
1. Программа выводит данные
2. Программа сохраняет данные в текстовом файле
3. Пользователь может ввести одну из характеристик для поиска определенной записи (например, имя или фамилию человека)

# Урок 1. Домашняя работа
Инициализирован локальный репозиторий
```
git init
git add .
git commit -m "Git Advanced. Lesson 1. Homework 1. initial commit"
```
Создан удалённый репозиторий с тем же именем, что и локальная папка
Добавлен путь для связи с удалённым репозиторием
```
git remote add origin https://github.com/Grudzinsky1978/git_hw_1.git
git remote -v
git branch -M master
git push -u origin master
```
Изменён файл удалённого репозитория
Выполнена команда `git pull` для передачи изменений в локальный репозиторий

*Попробуем изменить локальный файл, затем в том же месте файл удалённого репозитория*
```
git push
ошибка
git fetch
```
Открыл файл, разрешил конфликт, выбрал нужный вариант изменений
```
git merge
git commit -m "Merged"
```

# Описание программы
## Телефонный справочник с возможностью импорта и экспорта данных в формате .txt.
* Фамилия, имя, отчество, номер телефона - данные, которые должны находиться в файле.
1. Программа выводит данные
2. Программа сохраняет данные в текстовом файле
3. Пользователь может ввести одну из характеристик для поиска определенной записи (например, имя или фамилию человека)
