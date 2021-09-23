# Ensinando a usar o Git e Github na prática

 ## O que você vai precisar
* Primeiro você precisa instalar o `GIT`

* [Link para instalar](https://git-scm.com/downloads)

* Criar uma nova pasta e dentro dela criar um arquivo `.md` que significa markdown uma linguagem de `marcação`

* Para isso você precisara de uma IDE exemplo de uma é o VSCODE , para criar o novo arquivo `README.md`
  

  ## Principais Comandos GIT

  * `git init` Para inicializar o repositório

  * `git status` Da o status da branch e tambem do arquivo em espera pra ser Commitado

  * `git add README.md` Coloca o arquivo na área de `espera` para depois ser Commitado

  * `git add .` Coloca todos os arquivos da pasta em espera para ser Commitado

  * `git commit -m "primeiro commit"` Para de fato dar o commit local para depois dar `push` para seu repositório e entre aspas ali  é o comentario

  * `git branch -M "main"` Para alterar o nome da branch principal de `master` para `main` (isso é uma boa prática atualmente recomendada) mas você pode alterar para o nome que desejar

  * `git checkout -b "nome da branch"` Cria uma branch nova e vai direto para ela 

  * `git checkout nomedabranch` Vai até a branch apontada 

  * `git remote add origin <link do repositório>` Faz Conexão do repositório local com o repositório github 

  * `git clone LINK DO REPOSITORIO` É usado para clonar um repositório para sua máquina  

  * `cd NOMEDAPASTA` Ir para a pasta apontada

  * `git pull` Serve para puxar para sua máquina o arquivo junto com a alteração

  * `git merge NOMEDABRANCH` Juntar arquivo de um branch com a outra
  
