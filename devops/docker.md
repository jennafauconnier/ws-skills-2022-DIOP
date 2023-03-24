# Docker

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- la création d'une image docker ✔️
- l'éxécution d'un container ✔️
- l'orchestration de containers avec docker-compose ✔️


## 💻 J'utilise

### Un exemple personnel commenté ✔️

<!-- services:
  db:
    image: postgres:15-alpine
    restart: always
    environment:
      POSTGRES_PASSWORD: postgres
      PGUSER: postgres
    ports:
      - 5433:5432
    healthcheck:
      test: ["CMD-SHELL", "pg_isready"]
      interval: 10s
      timeout: 5s
      retries: 5

  server:
    image: wcs_project-server
    restart: always
    depends_on:
      db:
        condition: service_healthy
    environment:
      DB_HOST: db
    build: ./server
    ports:
      - 4000:4000
      - 4001:4001
    volumes:
      - ./server/src:/app/src
      Ici j'ai du rajouter /src car il y avait un conflit entre mon os (Mac) et Linux. 

  client:
    image: wcs_project-client
    restart: always
    build: ./client
    ports:
      - 3000:3000
    volumes:
      - ./client:/app -->

### Utilisation dans un projet ✔️

[lien github](https://github.com/WildCodeSchool/2211-wns-neumann-pawn-balls)

Description : Container Docker ==> server, client, db. Avec un DockerFile dans le client et server pour pouvoir faire toutes les install.

### Utilisation en production si applicable ❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionne l❌ / ✔️
. 

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
