# DIO | resumos git e github

Repositório para armazenar resmos do Git e GitHub
do curso Versionamento de Código com **Git** e **GitHub** da [Digital Innovation One](https://web.dio.me/track/coding-the-future-claro-java-spring-boot/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?autoplay=1).

## 📖 Documentação
- [Documentação do Git](https://git-scm.com/doc)
- [Documentação do GitHub](https://docs.github.com/pt/get-started)
- [Sintaxe Markdown do GitHub](https://docs.github.com/pt/get-started/writing-on-github)

## 👨‍💻 Resumos das aulas

| Aula | Conteúdo |
|------|----------|
| Gravando alterações no repositório local | Git init, add, commit      |
| Versionamento                            | Histórico, status e diff   |
| Repositório remoto                       | GitHub, push, pull, clone  |
| Branches                                 | Criação, troca e merge     |


### 📁 Criar uma pasta

```bash
mkdir nome-da-pasta
```

### 📂 Acessar uma pasta

```bash
cd nome-da-pasta
```

### 🗂️ Iniciar um repositório Git

```bash
git init
```

### 📄 Verificar o estado do repositório

```bash
git status
```

### ➕ Adicionando arquivos ao Stage
 Adicionar um arquivo específico:

```bash
git add nome-do-arquivo
```

#### Adicionar todos os arquivos:

```bash
git add .
```

### 📝 Criar um commit


```bash
git commit -m "mensagem descritiva do commit"
```

### 📜Histórico e alterações
 Ver histórico de commits

```bash
git log
```

#### Ver alterações antes do commit

```bash
git diff
```

### 🌿 Branches
 Criar uma nova branch

```bash
git branch nome-da-branch
```

#### Criar e trocar de branch ao mesmo tempo

```bash
git checkout -b nome-da-branch
```

### 🔗 Repositório Remoto (GitHub)
 Adicionar repositório remoto

```bash
git remote add origin https://github.com/usuario/repositorio.git
```

#### Ver repositórios remotos configurados

```bash
git remote -v
```

### ⬆️ Enviar alterações para o GitHub

```bash
git push origin main
```

#### *Primeiro push (quando necessário):*

```bash
git push -u origin main
```

### ⬇️ Atualizar repositório local

```bash
git pull origin main
```

### 📥 Clonar um repositório

```bash
git clone https://github.com/usuario/repositorio.git
```

### 🛑 Ignorar arquivos com .gitignore
Criar o arquivo:

```bash
touch .gitignore
```

#### Exemplo de conteúdo:

```bash
node_modules/
.env
*.log
```



## 🔎 Referências
- [Digital Inonovation One](https://web.dio.me/)

## 📖 Códigos






