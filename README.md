# learnGit
Как я повышал скилл в git

##workshop
+ [Git How To — интерактивный тур](http://githowto.com/ru)
+ https://try.github.io/levels/1/challenges/1 (+)
+ [Git Real](http://gitreal.codeschool.com/)

##Обучащий ведео-курс
[Lynda.com](http://www.lynda.com/Git-tutorials/Git-Essential-Training/100222-2.html)

##Общие короткие видео
+ 007. Системы контроля версий - Сергей Сергеев - ШРИ (+)

##Cтатьи
- [Git Flow](http://habrahabr.ru/post/106912/)
- [Git Rebase: руководство по использованию](http://habrahabr.ru/post/161009/)
- [19 советов по повседневной работе с Git](http://habrahabr.ru/company/mailru/blog/267595/)

##Книга
- http://firstaidgit.ru/ FAQ

##Дополнительно
+ http://geektimes.ru/post/248744/ - Интервью с Линусом Торвальдсом
+ http://danielkummer.github.io/git-flow-cheatsheet/index.ru_RU.html - надстройка над гитом для гит флоу
+ TortoiseGit 


#Вопросы на которые надо ответить
**Что такое rebase?**
**Что такое git flow, альтернативы**
**Как использовать stash**

#Выводы

+ Коммитить нужно частно, но атомарно
+ **commit massages**
  Нужно подробно описывать что сделал
  Начните писать в commit'ах пользовательскую ценность добавленного кода. Не «добавил два метода», а «Теперь пользователю быстрее/легче/меньше...» или «появилась функция / изменилась реакция». Вам нечего написать? Вы ничего не сделали за день.
  Название 50 строк и отбивка перед описанием
+ git flow
+ rebase
+ Ветка на каждый чих
+ WilCard. git add '*.txt' . Don't forget the quotes!
+ The name of our remote is origin and the default local branch name is master. The -u tells Git to remember the parameters, so that next time we can simply run git push and Git will know what to do. Go ahead and push it!
git push -u origin master
+ Git Hooks
+ git stash:
Sometimes when you go to pull you may have changes you don't want to commit just yet. One option you have, other than commiting, is to stash the changes.
Use the command 'git stash' to stash your changes, and 'git stash apply' to re-apply your changes after your pull.
+ Вспомогательные ветки надо через определенное время удалять
