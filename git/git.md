# Remove the cached files and add again using these commands
```sh
git rm -r --cached .
git add .
git commit -am "Removed git ignored files"
git push -f origin master

# Or 
echo .DS_Store >> ~/.gitignore_global
git config --global core.excludesfile ~/.gitignore_global
```
