
| Nome | Descrição |
| ------ | ------ |
| [`git-reflog`](https://git-scm.com/docs/git-reflog) | Logs de referência |
| [`git-diff`]() | Mostra mudanças entre commits, commit e árvore de trabalho |
| [`git-diff --cached`]() | Esta opção faz com que a entrada apareça como um novo arquivo em "git diff" |
| [`git-reset`]()  | Redefine o HEAD atual para o estado especificado |
| [`git-reset --hard`]() | Redefine o índice e a árvore de trabalho. Quaisquer alterações nos arquivos rastreados na árvore de trabalho desde `<commit>` são descartadas. |
| [`git-add -u`]() | Atualize o índice apenas onde ele já possui uma entrada correspondente a `<pathspec>`. Isso remove e também modifica as entradas de índice para corresponder à árvore de trabalho, mas não adiciona novos arquivos. |
| [`git-checkout -`]() | Alterne ramos ou restaure arquivos de árvore de trabalho - retorna na última branch |
| [`git-checkout -`]() | Alterne ramos ou restaure arquivos de árvore de trabalho - retorna na última branch |
| [`git-merge --no-ff`]() | Junte dois ou mais históricos de desenvolvimento juntos Com `--no-ff`, crie um commit de mesclagem em todos os casos, mesmo quando a mesclagem pudesse ser resolvida como um avanço rápido. |
| [`git-stash`]() | Esconde as mudanças em um diretório de trabalho sujo |
| [`git stash list`]() | As modificações armazenadas por este comando podem ser listadas `git stash list` |
| [`git stash show`]() | As modificações armazenadas por este comando podem ser inspecionadas `git stash show` |
| [`git stash apply `]() | As modificações armazenadas por este comando podem ser restauradas (potencialmente em cima de um commit diferente) com `git stash apply` |
| [`git stash pop `]() | Remova um único estado de stash da lista de stash e aplique-o no topo do estado da árvore de trabalho atual, ou seja, faça a operação inversa de `git stash push`. O diretório de trabalho deve corresponder ao índice. |
| [`git checkout -- fileName`]() | Remove arquivo não adicionado |
