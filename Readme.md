# kaamelott soundboard slack



## Introduction

Intégration slack du [kaamelott soundboartd](http://kaamelott-soundboard.2ec0b4.fr/)


## Installation

```bash
yarn
```

```bash
yarn start
```

si vous utilisez docker:
```bash
docker-compose up
```
il faudra également ajouter dans le fichier .env
```
EXPOSED_PORT=3333
```

l'application est désormais disponible sur [localhost:3333](http://localhost:3333)


## Configuration

- Créer une application slack
- Ajouter une souscription d'événement sur link_shared pour le domaine kaamelott-soundboard.2ec0b4.fr
- Ajouter les droits files:write:user et links:read
- Créer un fichier .env à la racine de l'application contenant le token oauth de l'application slack

```
SLACK_TOKEN=YOUR_SLACK_TOKEN
```

