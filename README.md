# Instruções para o Workshop 

## Configurando o ambiente

### Passo 1 - Instalando um bom bloco de notas (VsCode)

Se você não tem o VsCode no seu computador, [instale-o aqui](https://code.visualstudio.com/)

### Passo 2 - Instalando o GIT

Se você ainda não tem o git no seu computador, [instale-o aqui](https://git-scm.com/downloads)
[Manual de instalação no Windows](https://dicasdeprogramacao.com.br/como-instalar-o-git-no-windows/)

Para instalar no **Ubuntu**, basta digitar as seguintes linhas no Terminal:

```bash
sudo apt-get update

sudo apt-get install git
```

### Passo 3 - Configure o GIT

Abra o terminal _ou bash do GIT_ e digite:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```

### Passo 4 - usando o Git

*Passo 4.1* - Abrir o Git Bash na pasta do curso que você criou (Windows) ou abrir o Terminal e navegar até a pasta do curso (Ubuntu)

*Passo 4.2* - Digite o comando abaixo para iniciar rum repositório local na sua pasta

```bash
git init
```

*Passo 4.3* - Criar um arquivo "helloWorldGit.txt" e digitar dentro "Hello, World!!"

*Passo 4.4* - Volte ao bash ou ao terminal e digite 

```bash
git status

No ramo master
No commits yet

 Arquivos não monitorados:
  (utilize "git add <arquivo>..." para incluir o que será submetido)

helloWorldGit.txt
 nada adicionado ao envio mas arquivos não registrados estão presentes (use "git add" to registrar)
```

*Passo 4.5* - Para que os arquivos comecem a ser monitorados, nós precisamos adicioná-los ao Git.  Para isso vamos usar o comando:

```bash
git add <nomeDoArquivo.extensão>
```

Em nosso caso, o comando será:

```bash
git add helloWorldGit.txt
```

*Para adicionar TODOS os arquivos, você pode usar o comando "git add ."*

Após isso, vamos checar de novo com "git status"

deve aparecer algo do tipo 

```bash
No ramo master

No commits yet

Mudanças a serem submetidas:
  (utilize "git rm --cached <arquivo>..." para não apresentar)

	new file:   helloWorldGit.txt

```

*O snapshot ja foi feito? Já tenho uma cópia da minha versão salva? NÃÃÃÃÃÃOOOOOO*

*Passo 4.6* - Vamos commitar e criar o snapshot do estado atual da nossa pasta. Para isso vamos usar o comando:

```bash
git commit -m "adicione aqui sua mensagem"
```

Em nosso caso, o comando será:

```bash
git commit -m "Meu primeiro commit: Olá Git!"
```

Se você consultar o status do git, deve aparecer uma mensagem dizendo que não há nada para ser commitado.

## Atividade

Agora você deve colocar novos documentos dentro da sua pasta (arquivos de texto, algum código que você usa, imagens) e criar um novo commit a partir do que você aprendeu até aqui.



## Usando o GitHub

### Passo 5 - Crie sua conta no GitHub

### Passo 6- Crie um novo repositorio no GitHub

```bash
git remote add origin https://link.do.repositorio
git push origin master
```

### Passo 7 - Alterando seus arquivos no GitHub

**Passo 7.1** - Abra seu arquivo no GitHub e clique no lápis para editar seu código e adicione uma linha de texto qualquer. Em seguida role a página para baixo e commit sua modificação com um comentário. 

**Passo 7.2** - abra o git bash ou o terminal na psta do curso use o comando *fetch* para atualizar o repositorio local e em seguida use o comando *pull* para baixar as atualizações.

```bash
git fetch
git pull
```
Abra o arquivo que você modificou usando o VsCode e veja suas mudanças.

