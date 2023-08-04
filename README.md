# Git commands

[Reference guides](https://git-scm.com/docs)

## List of all commands

![Git logo](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)

### Getting and Creating Projects

```bash
# configura usuário
git config user.name "Fulano de Tal"
```

```bash
# configura e-mail
git config user.email fulano-de-tal@exemplo.br
```

```bash
# exibe as configurações atuais
git config --list
```

```bash
# inicializa um novo repositório git no diretório especificado
git init
```

```bash
# faz o clone de um repositório existe para sua workstation repository
git clone
```

### Basic Snapshotting
```bash
# mostra o status do seu repositório local
git status
```

```bash
# adiciona arquivos ao index
git add file-name
```

```bash
# faz o registro do/dos arquivo/arquivos adicionado no index contendo os metadados
git commit
```

```bash
# mostra quais foram as alterações dentro do arquivo
git diff
```

### Branching and Merging

```bash
# listar, criar ou deletar branch
git branch
```

```bash
# trocar de branch ou restaurar os arquivos que foram alterados
git checkout
```

```bash
# faz a junção de duas ou mais histórias / branch
git merge
```

```bash
# mostra os logs de commits
git log
```

```bash
# Guarde as alterações em um diretório de trabalho temporário
git stash
```

### Sharing and Updating Projects

```bash
# Atualize as referências locais com base no repositório remoto
git fetch
```

```bash
# Busca as alterações do repositório remoto e trás para o repositório legal
git pull
```

```bash
# Envia as alterações do repositório local para o repositório remoto
git push
```

```bash
# Gerenciar reposotórios rastreados
git remote
```
