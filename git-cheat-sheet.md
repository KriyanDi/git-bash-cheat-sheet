# Git Bash - команди за начинаещи

#### Как да конфигурираме папка и хранилище

##### 1. Инициализиране на желана папка
```git-bash
навигираме до директорията на папката чрез GitBash или в желаната папка с дясно копче -> GitBash here и в конзолата пишем команда:

git init
````
##### 2. Добавяне на файлове
```git-bash
git add . (за добавяне на всички файлове)
git add <file-name>.<file-type> (за добавяне на файл)
```
##### 3. Информация за статуса в хранилището
```git-bash
git status
```
##### 4. Предаване на промените към хранилището
```git-bash
git commit -m "<коментар-на-промените>" (не отваря текстов редактор)
git commit (отваря текстов редактор, в който пишем i -> Initial commit -> esc -> :wq)
```
##### 5. Избутва промените към дистанционното хранилище
```git-bash
git push
```
#### Списък с често ползвани команди
```git-bash
git init
git add <files>
git status
git commit
git push
git pull
git clone
git branch <name>
git config --global user.name ''
git config --global email.name ''
git rm --cached <name>
git remote
git checkout <branches>
git merge
clear
exit
