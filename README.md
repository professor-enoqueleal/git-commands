# Git commands

[Reference guides](https://git-scm.com/docs)

## List of all commands

![Git logo](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)

### Getting and Creating Projects

```bash
# configura usuário
$ git config user.name "Fulano de Tal"

# configura e-mail
$ git config user.email fulanodetal@exemplo.br

# exibe as configurações atuais
$ git config --list

# inicializa um novo repositório git no diretório especificado
$ git init

# faz o clone de um repositório existe para sua workstation repository
$ git clone
```

### Basic Snapshotting
```bash
# mostra o status do seu repositório local
$ git status

# adiciona arquivos ao index
$ git add

# faz o registro do/dos arquivo/arquivos adicionado no index contendo os metadados
$ git commit

# mostra quais foram as alterações dentro do arquivo
$ git diff

```

### Branching and Merging

```bash
# listar, criar ou deletar branch
$ git branch

# trocar de branch ou restaurar os arquivos que foram alterados
$ git checkout

# faz a junção de duas ou mais histórias / branch
$ git merge

# mostra os logs de commits
$ git log

# Guarde as alterações em um diretório de trabalho temporário
$ git stash
```

### Sharing and Updating Projects

```bash
# Atualize as referências locais com base no repositório remoto
$ git fetch

# Busca as alterações do repositório remoto e trás para o repositório legal
$ git pull

# Envia as alterações do repositório local para o repositório remoto
$ git push

# Gerenciar reposotórios rastreados
$ git remote
```
