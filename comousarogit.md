------Como Colocar os arquivos no GitHub usando o Git------


git init - repositório git vazio

git add nomedoarquivo - manda os arquivos para a área de stade (chama dos fundos para o "palco"). No caso usaremos "git add Readme.md"

git status - mostra o status, e as mudanças a serem "comitadas"

git commit -m "mensagem do commit" - enviaremos a primeira mensagem. No caso, usaremos "git commit -m "primeiro commit" "

git branch -M "main" - renomear

git remote add origin https://github.com/cursoidosos/projeto_curso_idosos.git - Adicionando o repositório local com o do GitHub, criando uma conexão com ele

git push -u origin main - adicionar pastas

___________________________________________________________________

Ordem: 
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/cursoidosos/projeto_curso_idosos.git
    git push -u origin main

__________________________________________________________________

Pra quem receber o Erro "Fatal: protocol 'https' is not supported" após o comando "git push -u origin main". Isso pode ter acontecer pela forma como colou o comando no git bash. Resolvi digitando o comando completo da seguinte forma: "git remote set-url origin 'link do meu repositório' (sem as aspas). O set-url vai sobrescrever a anterior. Aí pode manda o git push novamente

__________________________________________________________________

Como salvar as alterações?

    Abrir GitBash
    clear - limpar
    git add . - o ponto vai dizer que são todos os arquivos ali na pasta. Se quiser só um arquivo em específico coloco o nome do arquivo, como anteriormente
    git status
    git commit -m "criação do projeto"
    git push origin main - sem o remote pq só criamos a conexão uma vez
    Recarregar a página do GitHub
    


