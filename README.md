echo "# ansible_qa" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:blueforus/ansible_qa.git
git push -u origin main
