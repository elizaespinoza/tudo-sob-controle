# Tudo Sob Controle: Git e GitHub

Seja bem-vindo ao curso de Git e GitHub da Tudo Sob Controle! Neste curso, você aprenderá a usar o Git e o GitHub para controlar versões de arquivos e projetos. Você aprenderá a usar os principais comandos do Git, como commit, branch, merge, pull request, fork, clone, rebase, stash e tag. Você também aprenderá a usar o GitHub para hospedar seus projetos e contribuir com projetos Open Source.

## Materiais

Neste minicurso usaremos os seguintes materiais:

- [Git - guia rápido](https://rogerdudler.github.io/git-guide/index.pt_BR.html)
- Download Git: [Windows](https://git-scm.com/download/win), [Mac](https://git-scm.com/download/mac), [Linux](https://git-scm.com/download/linux)

## Exercícios

### Exercício 1: Fork e clone do repositório do curso!

1. Faça um fork do repositório do curso.

- Opções

> …or create a new repository on the command line

```bash
echo "# tudo-sob-controle" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:elizaespinoza/tudo-sob-controle.git
git push -u origin main
```

> …or push an existing repository from the command line

```bash
git remote add origin git@github.com:elizaespinoza/tudo-sob-controle.git
git branch -M main
git push -u origin main
```

2. Clone o repositório do curso.
3. Crie um branch com seu nome.
4. Faça um commit no branch com seu nome.
5. Faça um push do branch com seu nome.
6. Crie um pull request do branch com seu nome.

### Exercício 2: Personalize seu perfil no GiHub!

1. Crie um repositório no GitHub com o mesmo nome que seu nick no GitHub.

> Algumas dicas: [Como criar um README para o seu perfil do GitHub](https://www.alura.com.br/artigos/como-criar-um-readme-para-seu-perfil-github) e [Basic Syntax](https://www.markdownguide.org/basic-syntax/)

- Profile readme

```markdown
## Hi there 👋

<!--
**username/username** is a ✨ _special_ ✨ repository because its `README.md`
(this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
```

## FAQ

### O que é Git?

Git é um sistema de controle de versão distribuído, usado principalmente no desenvolvimento de software, mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo.

### O que é GitHub?

GitHub é uma plataforma de hospedagem de código-fonte com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo.

### O que é um repositório?

Repositório é um diretório onde ficam armazenados os arquivos de um projeto. Ele pode ser local, ou seja, armazenado na máquina do usuário, ou remoto, armazenado em um servidor.

### O que é um commit?

Commit é um comando do Git que salva as alterações feitas no repositório. Ele é usado para registrar o histórico de edições de um arquivo ou conjunto de arquivos.

### O que é um branch?

Branch é um comando do Git que cria uma ramificação do projeto. Ele é usado para criar uma cópia do projeto, onde é possível fazer alterações sem afetar o projeto principal.

### O que é um merge?

Merge é um comando do Git que une duas ramificações do projeto. Ele é usado para unir as alterações feitas em uma ramificação com a ramificação principal.

### O que é um pull request?

Pull request é um comando do Git que solicita a revisão de alterações feitas em uma ramificação. Ele é usado para solicitar a revisão de alterações feitas em uma ramificação antes de unir as ramificações.

### O que é um fork?

Fork é um comando do Git que cria uma cópia de um repositório. Ele é usado para criar uma cópia de um repositório, onde é possível fazer alterações sem afetar o repositório original.

### O que é um clone?

Clone é um comando do Git que cria uma cópia de um repositório. Ele é usado para criar uma cópia de um repositório, onde é possível fazer alterações sem afetar o repositório original.

### O que é um rebase?

Rebase é um comando do Git que une duas ramificações do projeto. Ele é usado para unir as alterações feitas em uma ramificação com a ramificação principal.

### O que é um stash?

Stash é um comando do Git que salva as alterações feitas no repositório. Ele é usado para salvar as alterações feitas em um repositório, sem fazer um commit.

### O que é um tag?

Tag é um comando do Git que cria uma tag no repositório. Ele é usado para criar uma tag no repositório, que pode ser usada para marcar versões do projeto.

### O que é um .gitignore?

.gitignore é um arquivo do Git que ignora arquivos e diretórios. Ele é usado para ignorar arquivos e diretórios que não devem ser versionados.
