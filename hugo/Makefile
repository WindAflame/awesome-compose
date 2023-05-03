.PHONY: build serve clean
include .env

new:
	docker-compose --env-file .env run --rm hugo new site .
build:
	docker-compose --env-file .env run --rm hugo build
serve: 
	docker-compose --env-file .env up
clean:
	docker-compose down