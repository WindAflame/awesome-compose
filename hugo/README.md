Template of Hugo project

## How to use this project ?

For use this template, you need to follow these instruction :
  - Clone this project
  - Update variables includes in [.env](./.env) file if needed.
  - Use Makefile to interact with hugo
  - Work in `$WORKDIR` directory.

## Fonctionnality
### Create a project

Request a `hugo new` through docker-compose with configuration from `.env` file.

```
make new
```

### Build project

Request a `hugo build` through docker-compose with configuration from `.env` file.

```
make build
```

### Serve project locally

Request a `hugo serve` through docker-compose with configuration from `.env` file.

```
make serve
```

### Clean 

Clean docker-compose associated with this project.

```
make clean
```