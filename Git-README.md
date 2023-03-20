cd <localdir>
#initialise git on local dir to create .git/
git init

git add .
git commit -m 'message'

#if any issue with git account run below:
git config credential.username "new_username"
git config --global credential.username "new_username"

git config user.email "you@example.com"
git config user.name "Your Name"

git remote add origin <https://github.com/SabinChh/todo_list_app>
git push -u origin main