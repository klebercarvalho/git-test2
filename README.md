# git-test2

# Testar conexão com o Github
ssh -T git@github.com

# Criar um arquivo chamado README.md
echo "# git-test2" >> README.md

# Initializa um Repositorio
git init

# adiciona o arrquivo README.md p/ o proximo commit
git add README.md

# Falei p/o Git quais arquivos e quero mandar para o servidor 
git commit -m "first commit"

# adicionei esse o repositorio de destino
git remote add origin git@github.com:klebercarvalho/git-test2.git

# enviar minha alterações para o servidor
git push -u origin master

# quais arquivos estão prontos para o proximo envio (commit)
git status

