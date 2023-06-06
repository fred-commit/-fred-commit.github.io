-fred-commit.github.io
Mon portefeuille

Technologies utilisées🛠️
Colis - Bundler
Bootstrap 4 - Bibliothèque de composants frontaux
Sass - Langage d'extension CSS
ScrollReveal.js - bibliothèque JavaScript
Tilt.js - petite bibliothèque de parallaxe JavaScript
Comment utiliser🔧
Depuis votre ligne de commande, clonez d'abord Simplefolio :

# Clone the repository
$ git clone https://github.com/cobiwave/simplefolio

# Move into the repository
$ cd simplefolio

# Remove the current origin repository
$ git remote remove origin
Après cela, vous pouvez installer les dépendances en utilisant NPM ou Yarn.

Utilisation de NPM : exécutez simplement les commandes ci-dessous.

# 2022 Update - Fix Dependencies
$ npm audit fix
$ npm i @parcel/transformer-sass

# Install dependencies
$ npm install

# Start the development server
$ npm start
Utilisation de Yarn : sachez que vous devrez supprimer le package-lock.jsonfichier avant d'exécuter les commandes ci-dessous.

# Install dependencies
$ yarn

# Start the development server
$ yarn start
REMARQUE : Si vous rencontrez des problèmes lors de l'installation des dépendances avec NPM, utilisez la commande ci-dessous :

# Install dependencies with all permissions
$ sudo npm install --unsafe-perm=true --allow-root
Une fois votre serveur démarré, rendez-vous sur cette url http://localhost:1234/pour voir le portfolio en local. Cela devrait ressembler à la capture d'écran ci-dessous.

