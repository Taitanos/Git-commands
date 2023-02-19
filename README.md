# Git commands

The most commonly used commands for working with git
Наиболее часто используемые команды для работы с git

1. #git status
Проверка проекта на изменения в файлах

2. #git add . 
Добавление измененных всех файлов в stage (подготовка к отправке)

3. #git commit -m ‘в ковычках указывается что именно было сделано’
Добавление комментария 

4. #git log
Команда используется для подробного просмотра комментарий в проекте

5. #git log --oneline
Команда для просмотра короткой записи комментариев в проекте

6. #git push [per_link] [branch-name]
Команда для отправки локальных правок на удаленный репозиторий (обычно используется команда git push origin main (вместо main название ветки))

7. #git reset
Команда позволяет удалить некоторые файлы из промежуточной области

8. #git reset --hard
Команда позволяет удалить все изменения в файлах из промежуточной области

9. #git diff
Команда позволяет увидеть внесенные изменения в файле

10. #git branch
Команда позволяет увидеть какие есть ветки в проекте

11. #git branch [name new branch]
Команда позволяет создать новую ветку в проекте для этого нужно после слова branch написать название новой ветки

12. #git branch -d [name branch]
Команда позволяет удалить ветку в локальном репозитории

13. #git checkout [name branch]
Команда позволяет переключиться на указанную ветку в [name branch]

14. #git checkout -b [name branch]
Команда позволяющая создать и переключиться на новую ветку.

15. #git fetch
Команда позволяющая проверить изменения сделанные на удаленном репозитории не применяя изменения

16. #git pull [per_link] [branch-name]
Команда позволяющая загрузить все изменения из удаленного репозитория в локальный (команда производит сразу два действия git fetch и git merge)

17. #git merge [name branch]
Команда позволяющая переместить код из одной ветки в другую, для этого нужно переключиться на ветку в которую нужно переместить код, а затем с помощью команды указать из какой ветки нужно загрузить код.
