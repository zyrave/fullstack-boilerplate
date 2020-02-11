# Fullstack Boilerplate

```bash
  cd server
  cp .env.example .env
  cp .env.example .env.dev
  code .env # make necessary changes
  yarn
  docker container start postgres redis
  yarn dev
  cd ../web
  cp .env.example .env
  cp .env.example .env.dev
  code .env # make necessary changes
  yarn
  yarn dev
```

## With Docker [Experimental]

```bash
  cp .env.example .env
  cp .env.example .env.dev
  code .env # make necessary changes

  # Development
  docker-compose -f docker-compose.yml -f docker-compose.dev.yml up --build

  # Production
  docker-compose -f docker-compose.yml -f docker-compose.prod.yml up -d -- build
```
