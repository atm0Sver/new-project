mkdir new-project  
cd new-project    
echo "init" >> README.md
  git init
  git add README.md
  git commit -m "init"
  git branch -M main
  git remote add origin https://github.com/atm0Sver/new-project.git
  git push -u origin main
git checkout -b development
notepad README.md
git add .
git commit -m "Add instruction to README.md"
git checkout main
git merge development
git push -u origin main
