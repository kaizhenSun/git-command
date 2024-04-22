# git-command
## create a new repository on the command line
```
echo "# fcw_StartShell" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:kaizhenSun/repo_name.git
git push -u origin main
```
## push an existing repository from the command line
```
git remote add origin git@github.com:kaizhenSun/repo_name.git
git branch -M main
git push -u origin main
```
### If report "fatal: remote origin already exists."
```
git remote rm origin
```
## generate ssh
https://docs.github.com/zh/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
