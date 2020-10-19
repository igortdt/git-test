## ADD git ao projeto
    git init

## Diretorios e arquivos ignorados 
    - criar arquivo .gitignore dentro do projeto
    - dentro do arquivo informar as pastas e aquivos que nao seram incluidos no controle de versao
    - Ex: node_modules

## ADD no reopsitorio locales   
    git add *  -- adciona todos os arquivos que ainda nao foram adcionados
    git add index.js -- add apenas o arquivo index.js arqu

## Realizar commit
    git commit - m "chore: commit inicial" -- onde o "m" é o paramentro da mensagem do commit
    OBS padrao das mensagens do commit:
        chore - iniciado uma nova funcionalidade, por exmplo
        fir - correção de bus
        feature - funcionalidade concluida

## Exibir arquivos q ainda nao foram incluidos no reopsitorio local
    git status

## Estabelecer conexão do projeto git local com o reopsitorio do github
    git remote add origin https://github.com/igortdt/git-test.git            

## Sincronizar projeto git local com o reopsitorio do github    
    git push -u origin master -- na primeira vez
    git push -- nas demais vezes

## Clonar um reopsitorio    
   git clone https://github.com/igortdt/git-test 

## Ver logs de commits
    git log

## Criar uma ramificacao
    git checkout -b feature/nova-func    

## Alterar ramificacao/branch
    git checkout master -- onde master é o nome da branch

## Sincronizar projeto online com o reopsitorio local com 
    git pull

## Sincronizar branch atual com a master
    git merge master    

