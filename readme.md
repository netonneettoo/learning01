### Imagem 01:
* Primeiro, entei no github e criei um repositório

### Imagem 02:
* Depois que criei o projeto apareceu esses comandos, mas vamos usar só o que precisa
* Iremos precisar do link do projeto, vou usar o link SSH "git@github.com:netonneettoo/learning01.git" (Mas pode usar o HTTPS também)
* Também iremos usar o "git remote add origin git@github.com:netonneettoo/learning01.git"
* Também iremos usar o "git push -u origin master"
> Obs: Por motivos de convenção usaremos o branch "master" como default e não o branch "main" como sugere o github

### Imagem 03:
* Entrei no desktop pelo terminal e criei uma pasta com o mesmo nome do repositório usando o comando: "mkdir learning01"
* Depois entrei na pasta "learning01" e criei um arquivo chamado ".gitignore"
* Depois executei: git add .
* Depois executei: git commit -m 'primeiro commit'

### Imagem 04:
* Primeiro executei: "git remote add origin git@github.com:netonneettoo/learning01.git" pra linkar o git local com o repositório na web
* Executei: "git remote -v" pra listar os remotes que essa pasta local está vinculada
* Executei: "git push -u origin master"
> Obs.: Esse -u vincula seu branch master local ao branch master do repositório na web
