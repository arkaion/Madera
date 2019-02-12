# Madera
Frontend du projet Madera réalisé en Angular

Le projet Madera représente la création d'une application web de modélisation de maisons modulaires.
Ce repo contient la partie frontend de cette application.

# SETUP :
## Config utilisée :
VM Ubuntu 14.04.5 LTS "trusty"

node v11.9.0

npm 6.7.0

## Installation
Certaines commandes peuvent nécessiter d'être executées en root superuser
```
npm install -g npm@latest

npm cache clean -f
npm install -g n
n stable
```
Vérifier les versions avec `node -v` et `npm -v`

Si node n'est pas à la bonne version :
```
nvm install #.#.#  (exemple : nvm install 11.9.0)
nbm use #.#.#
nvm alias default node
```

## Lancement
Dans le fichier package.json, la ligne

`"start": "ng serve --host $IP --port $PORT --public-host $C9_HOSTNAME",`

modifie la commande `npm start` pour lancer le projet avec une session cloud9.

La preview est accessible à https://angular-arkaion.c9users.io/
