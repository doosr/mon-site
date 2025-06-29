Résidence Haroun - Site Web de Réservation et Commande en Ligne
Description
Ce projet est un site web complet pour la Résidence Haroun, située à La Ghedhabna-Chebba en Tunisie. Le site propose :

Un système de commande en ligne pour le restaurant

Un scanner de QR code pour identifier les tables

Une interface de gestion de panier

Une section d'avis clients

Une présentation des services et commodités

Fonctionnalités principales
Système de commande
Menu interactif avec catégories (Pizzas, Sandwichs, Boissons, Desserts)

Panier dynamique avec ajustement des quantités

Validation de commande avec enregistrement dans Firebase

Scanner QR Code
Identification des tables via QR code

Interface caméra optimisée pour mobile

Avis clients
Formulaire d'évaluation avec notation par étoiles

Affichage des commentaires existants

Présentation
Galerie photo avec carrousel automatique

Vidéo de présentation

Description des services

Technologies utilisées
Frontend
HTML5, CSS3, JavaScript vanilla

Design responsive (mobile-first)

Animations CSS

Backend (données)
Firebase Firestore (base de données)

Firebase Authentication (optionnel)

Bibliothèques
jsQR pour la lecture des QR codes

API MediaDevices pour l'accès à la caméra

Installation
Cloner le dépôt :

bash
git clone https://github.com/votre-utilisateur/residence-haroun.git
Configurer Firebase :

Créer un fichier firebase-config.js avec vos identifiants Firebase

Activer Firestore dans la console Firebase

Hébergement :

Le site peut être hébergé sur Firebase Hosting, Netlify, Vercel ou tout hébergeur statique

Structure des fichiers
text
residence-haroun/
├── index.html          # Page principale
├── assets/
│   ├── css/            # Feuilles de style
│   ├── js/             # Scripts JavaScript
│   └── images/         # Images du site
├── firebase-config.js  # Configuration Firebase
└── README.md           # Ce fichier
Configuration Firebase
Remplacer les valeurs dans le script par vos identifiants Firebase :

javascript
const firebaseConfig = {
  apiKey: "VOTRE_CLE_API",
  authDomain: "VOTRE_DOMAINE.firebaseapp.com",
  projectId: "VOTRE_PROJET",
  storageBucket: "VOTRE_BUCKET.appspot.com",
  messagingSenderId: "VOTRE_SENDER_ID",
  appId: "VOTRE_APP_ID"
};
