# Manual Github

> Manual para realizar carga de projetos no github.

Para projetos já no github:

```
Passo 1: git clone https://github.com/CarlosLopes88/Manual_github.git

Passo 3: git add . (. ou o nome do arquivo index.html) para adicionar os arquivos a primeira versão dos arquivos

Passo 4: git commit . -m "primeiro commit"

Passo 5: git push

```

Para projetos novos no github:

```
Passo 1: git init na pasta do projeto

Passo 2: git add . (. ou o nome do arquivo index.html) para adicionar os arquivos a primeira versão dos arquivos

Passo 3: git branch -M main para alterar o nome da branch para a nova nomenclatura 

Passo 4: git remote add origin https://github.com/CarlosLopes88/teste_poo_av.git para adicionar o endereço do repositório

passo 5: git push -u origin main

```

Outros comandos github:

```
git -- version verifcar a versão instalada

git log verificar as alterações no reposotório

git log --oneline verificar as alterações compactadas

git status verificar status dos commits

git checkout -b desenvolvimento criando uma branch chamada desenvolvimento

git switch desenvolvimento trocar a branch

git branch mostra a branch que eu estou

git merge desenvolvimento quando estiver na branch main o comando trará todas as alterações da desenvolvimento e unirá com a main finaliando o proceso com um git push origin main

git restore --source a0c893b retorna ao estado do versionamento da rash git a0c893b

```

:)
