git status
git add [files]
git add . добавили все файлы в stage
git commit -m "comment"
git log
git log --oneline
git push [rep_link] [branch_name] / git push origin master

git branch
////////////////////////

 git reset index.html убрать наш файл с изменениями

 git diff позволяет просмотреть те сроки которые мы изменяли
  git diff index.html  выйти на q

  git reset --hard вернуть на изначальное положение изменения
  ///////////////////////////
  ветки
  git branch develop
  git checkout develop// переключение на ветку

git pull origin master забрали с гит хаба изменения
<<<<<<< HEAD
git branch -D develop //удалили ветку

///////////////////////
слияние веток
1. git checkout master
2. git merge feature/main-page
=======
git branch -D develop //удалили ветку
удаляем ветки на гитхаб и еще и локально
>>>>>>> feature/main-page
