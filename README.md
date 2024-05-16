# Como Subir Arquivos para o GitHub

Este guia ensina como subir arquivos para um repositório no GitHub, utilizando Git no terminal.

## Passos para Subir Arquivos

### 1. Crie um Repositório no GitHub

1. Acesse [GitHub](https://github.com) e faça login.
2. Clique no ícone de "+" no canto superior direito e selecione "New repository".
3. Dê um nome ao seu repositório.
4. Adicione uma descrição (opcional).
5. Escolha se o repositório será público ou privado.
6. Clique em "Create repository".

### 2. Inicialize o Repositório Localmente

- No terminal, navegue até o diretório do seu projeto e execute os seguintes comandos:

```bash
git init
```

### 3. Adicione os Arquivos ao Repositório Local

- Adicione todos os arquivos que você deseja subir para o GitHub:

```bash
git add .
```

### 4. Faça um Commit dos Arquivos

- Faça um commit inicial com uma mensagem descritiva:

```bash
git commit -m "Nome da Commit"
```

### 5. Conecte o Repositório Local ao GitHub

- No GitHub, você verá instruções para adicionar um repositório remoto. As instruções geralmente se parecem com isto:

```bash
git remote add origin https://github.com/...
```

### 6. Configure o Branch Principal

- Configure o branch principal como main (ou master dependendo da sua preferência):|

```bash
git branch -M main
```

### Dicas Adicionais

- Certifique-se de que o arquivo .gitignore está configurado corretamente para evitar subir arquivos desnecessários, como node_modules/ e arquivos de configuração sensíveis (.env).

```gitignore
node_modules/
.env
```

- Para verificar o status dos arquivos e commits, você pode usar:

```bash
git status
```

- Para visualizar o histórico de commits:

```bash
git log
```


Este `README.md` fornece um guia de como subir arquivos para um repositório no GitHub, incluindo os comandos Git necessários e dicas úteis.
