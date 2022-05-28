# Comandos git

## Configurações:
Usar o comando `git config --global` junto com um dos pâmetros:
 - **Email:** `user.email email@exemple.com`
 - **Usuário:** `user.name user_name`
 - **Editor de código:** `core.editor vim`
 - **Ferramenta de merge:** `merge.tool vimdiff`
 - **Aquivos ignorados:** `core.excludesfile ~/.ignore`
Para listar as configurações: `git config --list`

## Outros Comandos:

 - **Criar um novo repositório:** `git init name`
 - **Verificar o stado do repositório:** `git status`
 - **Adicionar arquivo/diretório:** `git add [...]`
 - **Adicionar tudo:** `git add .`
 - **Comitar:** `git commit -m "novo commit"`
 - **Exibir histórico:** `git log`
 - **Exibir o repositório remoto:** `git remote` / `git remote -v`
 - **Vincular com repositório remoto:** `git add [origin] [...]`
 - **Exibir informações do reposiório remoto:** `git remote show [origin]`
 - **Renomear um repositório remoto:** `git remote rename [origin] [origin-github]`
 - **Remover repositório remoto:** `git remote rm [...]`
 - **Dar pull:** `git pull`
 - **Dar push:** `git push -u [origin] [master]`
 - **Clonar um repositório:** `git clone [url]`
 - **Ajuda:** `git help` / `git help [add]`s