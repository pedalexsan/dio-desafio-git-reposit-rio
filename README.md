# O Git


&nbsp;

Git é o sistema de controle de versão open source mais usado no mundo atualmente! Ele é usado para controlar o histórico de alterações de arquivos e principalmente de projetos de desenvolvimento de software. Ele permite mais flexibilidade no fluxo de trabalho, segurança e desempenho. 
&nbsp;



## Principais Comandos do Git

Para configurar nova instalação - usuário:

```sh
git config --global user.name "(colocar usuário)"
git config --global user.email "(colocar email)"
```

**Para criar um novo projeto de Git.**

Cria um novo repositório em branco.
```sh
git init 
```
Para dar nome específico
```sh
git init (nome do repositório)
```
**Criar diretório, navegar:**
```sh
mkdir (nome rep)
```
Listar diretórios
```sh
dir 
```
Navegar para
```sh
cd (nome rep)
```
Retomar diretório anterior
```sh
cd .. 
```
Visualizar o caminho de diretório completo
```sh
pwd
```
Mover de para outro repositório
```sh
mv (nome) ./ (nome repositório) 
```
Para criar uma cópia exata de um repositório já existente.
```sh
git clone
```
Para adicionar arquivos especificados de código ao seu repositório. 
```sh
git add *
```
Adiciona um arquivo específico ao repositório
```sh
git add (_arquivo) 
```
Para remover arquivos da pasta.
```sh
git rm (nome)
```
Para executar o *commit* dos arquivos que foram *add* e cria uma revisão com um *log*.
```sh
git commit
git commit -m "com comentário"
```
**Para criar, renomear, excluir ou alternar uma ramificação.**
Lista todas as ramificações no seu repositório
```sh
git branch --list 
```
Cria nova ramificação
```sh
git branch (nome) 
```
Exclui a ramificação de forma segura.
```sh
git branch -d (nome) 
```
Exclui a ramificação mesmo que tenha mudanças não mescladas.
```sh
git branch -D (nome) 
```
Renomeia a ramificação atual
```sh
git branch -m (nome) 
```
Trocar de uma ramificação para outro.
```sh
git checkout (nome) 
```
Para uma conexão entre o repositório local e um remoto
```sh
git remote add (nome) (url)
```
lista repositórios remotos cadastrados
```sh
git remote -v 
```
Para upar modificações para um repositório remoto já conectado com o *remote*
```sh
git push -u (nome) (nome do branch)
```
Para baixar as mudanças criadas por outros usuários do projeto.
```sh
git fetch 
```
Para baixar o conteúdo do que foi alterado no repositório remoo para repositório local e atualiza seu conteúdo para a última versão.
```sh
git pull (url)
```
**Para armazenar temporariamente seus arquivos modificados em um esconderijo.**
```sh
git stash
```
Listas os esconderijos
```sh
git stash list 
```
Quando for aplicar o conteúdo a um *branch*
```sh
git stash apply  
```
Para integrar - mesclar as mudanças de dois *branches* diferentes em um único. Precisa ser iniciado a partir de um *branch* já selecionado.
```sh
git merge (nome do branch) 
```
Para determinar qual usuário realizou qual mudança em um determinado arquivo.
```sh
git blame (nome arquivo)
```
**Para ajuda**
```sh
git blame (nome arquivo)
```
Ajuda específica
```sh
git help (nome comando
```
