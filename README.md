<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest
## Description
[Bookmark]


## Installation
1. Install dependecies

```bash
$ yarn install
```
2. Run docker 

```bash
yarn db:dev:up
```

3. Run migrations 

```bash
yarn prisma:dev:deploy
```

4. Run the app
## Running the app

```bash
# development
$ yarn start

# watch mode
$ yarn start:dev

# production mode
$ yarn start:prod
```

## Test
```bash
# e2e tests
$ yarn test:e2e
```

## Stay in touch

- Author - [Bartosz Ostrowski](ostrowskibartosz85@gmail.com)


## License

Nest is [MIT licensed](LICENSE).
