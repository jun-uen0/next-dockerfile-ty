## Dockerized Next.js app
- Next.js app dockerized by image and compose file
- You can create Next.js "Welcome page"

## Version
docker: 20.10.12
docker-compose: 1.29.2

### Getting Started
- Create Next.js app with docker-compose run
```shell
docker-compose run --rm app sh -c "npm install create-next-app && npx create-next-app hello-next --ts"
```
--ts: option for using Typescript

## Run app
- Run the container with compose file
```shell
docker-compose up
```
Put `-d` after the command if you want to run in background
Access to http://localhost:3000