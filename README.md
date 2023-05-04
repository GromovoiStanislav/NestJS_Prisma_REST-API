## NestJS - REST API with Prisma (e2e tests, argon2 instead of bcrypt)

```
npm i prisma -D
npm i @prisma/client
npx prisma init --datasource-provider sqlite
npx prisma migrate dev
npx prisma migrate dev --name init
```