
Curso Git & GitHub

Feito para concretizar conhecimento na tecnologia


Anotações:

1.Configurando:
$ git config --global user.name "user_name"
$ git config --global user.email "user_email"
$ git config --global core.editor vim

2.Criando e Iniciando Repositório:
$ mkdir nome_repositório
$ cd nome_repositório
$ git init
$ git status

3.Adicionando e Commitando Repositório
$ git add Readme.txt
$ git commit -m "Add Readme.txt"
$ git push origin master

4.Logs
$ git log
$ git log --decorate
$ git log --author="author_name"
$ git shortlog -sn

5.Diff
$ git diff

6.Resets e Checkout
$ git reset HEAD Readme.txt
$ git checkout Readme.txt

7.Branch
$ git branch
$ git checkout -b brach_name_to_create
$ git checkout branch_name_to_go
$ git branch -D branch_name_to_delete