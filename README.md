git init
git config --global user.name 'Shakin'
git config --global user.email 'dimkinsa9@gmail.com'
git add .
git status
git commit -m 'fail ignore'
git status
git branch new
git status
git checkout new
git status
далее добавил папку и файлы в новую ветку
git add .
git status
git commit -m 'files in new'
git status
On branch new
git checkout master
git remote
git remote add origin https://github.com/dimkinsa/githome.git
git remote
git push -u origin master
