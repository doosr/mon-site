# Résidence Haroun - Site Web de Réservation et Commande en Ligne

## Description

Ce projet est un site web complet pour la Résidence Haroun, située à La Ghedhabna-Chebba en Tunisie.  
Le site permet aux clients de commander en ligne au restaurant, scanner un QR code pour identifier leur table, gérer leur panier, laisser des avis, et découvrir les services de la résidence.

---

## Fonctionnalités principales

- **Système de commande en ligne**  
  Menu interactif avec catégories (Pizzas, Sandwichs, Boissons, Desserts)  
  Panier dynamique avec modification des quantités  
  Validation et enregistrement des commandes dans Firebase

- **Scanner QR Code**  
  Identification des tables via QR code  
  Utilisation de la caméra (API MediaDevices) optimisée pour mobile

- **Avis clients**  
  Formulaire de notation avec étoiles  
  Affichage des commentaires clients

- **Présentation**  
  Galerie photo avec carrousel automatique  
  Vidéo de présentation  
  Description des services et commodités de la résidence

---

## Technologies utilisées

- Frontend : HTML5, CSS3, JavaScript vanilla  
- Design responsive (mobile-first) avec animations CSS  
- Backend (base de données) : Firebase Firestore  
- Firebase Authentication (optionnel)  
- Bibliothèque jsQR pour la lecture des QR codes  
- API MediaDevices pour accéder à la caméra

---

## Installation

1. Cloner le dépôt  
```bash
git clone https://github.com/votre-utilisateur/residence-haroun.git
