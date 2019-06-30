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

passo 4.1 - Abrir o Git Bash na pasta do curso que você criou (Windows) ou abrir o Terminal e navegar até a pasta do curso (Ubuntu)

passo 4.2 - Digite o comando abaixo para iniciar rum repositório local na sua pasta

```bash
git init
```

passo 4.3 - Criar um arquivo "helloWorldGit.txt" e digitar dentro "Hello, World!!"

Passo 4.4 - Volte ao bash ou ao terminal e digite 

```bash
git status

$No ramo master
$No commits yet
$
$ Arquivos não monitorados:
$  (utilize "git add <arquivo>..." para incluir o que será submetido)
$
$helloWorldGit.txt
$ nada adicionado ao envio mas arquivos não registrados estão presentes (use "git add" to registrar)
```

passo 4.5 - Para que os arquivos comecem a ser monitorados, nós precisamos adicioná-los ao Git.  Para isso vamos usar o comando:

```bash
git add <nomeDoArquivo.extensão>
```

Em nosso caso, o comando será:

```bash
git add helloWorldGit.txt
```

Após isso, vamos checar de novo com "git status"


