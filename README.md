echo "# TEST" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/2024P/TEST.git
git push -u origin main
