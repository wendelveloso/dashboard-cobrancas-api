![](https://i.imgur.com/xG74tOh.png)

# Desafio Final- PARTE BACKEND

# Variaveis de ambiente para iniciar a api (vai utilizar o arquivo .env)
O projeto utiliza variaveis de ambiente na qual você pode utilizar um banco de dados local ou online (desaful values podem ocorrer mudanças dependendo do seu banco de dados):

| Name                          | Description                         | Default Value                                  |
| ----------------------------- | ------------------------------------| -----------------------------------------------|
|PORT           | Porta que a api vai receber            | "3000"      |
|DB_HOST           | host do banco de dados            | "*"      |
|DB_PORT           | porta do banco de dados           | "5432"      |
|DB_USER           | usuario do banco de dados            | "*"      |
|DB_PASS           | senha do banco de dados            | "*"      |
|DB_NAME           | nome do banco de dados            | "*"      |
|JWT_HASH           | jason web token hash            | "testehashjwt"      |

# Pre-requisites
- Instalar [Node.js](https://nodejs.org/en/) version 8.0.0
- Configurar o arquivo .env com base no arquivo .env.exemple com as suas respectivas variaveis de ambiente  [.env](https://www.npmjs.com/package/dotenv)

# Getting started
- Clone o repositorio (https://github.com/cubos-academy/desafio-front-modulo4-next-parteBack-v3-resolucao)
```
- Install dependencies
```
cd projeto

```
npm install
```
- Build and run the project
```
npm run start ou npm run dev
```
  Navigate to `http://localhost:3000`
