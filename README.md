# This project just for study GIT and Python
git config --global user.email "kornerus@fjfi.cvut.cz"
git config --global user.name "Ruslan"


# связать удаленный и локальный репозиторий
git remote add origin {ссылка}

# опубликовать ветку в первый раз
git push -u origin название_ветки

# опубликовать изменения в существующей ветке на GitHub
git push

# переключение и создание веток
git checkout -b develop
(git checkout название_ветки - переключение на другую ветку)
(git checkout -b название_ветки - создание и переключение на другую ветку)
