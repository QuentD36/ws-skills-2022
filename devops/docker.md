# Docker

> ❌ A travailler

## 🎓 J'ai compris et je peux expliquer

- la création d'une image docker 📈
- l'éxécution d'un container 📈
- l'orchestration de containers avec docker-compose 📈


## 💻 J'utilise

### Un exemple personnel commenté ✔️

``` 
// Contenu d'un fichier docker-compose.yml

services:
  backend:
    build: ./back
    ports:
      - 5000:5000
    volumes:
      - ./back/src:/app/src
      - ./back/data:/app/data
  frontend:
    build: ./front
    ports: 
      - 8080:3000
      - 3000:3000
    volumes:
      - ./front/src:/app/src
```

### Utilisation dans un projet ✔️

[Projet Wilder Book Dockerisé](https://github.com/QuentD36/ws-docker-quest3.git)

Description :

### Utilisation en production si applicable ❌

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌

Description :

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
