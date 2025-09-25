git init
git add .
echo "node_modules/" > .gitignore
echo ".env" >> .gitignore
git add .gitignore
git commit -m "Initial commit"
# crie um repositório no GitHub pelo site e depois:
git remote add origin git@github.com:SEU_USUARIO/NOME_REPO.git
git branch -M main
git push -u origin main
