# Resumo para iniciar com o GIT

## Para criar um novo repositório local
echo "# angular9" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin git@github.com:rsouza13/angular9.git
git push -u origin master

## Subir um proijeto para um repositório exisitente
git remote add origin git@github.com:rsouza13/angular9.git
git branch -M master
git push -u origin master
