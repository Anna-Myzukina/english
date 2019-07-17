# english
english

https://www.w3schools.com/css/css_rwd_grid.asp

создаем новый репозиторий на гитхабе . 
затем заходим в этот репозиторий и нажимаем на зеленую кнопку скопировать .
копируем ссылку открывам у себя на компе терминал там пишем 
git clone http://...
git status
git branch //посмотреть сколько веток и их название та которая светиться зеленым значит сейчас активна 
git branch developer// создаем ветку с названием девелопер
git checkout developer // переключаемся в эту ветку.по умолчание мы изначально в ветке с названием мастер
затем содаем файлы ....делаем разные измнения в этих файлах....
git status 
git add .
git commit -m"comments"
git push origin developer
*************
после этого можно на гитхабе проверить в новой ветке изменения.если разработка идет в паре на этом этапе второй разработчик выполняет следующуюкоманду
git pull
после git pull второй разработчик вносит изменения в проект и когда завершил изменения второй разработчик делает таие же команды git status
git add .
git commit -m"comments"
git push origin developer
************
when you with coding partner finished project in github make pull for request
************
after good request you should merge branches
************
git fetch
git checkout master
git pull
git merge developer
git status
git push origin master
