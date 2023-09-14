# nlw-upload-ia-api
Aplicação que possibilita realizar upload de videos e por meio de IA, criar automaticamente títulos chamativos e descrições com um boa indexação.
 
## :computer: Tecnologias
Esse projeto foi desenvolvido utilizando:

1. Nodejs.
2. TypeScript.
3. Prisma.
4. OpenAi.
5. FFmpeg.

<h1 align="center">Vamos começar!!</h1>
 
## :rocket: Baixando o projeto: 
```javascript
https://github.com/jujulio/nlw-upload-ia-api.git
```

### :rocket: Configuração inicial
1. Necessário baixar e rodar o Front-end.
   [Web](https://github.com/jujulio/nlw-upload-ia-web.git)
2. Necessário criar uma conta na OpenAI e gerar uma api-key.
   [OpenAI](https://openai.com/)
3. Necessário alterar o arquivo "exemple-env" para ".env" e colocar o valor da api-key na chave.
4. Necessário instalar as seguintes extensões no VScode: DotENV, REST Client e prisma.
   

### :package: Rodar as APIs

```console
# Instalar dependências:
$ "pnpm i"

# Criar o banco de dados
$ "pnpm prisma migrate dev"
$ "pnpm prisma db seed"

# Verifica se foi criado corretamente o banco
$ "pnpm prisma studio"

# Rodar a aplicação
$ "pnpm run dev"

```

 ### :book:Licenças
 Lançamento em 2023 para estudos.
 Feito com :purple_heart: by [Julio César](https://github.com/jujulio)
 
 Dê um: star: se este projeto te ajudou!

