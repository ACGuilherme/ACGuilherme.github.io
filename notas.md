Linhas de Comando
-------------------

Linhas de Comando (CLI)
--------------------------

° Interagir com o Computador através do texto
    Comando começando com $ (Unix) ou > (win)

° Unix (Mac e Linux) vs Windows    
    Bash e Zsh (Unix) | CMD e PowerShell (Windows)

° https://ss64.com

--------------------------------------------

Movimentar (Bash)
----------------------

° $ cd sites
    Move para a pasta sites

° $ cd ..
     Move para a pasta sites dentro do Desktop

° $ cd ~
    Move para o diretório principal do sistema / home

° $ clear 
    Limpa a tela

--------------------------------------------

Listar e Criar (Bash)
------------------------

° $ ls
    Lista diretórios e arquivos

° $ ls -all
    Lista diretórios, arquivos, invisíveis e detalhes

° $ mkdir site
    Cria o diretório site

° $ touch index.html
    Cria o arquivo index.html

---------------------------------------------

Remover (Bash)
--------------

° $ rm index.html
    Remove o arquivo index.html
  
° $ rm -r site
    Remove o diretório site e todos os arquivos dentro dele

° seta para cima / baixo
    Acessa o comando anterrior

° tab
  Auto-completa o comando

  -------------------------------------------------

  NPM e Cleancss
  -------------------

  NPM
  
° Gerenciador de pacotes
    Permite instalarmos diferentes programas e versões utilizando o comando $ npm

    https://www.npmjs.com/

° Instalar Globalmente
    $ npm install -g NOMEDOPACOTE

° Remover Globalmente
    $ npm remove -g NOMEDOPACORE

-----------------------------------------------------

Clean CSS CLI
----------------

Programa de linha de comando (CLI) utilizado para otimizar o CSS (diminuir o tamanho e concatenar diferentes arquivos em um único).

° clean-css-cli
    https://www.npmjs.com/package/clean-css-cli

    $ npm install -g clean-css-cli

° USO
    cleancss -o style.min.css style.css

------------------------------------------------

Git
-----

° Git
    Sistema de controle de versões. Facilita o trabalho em equipe e controle de mudanças entre arquivos e diretórios.

° Github
    Plataforma online de hospedagem para repositórios Git. Existem outras como GitLab e Bitbucket.

Git Setup
-----------

° Instalar o Git
    https://git-scm.com/

° Github
    Criar conta: https://gitub.com/

° Configurar Nome
    $ git config --global user.name "Seu Nome"

° Configurando Email
    $ git config --global user.emal "email@gmail.com"

Git Comandos
----------------

° $ git init
    Inicia um repositório

° $ git add style.css
    Adiciona o arquivo style.coss ao index do git. Com o '$ git add -a', adicionamos todos os arquivos.

° $ git status
    Mostra os arquivos que tiveram mudanças.

° $ git commit -m 'Descrição'
    Irá fazer o commit do código adicionado com uma mensagem

Criar Repositório no Github
---------------------------------

° Novo Repositório
    https://github.com/new

° Adicionar diretório remoto
    $git remote add origin
    https://github.com/seuusuario/seurepositorio.git

° Push do primeiro commit
    $ git push -u origin main

° Se for a sua primeira vez
    Uma tela de login irá aparecer, utilize os dados da sua conta Github.

Mais Git
---------

° .gitignore
    Lista de arquivos que não devem ser manipulados pelo git. node_modules é um exemplo.

° Commit sem texto
    Ao usar o git commit você entra no modo completo de comentário, com um editor de texto direto na linha de comando. Utilize 'esc + :wq' para sair do mesmo.

Github Pages
-------------

° Criar repositório
    O nome deve ser 'seuusuario.github.io

° HTML Simples
    O site só funcionará em html/css/js simples, sem linguagem de servidor

° Qualquer projeto
    Qualquer projeto poderá ter uma página para o mesmo. Vá em Settings > GitHub Pages > selecione master branch e salve. E acesso seuusuario.github.io/repositorio/