# projeto-curso-git (treinando)

## Part 1
>- Para saber quais arquivos devem ser adicionado:
> *git status*

>- Como remover a origem do repositório remoto?
> *git remote rm origin*

>- Como monitorar os arquivos no repositório do Github?
> *git add*

## Part 2
>- *git add*:
> adiciona todos os arquivos modificados.

>- alterar o código:
> *git add* index.html e em seguida *git commit -m* 'minha alteração' e por fim, *git push*.

>- *git status*(após usar o commit de um arquivo alterado):
> o nome da branch que não tem alterações para serem commitadas.

>- significado da cor vermelha e verde após usar  *git status*:
> arquivo modificado e não rastreável - arquivo modificado e rastreável

>- *git log*:
> mostra o histórico de commits do reositório remoto e local.

>- depois de feito o commit quais dados aparecem no terminal?
> mostra todos os arquivos alterados, deletados ou adicionados, linhas alteradas e o id  commit.

### Historicos dos comandos usados na aula:

  mkdir projeto-curso-git  // criando directório

  cd projeto-curso-git  
  
  git init       
  
  git status  
  
  touch index.html  // criando o arquivo
  
  ls
  
  git status
  
  git add index.html // adicionando o arquivo no controle de versão
  
  git status
  
  git commit -m 'Meu primeiro commit'  // fazendo commit 
  
  git log   // mostra os commit feitos 
 
  cd projeto-curso-git
  
  git status
  
  git log
  
  ls
  
  clear
  
  git remote add origin https://github.com/Warleygomes/projeto-curso-git.git // adiciona o servidor remoto no local
  
  git push -u origin master   // publica ou sobe o projeto p/ o github
  
  git status
  
  git add index.html 
  
  git status
  
  clear
  
  git commit -m 'Adicionando estrutura html Inicial'  
  
  git log
  
  git push
  
  history
  
  
