
# DIO | Resumos Git e GitHub

Repositório para armazenar resumos sobre Git e GitHub do curso de Vesionamento de código com Git e GitHub da [Digital Innovation One](https://www.dio.me).

## 📚 Documentação
- [Documetação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/)
- [Criar um Readme](https://readme.so/pt/editor)

## 💻 Comandos do terminal
- ctrl+l: limpa o terminal
- clear: limpa terminal.
- pwd: exibe diretório atual
- mkdir "nome.diretorio"
- cd "nome.diretorio": entra no diretório
- cd ..: volta um diretório
- ls: lista arquivos do diretório
- cat "nome.arquivo": exibe conteúdo do arquivo
- touch nome-arquivo.xx: cria um novo arquivo.
- echo conteúdo > .nome-arquivo: cria um arquvivo com o nome escolhido com o conteúdo antes do sinal >.
- rm -rf .git: remove o repositório git de uma pasta.


## 👩‍💻 Comandos específicos para o git
- **git config --global user.name "xxx":** configurar nome no ambiente global. (ao invés de global poderia usar system ou local)
- **git config --global user.email "zzz":** configurar o e-mail global.
- **git config init.defaultBranch:** para verificar nome da brach padrão. O meu estava como master.
- **git config --global init.defaultBranch main:** para renomear a branch padrão como main no ambiente global.
- **git init:** inicia um diretório .git que está oculto
- **git clone nome.url novo.nome:**  copiar nome da url no GitHub. Clona pasta do github. O novo.nome é opcinal.
- **git remote -v:** mostra o repositório remoto vinculado.
- **git remote add origin url**: conecta o local ao remoto criado no github
- **git status:** mostra staus commit e untracked files.
- **git add nome-arquivo.xx**: identifica os arquivos não rastreados e prepara para o primeiro commit.
- **git log:** mostra as iformações de todos os commits.
- **git commit -m "nome-do- commit":** cria o novo commit (versão).
- **git restore nome-arquivo.xx:** restaura última versão e descarta tudo que foi feito após o último commit.
- **git commit --amend -m"novonome":** muda o nome do último commit.
- **git reset --soft/mixed/hard codigo-commit-para-retornar:** reseta e retorna a um commit. Ficar atento as opções.
- **git reflog:** mostra a lista de alterações.