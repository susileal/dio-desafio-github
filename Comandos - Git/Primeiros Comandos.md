# Primeiros Comandos - Git

## Iniciando o Git e criando um commit

1. git init - inicia o repositório do Git;
2. git add - move o arquivo e dá os primeiros comandos;
3. git add * - adciona tudo que foi modificado;
4. git add . - adiciona todas as modificações do repositório local para staged;
5. git commit -m "" - cria um commit.
6. git atatus - verifica se não tem nenhuma pendência no repositório;
7. git push oridin master - empurra do repositório local para o remoto.


Obs: Todo o comando do git tem que vim com a palavra git na frente.

## Como criar um repositório?

- Iniciando o repositório: $ git init
- Listando repositório: ls -a (lista pastas / arquivos ocultos)
- Entrando na pasta: cd .git/
- Configurando o git: git config --global user.email "" - enter - git config --global user.name

## Commit

São os objetos do Git que dão significados as alterações:
- autor;
- hora;
- alterações