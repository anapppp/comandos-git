# Comandos básicos do GIT

![](https://media3.giphy.com/headers/GitHub/w8ZJLtJbmuph.gif)

Comandos                | Descrição
----------------------- | --------------------------------
`git add .`             | adiciona para o stage todo o diretorio
`git status`            | mostra o status
`git clone`             | clona o diretorio da nuvem pro computador
`git commit -m "msg"`   | comita com mensagem
`git commit --amend -m "nova mensagem"` | altera um commit e atualiza os arquivos que estavam no stage
`git log --oneline`     | imprime informações sobre os commits mais recentes, como o carimbo de data/hora, o autor e uma mensagem de commit.
`git push`              | empurra pra nuvem
`git pull`              | puxar para a maquina
`git init`              | inicializa um repositorio no seu computador (local)
`git status`            | fornece o status
`git add file.js`       | adiciona para o stage apenas o arquivo
`git reset file.js`     | remove arquivo do commit
`git checkout -b nova-branch`   | sai da branch, cria uma nova e muda
`git switch`            | troca de branch 
`git branch`            | lista as branchs
`git branch -m master main` | altera o nome da branch de master para main
`git remote`            | exibe lista de repositórios remotos associados ao repositório local
`git remote add <nome-remoto> <URL-do-repositorio-remoto>` | adiciona um repositório remoto ao seu projeto Git. Usa-se comumente *`origin`* ao iniciar um novo repositório e *`upstream`* para colaborar com um projeto remoto.
`git remote add upstream https://github.com/REPOSITORIO`  |  para manter seu repositório local atualizado
`git pull upstream main`  |  baixa e mescla as alterações no seu repositório local com base na branch main deste repositório original 
`git --h`               | Help!
`git push origin nome-da-branch` |  faz o pull numa branch especifica. 
`git push -u origin nome-da-branch`  |  faz o pull numa branch especifica, e configura essa branch para receber o `git push` automaticamente. 
`git merge nome_da_sua_branch`  |  faz o merge de outra branch com a atual (cheque a branch que vc está, e se ela está atualizada com o servidor remoto)
`git checkout <nome da branch>` | volta para o estado da sua branch atual
`git reset --hard <hash do commit>` | descarta alterações e volta para um commit anterior


##  Status no GIT

- **not staged:** quando o usuário alterou arquivos mas não adicionou para o stage 
- **staged:** quando a pasta ou arquivo já foi adicionado ao stage pelo `git add`, e está pronto para comitar

## Padrões de commits
- feat: para uma nova funcionalidade ou recurso adicionado.
- fix: para uma correção de bug.
- docs: para alterações na documentação.
- style: para alterações que não afetam o comportamento do código (por exemplo, formatação, ponto e vírgula ausente).
- refactor: para alterações no código que não corrigem bugs nem adicionam novos recursos.
- test: para adicionar testes ausentes ou corrigir testes existentes.
- chore: para tarefas de manutenção ou trabalho de casa.
- perf: para melhorias de desempenho.

