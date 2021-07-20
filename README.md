[*https://git-school.github.io/visualizing-git/*](https://git-school.github.io/visualizing-git/)

`git config --global user.name "Seu nome aqui"`

`git config --global user.email "seu@email.aqui"`

`git init` *inicializar o git em um projeto*

`git init --bare` *contem somente as alteracoes, seria um "servidor"*

`git status` 

`git add <file>` *adicionar arquivo*

`git add .` *adicionar todos arquivos*

`git commit -m "Criando arquivo index.html com lista de cursos"`

`git log` *historico de alteracoes*

`git log —oneline`  *historico resumido em uma linha*

`git log -p` *mostra as modificacoes que foram feitas no codigo*

- `git log --help`  [*https://devhints.io/git-log](https://devhints.io/git-log)  para mais tipos de logs*
- [**gitignore.io**](https://www.toptal.com/developers/gitignore) *site para criar .gitignore personalizados*
- `dotnet new gitignore` *em projetos .NET*

`git remote`  *lista os repositorios remotos nesse projeto*

`git remote -v` *mostra o endereco do repositorio remoto*

`git remote add <nome> <local>`  *adicionar repositorio remoto*

`git remote rename <nomeAtual> <nomeNovo>` *alterar nome de um remote*

`git clone <local> <nome>` *clona os dados de um repositorio*

`git push <nomeRemote> <branch>` *envia os dados para o repositorio*

`git pull <nomeRemote> <branch>` *traz os dados do repositorio*

`git branch`  *lista as branch*

`git branch <nome>` *cria uma nova branch*

`git checkout <branch>` *troca de branch* 

`git checkout -b <nome>`  *cria uma branch e ja troca pra ela*

`git merge <branch>`  *junta os trabalhos e gera um merge commit*

`git rebase <branch>` *aplica os commits de outra branch na branch atual.*

`git checkout — <file>` *descarta alteracoes antes do commit*

`git reset HEAD <file>` *remove esse arquivo da lista a ser commitada*

`git revert <hashCommit>` *cria um commit desfazendo o commit do hash*

`git stash`  *salva o trabalho para depois*

`git stash list`  lista todos trabalhos salvos

`git stash apply <numeroStash>` *aplica o trabalho salvo*

`git stash drop <numeroStash>`  *remove o trabalho salvo no stash*

`git stash pop`  remove o ultimo dado salvo do stash, traz e aplica 

`git checkout <hashCommit>`  *volta o codigo pra versao desse  commit*

- *para continuar commitando nesse estado eh necessario criar uma nova branch*

`git diff` *vemos alteracoes em nossos arquivos que nao foram adicionados para commit*

`git diff <hashCommit>..<hashCommit>`  *diferenca entre 2 commits*

`git tag`  *lista todos tags desse repositorio*

`git tag -a <nome> -m "mensagem"` *cria uma versao do teu projeto*
