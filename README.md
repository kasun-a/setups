# create a new repository on the command line

```sh
echo "# setups" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/user/repo.git
git push -u origin main
```

# push an existing repository from the command line

```sh
git remote add origin https://github.com/user/repo.git
git branch -M main
git push -u origin main
```
