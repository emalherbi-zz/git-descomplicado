# git-descomplicado

Apenas um guia prático para começar com git. Sem complicação ;)

1) Obtenha um repositório:

git clone https://github.com/emalherbi/git-descomplicado.git

2) Crie uma nova branch chamada de "primeira-branch":

git checkout -b primeira-branch

3) Crie uma nova tag dessa sua branch.

git tag -a v1.0.0 -m "primeira-tag referente a primeira-branch"

4) Realize suas alterações no projeto e envie suas mudanças para o Index:

git add *

* Esse comando envia todas suas alterações.

5) Para realmente confirmar estas mudanças (isto é, fazer um commit), use:

git commit -m "comentários das alterações"

6) Envie suas alterações para o git:

git push --set-upstream origin primeira-branch
