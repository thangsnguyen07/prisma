# How to run project

```bash

# Remove previuos volumes related (optional).
docker volumes prune ( make sure not any useful volume)

# Start the docker containers
docker-compose up -d 

# First time installation of packages
npm install

npx prisma init

npx prisma db pull

npx prisma db push

```

