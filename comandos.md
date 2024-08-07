git --version

// verifica a versão do git que está no seu computador

$ git --config user.name "xxx"
$ git --config user.email "xxx"

// configura o seu git

ls -al ~/.ssh

// verifica se existe chave ssh

ssh-keygen -t ed25519 -C "xxx"

// adiciona uma chave

eval "$(ssh-agent -s)"

// guarda as chaves geradas

ssh-add ~/.ssh/id_ed25519

// adiciona a sua chave no agente

clip < ~/.ssh/id_ed25519.pub

// copia sua chave para o CTRL + V

cat ~/.ssh/id_ed25519.pub

// mostra a chave que foi gerada

git init

// inicia o git

git add

// adiciona um arquivo

git branch

// cria branch

git checkout

// altera a branch que você está

git checkout -b xxx

// cria a branch e acessa ela