# git-descomplicado

Apenas um guia prático para começar com git. Sem complicação ;)

1) Obtenha um repositório:

```
git clone https://github.com/emalherbi/git-descomplicado.git
```

2) Crie uma nova branch chamada de "primeira-branch", geralmente cria-se um issues referente a essa branch criada. Esse issues detalha o que está sendo corrigido no projeto:

```
git checkout -b primeira-branch
```

3) Realize suas alterações no projeto e envie suas mudanças para o Index:

```
git add *
```

* Esse comando envia todas suas alterações.

4) Para realmente confirmar estas mudanças (isto é, fazer um commit), use:

```
git commit -m "comentários das alterações, fechar uma issues aberta closed #1, closed #2"
```

5) Envie suas alterações para o git:

```
git push --set-upstream origin primeira-branch
```

6) Retorne para o master usando:

```
git checkout master
```

7) Faça um merge da sua branch para a master:

```
git merge primeira-branch
```

8) Envie suas alterações para a master do git:

```
git push
```

9) Crie uma tag do seu projeto. Essa tag é uma versão do projeto com todos seus commits.

```
git tag -a v1.0.0 -m "minha versao v1.0.0"
```

10) Envie sua tag para o git:

```
git push origin v1.0.0
```

11) Remova a branch do seu local de trabalho e do git:

```
git branch -d primeira-branch
git push origin :primeira-branch
```
