# gitflow-examplegit 

1. Создать репозиторий на GitHub и клонировать его на компьютер

2. Создать ветку разработки develop от главной ветки (master or main)

git branch develop

git checkout develop

git push origin develop

---------------
GitFlow, часть 2

git branch feature/main-page
git checkout feature/main-page

3. Создать от ветки develop feature/-ветки и мержить feature/-ветки в develop когда фичи будут выполнены
git merge feature/main-page -m "Merge feature/main-page into develop"