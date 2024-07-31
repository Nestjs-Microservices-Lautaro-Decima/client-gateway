# Client Gatewat

El gateway es el punto de comunicación entre nuestros clientes y nuestros servicios.
Es el encargado de recibir las peticiones, enviarlas a los servicios correspondientes y devolver la respuesta al cliente.

1. Crear un archivo `.env` basado en el `.env.example`

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Install NATS

`docker run -d --name nats-main -p 4222:4222 -p 6222:6222 -p 8222:8222 nats`
