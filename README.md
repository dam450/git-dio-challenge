# Desafio Git/Github

Repositório criado para o desafio de projeto da [Digital Innovation One](web.dio.me).

Para mais comandos consulte a [Wiki](https://github.com/dam450/git-dio-challenge/wiki) do projeto.

## ⚙️ Instalando o Git

Faça o download do instalado do git através do site oficial [https://git-scm.com/downloads](https://git-scm.com/downloads). 

Após a instalação execute o **git bash**, este é o *prompt* de comandos onde são executadas todas a funções do **git**. 

### 🔧 Configurando nome de usuário

No *prompt* do **git** execute o comando **git config** com os parâmetros **--global user.name** e seu nome de usuário, este nome será gravado globalmente para todo seus projetos.

> `$ git config --global user.name "meu nome"`

### 🪛 Configurando e-mail

Para configurar seu e-mail no **git**, no *prompt* execute o comando **git config** seguido dos parâmentros **--global user.mail** para definir o e-mail globalmente.

> `$ git config --global user.mail meu_email@exemplo.com.br`

## 🧬 Clonando repositórios com HTTPS

Utilizamos o comando **git clone** seguido da *URL HTTPS* do projeto.  
exemplo: 

> `$ git clone https://github.com/dam450/git-dio-challenge.git`

## 🔬 Consultando estado do repositório local

Utilize o comando **git status** para saber como está o estado atual do repositório. O comando retorna se 

> `$ git status`

## 🔏 Assinar git commits com chave GPG

Utilize a opção **-S** (s maiusculo) e o git vai usar sua chave GPG para assinar o commit. Se você tiver adicionado sua chave publica GPG a sua conta GitHub seus commits vão aparecer como verificados.

 > `$ git commit -S -m 'mensagem de commit'`
 
 ### 🏷️ Commits assinados por padrão
 
 Adicione a opção git config `commit.gpgsign` a configuração para que todos os commits sejam assinados por padrão, sem a necessidade de informar a opção **-S**.
 
 > `git config --global commit.gpgsign true`

Para desbilitar execute o mesmo comando sinalizado com a opçao false

> `git config --global commit.gpgsign false`

### 🤔 Por que usar GPG?

O GnuPG também chamado de GPG (Gnu Privacy Guard), permite que os commits sejam criptografados e assinados impedindo que alguém se passe por você e insira alterações que possam comprometer o repositório.
> **Nota:** para utilizar assinatura GPG é preciso ter uma chave criada e adicionada a sua configuração com o comando `$ git config --global user.signingkey ID-DA-SUA-CHAVE-GPG`. Mais detalhes de como gerar e configurar sua chave GPG acesse a documentação GitHub no [link](https://docs.github.com/en/authentication/managing-commit-signature-verification/generating-a-new-gpg-key).

## 💡 Links úteis

- [Git Website](https://git-scm.com/) (Site oficial do git)
- [MarkdownGuide.org](https://www.markdownguide.org/) (Guia de referência gratuito e de código aberto que explica como usar o Markdown)

