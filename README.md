# Meu primeiro git

## git init= inicia o repositorio git vazio
`git init`
## git add= preparar para o commit
para enviar um unico arquivo `git add <nome do arquivo>` para enviar todos `git add .`
## git status= mostra o detalhes do status do projeto
para ver o status do projeto com branch atual a serem commitados digite `git status`
## git commit= adicionar um comentario ao commit da versão a ser enviada 
para adicionar um comentário a versão (mudanças) a serem enviadas digite `git commit -m "mensagem aqui"`
e para preparar e fazer o commit das mudanças ao mesmo tempo evitando o uso do `git add`
é só adicionar a flag `-am` onde o 'a' substitui o git add e o 'm' para representa a mensagem do comentário, por exemplo: `git commit -am "sua mensagem aqui"`
## git remote= adiciona o repositorio remoto do git
para adicionar um ramo do repositorio remoto ao seu projeto local digite `git remote add origin <url do repositorio>`
