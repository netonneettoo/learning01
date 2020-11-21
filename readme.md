### Imagem 01:
* Primeiro, entei no github e criei um repositório

### Imagem 02:
* Depois que criei o repositório apareceu esses comandos, mas vamos usar só o que precisa
* Iremos precisar do link do projeto, vou usar o link SSH `git@github.com:netonneettoo/learning01.git` (Mas pode usar o HTTPS também)
* Também iremos usar o `git remote add origin git@github.com:netonneettoo/learning01.git`
* Também iremos usar o `git push -u origin master`
> Obs: Por motivos de convenção usaremos o branch `master` como default e não o branch `main` como sugere o github

### Imagem 03:
* Entrei no desktop pelo terminal: `cd ~/Desktop`
* Dentro do Desktop criei uma pasta com o mesmo nome do repositório: `mkdir learning01`
* Depois entrei na pasta: `cd learning01`
* Depois criei o arquivo .gitignore: `touch .gitignore`
* Depois adicionei os arquivos pro próximo commit: `git add .`
* Depois realizei o commit `git commit -m 'primeiro commit'`

### Imagem 04:
* Linkei o git local com o repositório na web: `git remote add origin git@github.com:netonneettoo/learning01.git`
* Listei os remotes que o repositório local está vinculado: `git remote -v`
> Obs.: O comando `git remote -v` foi usado apenas pra nível de informação
* Fiz o push usando o `git push -u REMOTE BRANCH_DEFAULT`: `git push -u origin master`
> Obs.: Esse -u vincula seu BRANCH local ao BRANCH na web
