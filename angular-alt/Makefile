.PHONY: build serve clean
include .env

new:
	compose --env-file .env run --rm web ng new \
	--package-manager ${PACKAGE_MANAGER} \
	--style ${STYLE_EXTENSION} \
	--directory ./ \
	--skip-git true \
	${PROJECT_NAME}
build:
	compose --env-file .env run --rm web ng build
serve: 
	compose --env-file .env up
clean:
	compose down