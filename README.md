# Prova de Programação Avançada para Web

## Como usar

Abra cada uma das pastas separadamente no Visual Studio Code, ou sua IDE/plataforma de preferência e siga as instruções abaixo:

---

## Pasta **Back-TrabWebAvan-b2**

### 1. Configure no Inicio, irá te Ajudar

Primeiro, Crie um arquivo chamado ".env" e escreva o seguinte texto dentro dele:

```
  DATABASE_URL=file:./dev.db
  GROQ_API_KEY=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
```

### 2.Instale as Dependências Necessárias

Em seguida, abra o terminal e digite:

```
npm install
```

### 3. Para Executar o Projeto

Você pode executar o projeto através do código:

```
npm run build
```

Se você estiver desevolvendo, o ideal é que, ao invés do `npm run build`, o código usado seja:

```
npm run dev
```

### 4. Sobre a Resolução de erros

Os erros podem estar relacionado ao PrismaORM, por esse motivo, uma forma de resolvê-los é criando novamente o banco de dados:

```
 npx prisma migrate dev --name init
```

### 5. Instale as Extensões do VSCode recomendadas para o desenvolvimento (VSCode):

```
{
    "recommendations": [
        "vscode-icons-team.vscode-icons",
        "esbenp.prettier-vscode",
        "prisma.prisma",
        "Prisma.prisma-insider"
        "rangav.vscode-thunder-client"
        "mikestead.dotenv"
        "qwtel.sqlite-viewer"
    ]
}
```

---

## Pasta **Front-WebAvan-b2**

### 1. Instale as Dependências Necessárias

Primeiro, abra o terminal e digite:

```
npm install
```

### 2. Para Executa o Projeto

Em seguida, você pode executar o projeto através do código:

```
npm run web
```

---

## Considerações finais

1. Cada uma das pastas possui um arquivo **README.md** próprio com instruções e passo-a-passo de como o projeto foi desenvolvido, porém, o projeto foi feito para funcionar seguindo apenas as instruções deste arquivo, que está fora das pastas.
2. Os arquivos devem ser executados na ordem **Back-TrabWebAvan-b2** > **Front-WebAvan-b2** para funcionar da maneira correta, sem erros.
3. Instalar as extensões PrismaORM e dotenv antes de começar a executar o código da API, É DE EXTREMA IMPORTÂNCIA para evitar transtornos.

```

4. Caso queira abrir as duas pastas é possível usando o VS Code, mas é Importante que uso terminais diferentes para rodar.
