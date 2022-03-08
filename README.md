
[Git Documentation](https://git-scm.com/doc) |
[Learn Git Branching](https://learngitbranching.js.org/?locale=pt_BR) |
[Atlassian tutorials](https://www.atlassian.com/br/git/tutorials/what-is-version-control)

| Nome | Descrição |
| ------ | ------ |
| [`git-reflog`](https://git-scm.com/docs/git-reflog) | Logs de referência |
| [`git reset HEAD@{1}`](https://git-scm.com/docs/git-reflog) | Pegamos o index do qual desejamos voltar |
| [`git branch -D`]() | Shortcut for `--delete` `--force` |
|[`git branch -d`]() | Delete a branch. `-d` or `--delete` |
|[`git switch -c`]() | with `-c` switch to new-branch |
| [`git-diff`]() | Mostra mudanças entre commits, commit e árvore de trabalho |
| [`git-diff --cached`]() | Esta opção faz com que a entrada apareça como um novo arquivo em "git diff" |
| [`git-reset`]() | Redefine o HEAD atual para o estado especificado |
| [`git-reset --hard`]() | Redefine o índice e a árvore de trabalho. Quaisquer alterações nos arquivos rastreados na árvore de trabalho desde `<commit>` são descartadas. |
| [`git-add -u`]() | Atualize o índice apenas onde ele já possui uma entrada correspondente a `<pathspec>`. Isso remove e também modifica as entradas de índice para corresponder à árvore de trabalho, mas não adiciona novos arquivos. |
| [`git-checkout -`]() | Alterne ramos ou restaure arquivos de árvore de trabalho - retorna na última branch |
| [`git-checkout -`]() | Alterne ramos ou restaure arquivos de árvore de trabalho - retorna na última branch |
| [`git-merge --no-ff`]() | Junte dois ou mais históricos de desenvolvimento juntos Com `--no-ff`, crie um commit de mesclagem em todos os casos, mesmo quando a mesclagem pudesse ser resolvida como um avanço rápido. |
| [`git-stash`]() | Esconde as mudanças em um diretório de trabalho sujo |
| [`git stash list`]() | As modificações armazenadas por este comando podem ser listadas `git stash list` |
| [`git stash show`]() | As modificações armazenadas por este comando podem ser inspecionadas `git stash show` |
| [`git stash clear`]() | Limpa as modificações armazenadas |
| [`git stash apply `]() | As modificações armazenadas por este comando podem ser restauradas (potencialmente em cima de um commit diferente) com `git stash apply` |
| [`git stash pop `]() | Remova um único estado de stash da lista de stash e aplique-o no topo do estado da árvore de trabalho atual, ou seja, faça a operação inversa de `git stash push`. O diretório de trabalho deve corresponder ao índice. |
| [`git checkout -- fileName`](https://git-scm.com/docs/git-checkout) | Prepare-se para trabalhar em cima <commit>, desanexando HEAD-o (consulte a seção "CABEÇA DESTACADA") e atualizando o índice e os arquivos na árvore de trabalho. As modificações locais nos arquivos na árvore de trabalho são mantidas, de forma que a árvore de trabalho resultante será o estado registrado no commit mais as modificações locais. |
| [`git checkout -D fileName`](https://git-scm.com/docs/git-checkout) | Em vez de verificar um branch para trabalhar nele, verifique um commit para inspeção e experimentos descartáveis. Este é o comportamento padrão de git checkout <commit>quando <commit>não é um nome de ramificação. Consulte a seção "CABEÇA DESTACADA" abaixo para obter detalhes. |
| [`git-cherry-pick`](https://git-scm.com/docs/git-cherry-pick) | Aplica as mudanças introduzidas por alguns commits existentes |
| [`git merge-base`](https://git-scm.com/docs/git-cherry-pick) | encontra os melhores ancestrais comuns entre dois commits para usar em uma fusão de três vias. Um ancestral comum é melhor do que outro ancestral comum se este for um ancestral do primeiro. |
| [`git log --oneline -5`](https://chris.beams.io/posts/git-commit)| últimos 5 commits, Este é um atalho para "--pretty = oneline --abbrev-commit" usado junto. |
| [`Git Aliases`](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases) | Criar Alias |
| [`git-blame`](https://git-scm.com/docs/git-blame) | Mostra qual revisão e autor modificou por último cada linha de um arquivo |
