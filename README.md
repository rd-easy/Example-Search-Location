## Example Search Location (typeorm)
- Buscar "dados" de usuários próximo a localização do usuário atual

___

### Objetivo 🌟

- Aprendizado

___

## Tecnologias ☘️

- [typeorm](https://typeorm.io)
- [Postgres](https://postgresql.org)
- [kartoza/postgis](https://hub.docker.com/r/kartoza/postgis)
- [Express](https://expressjs.com)
- [Typescript](https://typescriptlang.org/)

___

## Run 🏃‍♂️

[JSON-Insomnia](./.github/Insomnia-All_2021-10-16.json)

``` bash
# clone o projeto
git clone https://github.com/rd-easy/estudo-prisma.git
cd project
yarn

# execute o docker ou instale o postgres e crie a extensão 
docker run --name johnDoe -e POSTGRES_USER=johnDoe -e POSTGRES_PASSWORD=johnDoe -e POSTGRES_DB=johnDoe -p 5433:5432 -d kartoza/postgis

# termine de executar o projeto
yarn typeorm migration:run
yarn dev
```
