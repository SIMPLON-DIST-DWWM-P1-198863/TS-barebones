# TS-barebones

Ce repo contient le strict minimum pour pouvoir travailler un peu de Typescript via Node.

## Installation

- Cloner le repo
- `npm i`

## Lancement

On a deux modes d'exécution: dev et prod

### Mode dev

- `npm run dev`

Le terminal est pris par "tsx", un outil qui va traduire votre TS en JS à la volée.
NB: Il est configuré par défaut pour "surveiller" le fichier src/index.ts. A chaque changement dans le fichier, le contenu est reexécuté
Pour l'arrêter: `Ctrl-C`

### Mode prod

- `npm run build`
- `npm run start`

Le "build" crée un dossier dist/ et stocke dedans la traduction de votre TS en JS.
Le "start" exécute le fichier JS généré.
Il n'y a aucun serveur, le code est exécuté une et une seule fois.
