# Mini Projet Node.js avec Express et MongoDB

Ce projet est un exemple de mise en œuvre d'une application simple utilisant Node.js, Express et MongoDB pour la gestion de données.

## Configuration requise

- Node.js v18.17.0
- MongoDB 

## Installation

1. Ouvrez ce dossier dans Visual Studio Code.

2. Installez les extensions recommandées pour Node.js et MongoDB.

3. Clonez ce dépôt en utilisant la commande Terminal intégrée :

git clone https://github.com/votre-utilisateur/mini-projet-node-express-mongodb.git

Accédez au répertoire du projet :
cd mini-projet-node-express-mongodb

Installez les dépendances en exécutant la commande suivante dans le Terminal :
npm install

Configurez votre base de données MongoDB dans le fichier config.js.

Démarrage du serveur
Ouvrez le terminal intégré à partir de Visual Studio Code.

Exécutez la commande suivante pour démarrer le serveur :
npm start

Le serveur sera accessible à l'adresse : http://localhost:3000

Routes API
GET /api/articles : Récupérer tous les articles.
GET /api/articles/:id : Récupérer un article spécifique par son ID.
POST /api/articles : Créer un nouvel article.
PUT /api/articles/:id : Mettre à jour un article existant.
DELETE /api/articles/:id : Supprimer un article.

Structure du Projet
app.js : Fichier principal de l'application.
routes/ : Contient les fichiers de définition des routes API.
models/ : Contient les modèles de données MongoDB.
controllers/ : Contient les contrôleurs pour les différentes routes.
config.js : Configuration de la base de données et d'autres paramètres.
package.json : Fichier de configuration de Node.js.
Contribuer
Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une pull request pour apporter des améliorations ou des corrections.

Auteur
Julius Djossou
