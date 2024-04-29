# My Contest Backend 🌍

![GitHub top language](https://img.shields.io/github/languages/top/yourusername/my-contest-backend)
![GitHub](https://img.shields.io/github/license/yourusername/my-contest-backend)
![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/my-contest-backend)
![GitHub issues](https://img.shields.io/github/issues-raw/yourusername/my-contest-backend)
![Node.js CI](https://github.com/yourusername/my-contest-backend/workflows/Node.js%20CI/badge.svg)

## Description 📜
Le backend de "My Contest" fournit les services API nécessaires pour gérer des concours interactifs en ligne. Il permet aux utilisateurs de créer, participer et gérer différents types de concours comme des jeux de type GeoGuessr et des quiz. Cette solution est conçue pour être robuste, sécurisée et facilement évolutive.

## Fonctionnalités 🚀
- Création et gestion de concours 🏆
- Inscription et authentification des utilisateurs 🔐
- Participation aux concours 🌐
- Calcul dynamique des scores et classements 📊
- API pour récupérer les questions des quiz via des services externes 📚

## Technologies Utilisées 💻
- **Node.js** - Plateforme serveur pour exécuter JavaScript côté serveur.
- **TypeScript** - Langage de programmation typé basé sur JavaScript.
- **Express** - Framework pour applications web Node.js.
- **Mongoose** - ODM pour MongoDB.
- **Jest** - Framework de test pour JavaScript.

## Architecture et Principes 🏗️
### Architecture Hexagonale
Ce projet implémente l'**Architecture Hexagonale** (ou architecture pilotée par les ports et les adaptateurs), qui vise à créer une séparation claire entre la logique métier de l'application et les détails techniques tels que les bases de données et les interfaces utilisateurs.

### Injection de Dépendances
L'utilisation de l'injection de dépendances permet de réduire le couplage entre les différents composants de l'application.

### Principe de Responsabilité Unique
Chaque module ou composant du système est conçu pour avoir une seule raison de changer.

## Comment Utiliser 📘

### Installation
Clonez le dépôt et installez les dépendances :
```bash
git clone [URL du dépôt]
cd my-contest-backend
npm install
