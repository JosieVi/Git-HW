# Git-HW
## Homework-1
1. Зайдите на github.com, зарегистрируйтесь, создайте public репозиторий  c названием Git_hw
2. Клонировать репозиторий Git_HW на локальный компьютер. git clone https://github.com/JosieVi/Git-HW.git
3. Внутри локального Git_HW создать файл "new.txt".
4. Добавить файл под гит. Добавить содержимое рабочего каталога в индекс: <b>git add</b>
5. Закоммитить файл/сделать коммит: <b>git commit -m 'Add file new.txt'</b>
6. Отправить файл на внешний GitHub репозиторий: <b>git push</b>
7. Зайти на GitHub.com, проверить добавленный файл в удаленном репозитории
8. В локальном репозитории отредактировать содержание файла "new.txt" - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате txt.
9. Отправить изменения на внешний репозиторий. Повторить действия пунктов 4,5,6.
10. Создать файл preferences.txt
11. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате txt.
12. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате txt
13. Создать файл secrets.txt добавить туда ваш супер-секретный ключ (придумайте что угодно)
14. Добавить secrets.txt в gitignore (предварительно создать файл gitignore и разместить его в корне проекта) 
15. Отправить сразу 2 файла на внешний репозиторий. Повторить действия 4,5,6. Сделать коммит в одну строку.
16. На веб интерфейсе (github.com) создать файл bug_report.txt.
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
18. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате txt.
19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
20. Синхронизировать внешний и локальный репозиторий Git_HW: <b>git pull</b>
21. На локальном репозитории создать новую ветку "first_branch": <b>git checkout -b first_branch</b>, <b>git push origin first_branch</b>
22. На локальном репозитории создать новую ветку "second_branch": <b>git branch second_branch</b>, <b>git push origin second_branch</b>
23. На ветке first_branch создать еще 1 файл с баг репортом (закоммитать+запушить): <b>touch bug_report_2.txt</b>, <b>git add 'bug_report_2.txt'</b>
24. На веб интерфейсе создать Pull Request c вашими изменениями на first_branch в main (гитхаб сам предложит, не пропустите!)
25. Вмержить pull request
26. На локальном перейти на ветку main: <b>git checkout main</b>
27. Стянуть свежие изменения и обновить main: <b>git pull</b>
28. Перейти на ветку second_branch: <b>git checkout second_branch</b>
29. Вмержить main в second_branch: <b>git merge main</b>
30. Запушить изменения на внешний репозиторий ветки second_branch: <b>git push origin second_branch</b>
31. На ветке second_branch создать 3й багрепорт (сделать commit and push):  touch bug_report_3.txt, add bug_report_3.txt, git commit -m 'Add bug_report_3.txt to second_branch', git push origin second_branch
32. Перейти на ветку first_branch: <b>git checkout first_branch</b>
33. Скопировать коммит из пунка 31 в first_branch нужной командой: <b>git cherry-pick 79abe79c84c182eae1c44f1316b32aea2a3f46b4</b>
34. Запушить изменения на внешний репозиторий ветки first_branch: <b>git push origin first_branch</b>
35. Перейти в main: <b>git checkout main</b>
36. Сделать Rebase first_branch в main: <b>git rebase first_branch</b>
37. Отправить изменения на внешний репозиторий: <b>git commit -m 'Update after operation rebase', git push</b>
