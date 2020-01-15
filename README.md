# :whale: Docker Node Express Mongo

A boilerplate and example of a Node.js, Express.js, MongoDB, Mongoose, and EJS application with Docker.

## :computer: Technologies Demonstrated

- Docker
- Node
- Express
- MongoDB
- Mongoose
- EJS

## :floppy_disk: Install

```sh
docker-compose up
```

View at localhost

## :whale: Docker

### Dockerfile

Docker can build images automatically reading the instructions from a Dockerfile. A Dockerfile is a text document that contains all the commands a user could call on the command line to assemble an image. Using docker build users can create an automated build that executes several command-line instructions in succession.

Dockerfile best practices [documentation](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/#examples-for-official-images).

### Docker Compose

Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration.

Docker Compose official [documentation](https://docs.docker.com/compose/).

#### Run

```sh
docker-compose up
```

:pushpin: add -d flag to run detached

#### Stop

`Ctrl + C`

#### Down

```sh
docker-compose down
```

#### Rebuild

```sh
docker-compose build
```

### Continue Learning

More examples can be found via Dockers official [documentation](https://docs.docker.com/samples/).

## :man_technologist: Author

- **Austin** - [austinbuilds](https://github.com/austinbuilds)
