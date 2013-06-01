Tradução do [TRY GIT](http://try.github.io/) para Português Brasileiro
=============================================

Clonar repositório
------------------
```bash
$ git clone https://github.com/REPOSITORIO/REPOSITORIO.git
```

Inicializar repositório na pasta
--------------------------------
```bash
$ git init
```

Exibir o status do repositório git na pasta
-------------------------------------------
```bash
$ git status
```

Adicionar arquivos ao versionamento
-----------------------------------
```bash
$ git add NOME_DO_ARQUIVO
```

Remover arquivos do versionamento
---------------------------------
```bash
$ git rm NOME_DO_ARQUIVO
```

Submeter as modificações efetuadas
----------------------------------
```bash
$ git commit -m "Mensagem explicando o que foi feito na submissão"
```

Exibir log das submissões efetuadas
-----------------------------------
```bash
$ git log
```

Adicionar um repositório remoto
-------------------------------
```bash
$ git remote add origin https://github.com/REPOSITORIO/REPOSITORIO.git
```

Enviar todas as submissões locais para o servidor remoto
--------------------------------------------------------
```bash
$ git push -u origin master
```

Baixar submissões feitas por outras pessoas no repositório remoto
-----------------------------------------------------------------
```bash
$ git pull origin master
```

Exibir as diferenças entre a última submissão e o servidor remoto
-----------------------------------------------------------------
```bash
$ git diff HEAD
```

Exibir modificações que efetuei no repositório local
----------------------------------------------------
```bash
$ git diff --staged
```

Remover arquivo do versionamento antes da submissão
---------------------------------------------------
```bash
$ git reset NOME_DO_ARQUIVO
```

Retornar os arquivos até o estado do último commit do arquivo informado
-----------------------------------------------------------------------
```bash
$ git checkout -- NOME_DO_ARQUIVO
```

Criar novo branch no repositório
--------------------------------
```bash
$ git branch NOME_DO_BRANCH
```

Listar branchs existentes
-------------------------
```bash
$ git branch
```

Mudar para o branch informado
-----------------------------
```bash
$ git checkout NOME_DO_BRANCH
```

Unir o branch atual ao branch informado
---------------------------------------
```bash
$ git merge NOME_DO_BRANCH
```

Remover branch do repositório local
-----------------------------------
```bash
$ git branch -d NOME_DO_BRANCH
```