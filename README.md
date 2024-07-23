Notion do evento: https://narrow-beach-a00.notion.site/Full-Stack-Week-Guia-do-Evento-d62f1e9924744e37843e8b419fa6c3df

### Bibliotecas

-Prisma ORM de banco de dados

```
npm i prisma --save-dev
```

inicializando o prisma:

```
npx prisma init --datasource-provider postgresql
```

Fazer uma migrate depois de criar as tabelas roda para criar as tabelas

```
npx prisma migrate dev --name init_db
```

Para rodar as seed basta rodar o comando abaixo

```
npx prisma db seed
```

-Ts-node para criar as seed:

```
npm i -D ts-node
```

-Plugin para o prettier ajustar o código tailwindcss

```
npm i -D prettier prettier-plugin-tailwindcss
```

-Bibliotecas de componentes: Shadcn-ui

```
npx shadcn-ui@latest init
```
