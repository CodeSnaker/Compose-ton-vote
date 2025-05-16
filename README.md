# Compose Ton Vote

## L'application

Compose ton vote est une application qui permet de voter pour son école préférée parmi 4 choix possible et de visualiser l'ensemble des votes sur une page web.

## Mon travail

Je me suis chargé de la containerization sur ce projet: rédiger les Dockerfile et le docker-compose.yaml.

## Architecture du projet

![app architecture](https://github.com/CodeSnaker/Compose-ton-vote/blob/main/architecture_schema.jpg?raw=true)

## Les serveurs web

### poll

Ce serveur permet aux utilisateurs de voter. Il tourne sur le port 5000.

### result

Ce serveur permet de visualiser les votes des utilisateurs. Il tourne sur le port 5001.
