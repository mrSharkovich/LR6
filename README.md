# Отчёт по лабораторной работе №6 (2)
# Система контроля версий
Выполнила студентка группы 4414
Гнатив М.Ю.

## **Цель работы**
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

## **Решение**
### Создать аккаунт на сайте GitHub, установить Git 
Аккаунт был создан, Git был установлен.

### Сделать копию в личное хранилище из Fork
![img](screenshots/13.jpg)
### После установки настроить клиент git, введя имя пользователя и email
![img](screenshots/1.jpg)
### Клонировать свой личный удалённый репозиторий на компьютер
![img](screenshots/2.jpg)
### Добавить файл через интерфейс GitHub. Подтянуть изменения в локальный репозиторий
![img](screenshots/7.jpg)
### Получить историю операций для каждой из веток
![img](screenshots/3.jpg)
### Просмотреть последние изменения
![img](screenshots/5.jpg)
### Выполнить слияние в ветку master, разрешив конфликт
![img](screenshots/merge_before.jpg)
![img](screenshots/merge_after.jpg)
![img](screenshots/6.jpg)
### Удалить побочную ветку после успешного слияния
![img](screenshots/4.jpg)
### Сделать изменения и зафиксировать их, оставляя комментарии, несколько раз
![img](screenshots/10.jpg)
### Сделать откат коммита
![img](screenshots/revert.jpg)
![img](screenshots/8.jpg)
### Создать ветку для отчёта
![img](screenshots/9.jpg)
### Начать оформлять отчёт в файле README.md, используя markdown синтаксис
![img](screenshots/11.jpg)
#### Файлы снимков экрана разместить в отдельной папке
Файлы раземещены в папке screenshots.
#### Лог команд
+ git config --global user.name 
+ git config --global user.email 
+ git clone
+ git pull
+ git log --oneline --graph --all
+ git log -p -1
+ git merge
+ git checkout 
+ git add
+ git commit
+ git status
+ git push
+ git push origin --delete
+ git log --oneline
+ git revert (открылся VIM)
+ git log --pretty=format:"%h %ad %an %s" --date=short
+ 
### Получить историю операций в форматированном виде, добавить её в отчёт и сделать финальную фиксацию изменений.
![img](screenshots/12.jpg)


## **Вывод**
В ходе работы были изучены базовые возможности системы управления версиями, был получен опыт работы с Git Api, с локальным и удаленным репозиторием.