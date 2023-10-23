Como clonar um repositório via git bash:

Criar um repositório manualmente no github.
Copiar o link da barra de endereços.
Abrir o Git Bash instalado na máquina.
Navegar utilizando os comandos cd e dir (caso necessário) para encontrar a pasta desejada para ser clonada.
Utilizar o comando git init para iniciar o processo.
git add nome_arquivo.extensao
git status (para ver se tem algum item com atualizações)
git commit -m "Escreva aqui um comentário sobre o commit"
git add remote origin 
git push
Como baixar os arquivos de um repositório:

Navegar com cd :/
Rodar o comando: git clone https://github.com/GuilhermeCarl/EstudosGit.git
Como visualizar os commits que foram realizados no meu repositório:

Opção 1: git log Opção 2: git log --oneline

Como baixar os arquivos atualizados de um repositório (caso que já tenho uma pasta que faz referência ao meu repositório): git pull https://github.com/GuilhermeCarl/EstudosGit.git

como voltar o meu código para um determinado commit:

git restore --source codigo_commit nome_arquivo_restaurar git push

como adicionar um arquivo para o meu repositório: git add nome_arquivo

como criar uma nova branch: git checkout -b desenvolvimento

como trocar para uma outra branch: git switch nome_branch

como fazer uma merge entre as branches: git switch main git merge desenvolvimento
