git init
git clone <URL-del-repo>
git remote add origin <URL-del-repo>
git add .
git commit -m ""
git push origin main
echo "privado.txt" >> .gitignore
echo "privada/" >> .gitignore
git branch v0.2
git checkout v0.2
git tag v0.1
git push origin v0.1
git checkout master
git merge v0.2
git add 1.txt
git commit -m "Conflicto resuelto"
git branch
git branch --merged
git branch --no-merged
git branch -d v0.2
git log --oneline --decorate --graph --all
git config --global alias.list "log --oneline --decorate --graph --all"
