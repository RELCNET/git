<!-- git config user and email -->
git config user.email test@gmail.com

<!-- Making commits -->
git commit -m "first commit"

<!-- Commit history -->
git log
git log --oneline

<!-- Undoing stuff -->
git checkout
git revert
git reset
git reset 12345 --hard


<!-- CREATING BRANCHS -->
<!-- novo branch -->
git branch nomedobranch

<!-- ver os branchs -->
git branch -a

<!-- mudar para o brach -->
git checkout nomedobranch

<!-- apagar branch -->
git branch -D nomedobranch

<!-- criar e mudar para o branch criado -->
git chechout -b nomedobranch

<!-- MERGING BRANCHS -->
git merge nomedobranch

<!-- quando a confilito no merge -->
git commit

<!-- GITHUB -->
<!-- enviar para github site -->
git push https://github.com/RELCNET/git.git master

<!-- atalho para enviar github site -->
git remote add origin https://github.com/RELCNET/git.git
git push origin master

<!-- inviar uma branch para o repositorio para revisões do colegas e depois puxar -->
git push origin nomedobrunch

<!-- para puxar as mudanças atraves do repositório github -->
git pull origin master

<!-- ver em que repositorio está -->
git remote -v


<!-- ==================================================== -->

<!-- INFORMAÇÕES DO SITE -->
…or create a new repository on the command line
echo "# ReactNative" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/RELCNET/ReactNative.git
git push -u origin main
                
…or push an existing repository from the command line
git remote add origin https://github.com/RELCNET/ReactNative.git
git branch -M main
git push -u origin main
