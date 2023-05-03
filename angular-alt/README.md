Template of Angular project

## How to use this project ?

For use this template, you need to follow these instruction :
  - Clone this project
  - Update variables includes in [.env](./.env) file if needed.
  - Use Makefile to interact with angular
  - Work in `$WORKDIR` directory.

## Fonctionnality
### Create a project

Request a `ng new` through docker-compose with configuration from `.env` file.

```
make new
```

### Build project

Request a `ng build` through docker-compose with configuration from `.env` file.

```
make build
```

### Serve project locally

Request a `ng serve` through docker-compose with configuration from `.env` file.

```
make serve
```

### Clean 

Clean docker-compose associated with this project.

```
make clean
```

### Deploy project

*TODO: Not implemented yet*