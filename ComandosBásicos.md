# GIT
  
## CONCEITO:
Sistema de Controle de Versão Distribuídos - Source Control Management

## CONCORRENTES:
SVN, Mercurial, CVS e Bazaar.

## ESTADOS DOS ARQUIVOS:
UNTRACKED - Não monitorado
TRACKED - Monitorado - Rastreado
MDDIFIED - Rastreado e modificado
STAGE - Pronto para ser enviados

## COMANDOS: 

### Configurações: 
#### Serve para o Git te identificar. Se não utilizar o "global" a cada repositório criado, terá que dar esses comandos.
- git config user.name "nomeDaPessoa"
- git config user.email "EmailDaPessoa"

#### Ao utilizar o "global" você não precisará fazer isso mais. É indicado somente para o caso do computador ser seu.
- git config --global user.name "nomeDaPessoa"
- git config --global user.email "EmailDaPessoa"

### Inicializar o repositório
- git init

### Adicionar o arquivo para ser monitorado
- git add nomeDoArquivo.extensao

### Verificar o status da sua branch
- git status

### Comitar, ou seja, tirar uma fotografia do estado da sua branch
- git commit -m "mensagem Desejada"

### Verificar todos os commits realizados e identificar os hash (identificadores) dos mesmo
- git log

### Verificar quais branches tem no seu repositório local
- git branch

### Verificar todas as branches do repositório remoto que você clonou
- git branch -a

### Excluir branch local
- git branch -D

### Renomear branch 
- git branch -M

### Clonar o repositório remoto (obter uma cópia)
- git clone <link do repositorio remoto>

### Puxar o repositório remoto, sem fazer cópia
- git pull <link do repositorio remoto>

### Puxar repositório específico para sua branch 
- git pull <remote> <branch>

### Enviar sua branch para o repositório remoto com um branch remoto específico
- git push <remote-name> <local-branch-name>:<remote-branch-name>

### Enviar branch para o repositório remoto
- git push <branch-remoto> <branch-local>

### Altere a URL do repositório remoto do SSH para HTTPS com o comando git remote set-url.
- git remote set-url origin https://github.com/USERNAME/REPOSITORY.git

### Enviar branch para o repositório remoto, sem precisar digitar o branch local. O branch a ser considerado é o que você está trabalhando.
- git push <branch-remoto> HEAD

### Alterar a origem remota utilizando uma URL
- git remote set-url origin <linkDoRemoto>

### Verificar qual a sua origem remota
- git remote -v

### Para erros do tipo fatal: refusing to merge unrelated histories
- git pull main main --allow-unrelated-histories


