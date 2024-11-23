# Product Inventory App

## 📝 Description

Application web de gestion d'inventaire de produits développée avec React, TypeScript et Material-UI. Elle permet la gestion en temps réel des produits grâce à l'intégration de WebSocket.

## ✨ Fonctionnalités

- 🔐 Authentification (connexion/inscription)
- 📦 Gestion des produits :
  - Affichage de la liste
  - Ajout
  - Modification
  - Suppression
- 🔍 Recherche de produits
- 🔄 Mise à jour en temps réel (Socket.io)
- 💅 Interface utilisateur moderne et responsive

## 🛠 Technologies Utilisées

- **Frontend**
  - React
  - TypeScript
  - Redux Toolkit (Gestion d'état)
  - Material-UI (Composants UI)
  - Socket.io-client (WebSocket)
  - React Router (Navigation)
- **Backend**
  - Node.js avec Express
  - TypeScript
  - Prisma (ORM)
  - Socket.io
  - JWT pour l'authentification

## 🚀 Installation et Démarrage

### Prérequis

- Node.js (version 14 ou supérieure)
- npm ou yarn

### Installation
Cloner le repository
```
git clone https://github.com/Abbasrx77/Product-Inventory.git
```
Accéder au dossier
```
cd Product-Inventory
```
Accéder au frontend
```
cd frontend
```
Installer les dépendances
```
npm install
```
ou
```
yarn install
```
Accéder au backend
```
cd ..
```
```
cd backend
```
Installer les dépendances
```
npm install
```
ou
```
yarn install
```
### Démarrer l'application en mode développement
- **Démarrer le backend**
  - Ouvrir un nouveau terminal et accéder au backend
  ```
  cd backend
    ```
- Lancer le serveur
  ```
  npm start
  ```
  Le message suivant devrait s'afficher: The server is listening on http://localhost:3000
- **Démarrer le frontend**
  - Ouvrir un nouveau terminal et accéder au frontend
  ```
  cd frontend
  ```
  - Lancer l'application
  ```
  npm run dev
  ```

## 🔒 Authentification
L'application utilise un système d'authentification par token JWT :
- Les tokens sont stockés dans le localStorage
- Protection des routes nécessitant une authentification
- Déconnexion automatique à l'expiration du token

## 🎯 Utilisation
1. Créez un compte ou connectez-vous
2. Accédez à la liste des produits
3. Utilisez le champ de recherche pour filtrer les produits
4. Ajoutez un nouveau produit via le bouton "+"
5. Modifiez ou supprimez les produits existants

## 🔄 Fonctionnement WebSocket
- Connexion WebSocket établie à l'ouverture de la liste des produits
- Mise à jour automatique lors des modifications
- Déconnexion lors de la fermeture de la page

## 🎨 Personnalisation du Thème
Le thème peut être personnalisé dans `src/theme.ts` :
- Couleurs
- Typographie
- Espacements
- Animations
- etc.

## 🤝 Contribution
Les contributions sont les bienvenues ! Pour contribuer :
1. Forkez le projet
2. Créez une branche pour votre fonctionnalité
3. Committez vos changements
4. Poussez vers la branche
5. Ouvrez une Pull Request

## 📝 License
MIT

## 👥 Auteurs
- Abbas MAMA

## 📧 Contact
- Email : abbasmama007@gmail.com