# Docker-nuxt-flask
Nuxt application with Flask in Docker container

# Start Container
docker-compose up -d
docker-compose exec web bash

# init nuxt in container
create-nuxt-app ./
npm run dev
