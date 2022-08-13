# Entretenimento - API
#### _Uma API para salvar seus filmes e séries favoritas_

## Features

- Criar, editar, deletar e requisitar usuários
- Criar, editar, deletar e requisitar filmes
- Criar, editar, deletar e requisitar séries
- possibilidade de trabalhar direto no Docker, sem necessidade de intalação na máquina
- Com autenticação

## Tech

Entretenimento - API | utiliza vários recursos para o projeto funcionar perfeitamente, são eles:

- [node.js] - servidor aplicacional para camada de serviços
- [Express](https://expressjs.com/) - Framework
- [Sequelize](https://sequelize.org/) - Manipulção de Dados (ORM)
- [markdown-it]
- [rest API] - Arquitetura aplicacional 
- [docker](https://www.docker.com/) - Serviço de contentenrização
- [mysql](https://www.mysql.com/) - servidor de base de dados
- [jwt](https://jwt.io/) - serviço de autenticação e autorização
- [OpenAPI 3.0](https://swagger.io/specification/) - Formato de 
- [postman](https://www.postman.com) - consulta e testes dos recursos

## Installation

Entretenimento-API requer [Node.js](https://nodejs.org/)  to run.

Instalação das dependencias necessárias

```sh
npm i
```
Para ambiente de desenvolvimento:

```sh
npm start
```

## Plugins

Obtenha a API nos seguintes repositórios

| Plugin | Repositório |
| ------ | ------ |
| GitHub | [https://github.com/webmomento2/inf-22-dw2-g21.git](https://github.com/webmomento2/inf-22-dw2-g21.git) |
| Postman | [https://www.getpostman.com/collections/eb816fd335ca044821c3](https://www.getpostman.com/collections/eb816fd335ca044821c3) |


## Docker

Uma maneira fácil de correr a aplicação e testá-la sem necessidade de instalação

Por padrão, o Docker irá expor a porta 3000, então altere isso dentro do
Dockerfile se necessário. Quando estiver pronto, basta usar o docker-compose.yml para construir a imagem.

no ficheiro .env:
- descomente a linha DB_HOST=app_bd e comente DB_HOST=localhost
- descomente a linha DB_DATABASE=app_bd e comente DB_DATABASE=app1

comando para executar:
```sh
docker compose up
```
Isso criará a imagem e extrairá as dependências necessárias.

Verifique a implantação navegando até o endereço do servidor em seu navegador preferido.

```sh
127.0.0.1:3000
```

#### DockerHub

Outra maneira de utilização com o Docker é utilizar as imagens direto do repositório.
Utilzando os seuintes comandos:

| Plugin | Repositório |
| ------ | ------ |
| APP | docker pull a036020/inf-22-dw2-g21:5.7-oracle |
| MYSQL | docker pull a036020/inf-22-dw2-g21:latest |


## License

MIT

**Free Software, Hell Yeah!**


