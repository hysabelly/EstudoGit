# EstudoGit
Estudos do Git e Gihub para aplicação dos códigos.

## Copiar um repositório
- git clone e o link do repositório

## Criar um novo repositório local
- git init

## Mudanças locais
- git init
- git diff
- git add . 
- git add . -p <file>
- git commit -a
- git commiy 
- git commit -emend
  
## Histórico
- git log
- git log - p <file>
- git blame <file>
  
## Branches
  
  ![image](https://user-images.githubusercontent.com/90413604/163991740-4cecd22b-8431-420d-a8ea-1afa264bfac3.png)
  
## Atualizar e republicar

  ![image](https://user-images.githubusercontent.com/90413604/163991912-ebe80a2b-8189-4c28-afb3-90638fca65d9.png)

## Desfazer
  
  ![image](https://user-images.githubusercontent.com/90413604/163992010-d4584955-d528-4b71-9edc-b34a9ee2a1f1.png)
  
## Fundir e Rebase
  
  ![image](https://user-images.githubusercontent.com/90413604/163992064-109263d1-ad95-407e-b5f5-545020c19533.png)
  
# Usado na sala de aula
Passo a passo para criar e fazer commit:
  
  Configuração Inicial:
- cd Desktop
- mkdir NomeNome
- cd NomeNome
- dotnet new console -o NomeNome
- code NomeNome
- git config --global user.name "hysabelly"
- git config --global user.email hysabellynunes@gmail.com
- se precisar do gitgnore escreve: "<file> não quer passar pro github"
- dotnet run pra rodar no terminal
- clear pra limpar o git bash

  Commit's e Github:
- git init
- git add .
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://NomeNomedoLinkdoGithub
- git push -u origin main
- git status
- git add NomeNome.extensão
- git commit -m "mensagem do commit"
- git push: ai vai abrir a página do login
  
