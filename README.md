# FlowersShop
clear			        -> очистить консоль

cd folderName     -> перейти в папку

ls	      		    -> просмотреть папки, в которые можно перейти

git status        -> показывает изменения (красные файлы - новые, желтые - измененные, зеленые - добавлены, но нужно отправить на гит)

git add fileName	-> добавить файл (fileName - имя файла) 

git add .		      -> добавить все файлы

git commit -m "коментрарии к коммиту" 	-> использовать после add


git rm --cached fileName  -> отменить добавление файла


git push		-> закинуть файл в репозиторий (использовать после commit)

git pull		-> затянуть из гитхаб репозитория новые файлы


git branch		        -> посмотреть текущее имя ветки

git branch name	    	-> создать ветку с именем name

git branch -D name	  -> удалить ветку с именем name

git checkout name	    -> переключиться на ветку name

git checkout -b name	-> создать новую ветку name и переключиться на неё

git merge name		    -> совместить текущую ветку с name (добавить новые файлы из name в текущую)

git branch -M main	  -> переименовать главную ветку с master в main


git remote add origin ссылка на гитхаб 	-> связать гитхаб и проект

git push -u origin main(или master)   	-> добавить в репозиторий всё, что есть в проекте сейчас

git config --global user.name 		    -> показать имя

git config --global user.name "Name" 	-> сменить имя

git config --global user.gmail 		    -> показать gmail

чтобы добавить в .gitignore папку нужно в него дописать /foledName
