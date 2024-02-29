# Setup du projet BeginJavascript avec VSCode

Initialisation du projet, on va :

- Télécharger les dépendances nécessaires (NodeJS, NPM)
- Clone le projet en utilisant GIT
- Télécharger VSCode
- Setup VSCode

## Télécharger les dépendances

- [git](https://git-scm.com/downloads) - v2 ou plus
- [node](https://nodejs.org/en/) - v12 ou plus
- [npm](https://nodejs.org/en/) - v6 ou plus
- [VSCode](https://code.visualstudio.com/download) - 1.78.2 ou plus

Vérifie que tout est ok en affichant les versions des dépendances installées :

- Ouvrir un terminal

```bash
git -v
node -v
npm -v
```

## Cloner le projet

- Ouvrir un terminal

```bash
git clone https://github.com/jonkab/begin-javascript.git

cd begin-javascript

npm install
```

## Setup VSCode

1. Lors de l'ouverture de VSCode, accepter d'installer toutes les extensions.

2. Ouvrir les settings VSCode en JSON avec CMD + SHIFT + P (ou CTRL sur Windows) et écrire "Open User Settings (json)"

Une fois le fichier ouvert, le contenue de `settings.beginjavascript.json` sert à installer toutes les extensions choisies.

## Test du projet

Lancer les commandes pour exécuté notre fichier `script.ts` :

```bash
npm run start
```
