# Curso Git & GitHub

Feito para concretizar o conhecimento e estudar mais a tecnologia.


Anotações:

1.Configurando:
$ git config --global user.name "user_name"
$ git config --global user.email "user_email"
$ git config --global core.editor vim

2.Criando & Iniciando Repositório:
$ mkdir nome_repositório
$ cd nome_repositório
$ git init
$ git status

3.Adicionando & Commitando Repositório
$ vim Readme.txt
$ git add Readme.txt
$ git commit -m "Add Readme.txt"
$ git show commit_hash
$ git push origin master

4.Logs
$ git log
$ git log --decorate
$ git log --author="author_name"
$ git shortlog -sn

5.Diff
$ git diff

6.Resets & Checkout & Revert
$ git reset HEAD Readme.txt
$ git checkout Readme.txt
$ git revert commit_hash

7.Branch
$ git branch
$ git checkout -b brach_name_to_create
$ git checkout branch_name_to_go
$ git branch -D branch_name_to_delete

8.Merge & Rebase
$ git merge branch_to_merge
$ git rebase branch_to_rebase

9.gitignore
$ vim .gitignore
$ git add .gitignore
$ git commit -a

10.Git Stash
$ git stash
$ git stash apply
$ git stash list
$ git stash clear

11.Alias - Adicionando comandos/shortcuts
$ git config --global alias.shortcut command_name
$ git config --global alias.s status
$ git s = $ git status

12.Tags
$ git tag
$ git tag -a version_num -m "msg"
$ git tag -a 1.0.0 -m "Readme finalizado"
$ git tag -d tag_to_delete
$ git commit -am "msg"
$ git push origin master --tags

13.Apagando do repositório remoto
$ git push origin :tag/branch_to_delete
$ git push origin :1.0.0