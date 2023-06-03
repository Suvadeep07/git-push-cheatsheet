# git-push-cheatsheet
## Pushing a new file 
echo "# git-push-cheatsheet" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Suvadeep07/git-push-cheatsheet.git
git push -u origin main

## Pushing a old file 
git remote add origin https://github.com/Suvadeep07/git-push-cheatsheet.git
git branch -M main
git push -u origin main
