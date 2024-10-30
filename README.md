# NodeJsTransfer - Frontend

Ce repository contient le frontend du projet NodeJsFinal, une interface utilisateur Vue.js pour gérer le serveur de fichiers.

### Ce repository correspond à la partie Frontend du projet 'NodeJsTransfert', afin de pouvoir le tester et en profiter dans son intégralité, je vous invite à vous rendre [ici](https://github.com/TheKyyn/NodeJsFinal).

## Fonctionnalités

- **Tableau de Bord Utilisateur** : Affiche les fichiers, le quota d'espace et les actions possibles.
- **Actions sur les Fichiers** : Téléchargement, suppression et partage.
- **Affichage du Quota** : Mise à jour dynamique de l'espace utilisé.

## Prérequis

- Node.js et Vue CLI
- Docker et Docker Compose

## Installation et Déploiement

Clonez le repo :

```bash
git clone https://github.com/TheKyyn/NodeJsTransferFront.git
cd NodeJsTransferFront
```

Lancer en Docker :

```bash
docker-compose up -d --build
```

Accédez à l'interface :

```arduino
http://localhost:8080
```

## Contribuer

Forkez le repo, créez une branche pour vos modifications, et soumettez une pull request.
