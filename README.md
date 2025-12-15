# Pokémon API Flask + Docker

Ce projet est une API Flask qui récupère les données d'un Pokémon depuis la [PokéAPI](https://pokeapi.co/) et les renvoie au format JSON. Il est containerisé avec Docker pour pouvoir être exécuté facilement sur n'importe quelle machine.

---

## Contenu du projet
pokeAPI/
├── app.py # Code principal de l'API
├── Dockerfile # Instructions pour Docker
├── index.html # Page d'affichage de l'API
├── README # Explication du projet
└── requirements.txt # Dépendances Python

---

## Prérequis

- [Docker](https://www.docker.com/products/docker-desktop) installé
- Accès à Internet pour récupérer les données de la PokéAPI

---

## Instructions pour exécuter le projet

### 1. Cloner le dépôt

```bash
git clone https://github.com/Stims-cmd/pokeAPI
cd pokeAPI
```

### 2. Cloner l'image Docker

```bash
docker build -t pokemon-api .
```

### 3. Lancer le container Docker

```bash
docker run -p 5000:5000 pokemon-api
```

## Notes 

L’API sera accessible sur : http://localhost:5000

## Auteur 

- Simon DUCHANAUD 