# Blockchain Auth Interface

Cette application web permet aux utilisateurs de s'inscrire, de se connecter et de vérifier leur identité en utilisant une interface basée sur la blockchain.

## Prérequis

- Node.js
- Un serveur backend fonctionnant à `http://localhost:3000` avec les endpoints `/auth/register`, `/auth/login`, et `/auth/verify`.

## Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/blockchain-auth-web.git

2. Accédez au répertoire du projet :
   cd blockchain-auth-web

Utilisation

1. Ouvrez le fichier index.html dans votre navigateur web préféré.
Structure du projet
    index.html : Le fichier HTML principal contenant la structure de l'interface utilisateur.
    styles.css : Le fichier CSS contenant les styles pour l'interface utilisateur.
    script.js : Le fichier JavaScript contenant la logique pour l'inscription, la connexion et la vérification de l'identité.
    README.md : Ce fichier.

Fonctionnalités

  Inscription

    Les utilisateurs peuvent s'inscrire en fournissant leur adresse e-mail.
    Une clé publique et une clé privée sont générées et affichées à l'utilisateur.

  Connexion

    Les utilisateurs peuvent se connecter en fournissant leur clé publique et leur clé privée.
    Une signature est générée à partir de la clé privée pour authentifier l'utilisateur.
    Vérification de l'identité
    Les utilisateurs peuvent vérifier leur identité en utilisant le jeton JWT obtenu lors de la connexion.

  Dépendances

    Font Awesome : Pour les icônes.
    Web3.js : Pour la génération de signatures.