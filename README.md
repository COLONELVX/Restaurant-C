# Système de Gestion de Restaurant 🍽️

Une application console de gestion de restaurant écrite en C permettant de gérer les informations du restaurant, les repas et les employés via un système de menus interactifs.

## 📋 Description

Ce Système de Gestion de Restaurant est une application console simple mais fonctionnelle qui permet aux propriétaires ou gestionnaires de restaurant d'effectuer des opérations CRUD (Créer, Lire, Modifier, Supprimer) sur trois entités principales :
- **Restaurant**
- **Repas**
- **Employés**

Le programme dispose d'une interface menu conviviale qui guide les utilisateurs à travers diverses opérations.

## ✨ Fonctionnalités

### 🏪 Gestion du Restaurant
- Ajouter les détails du restaurant (ID, Nom, Adresse)
- Afficher les informations du restaurant
- Modifier les données du restaurant
- Supprimer les enregistrements du restaurant

### 🍳 Gestion des Repas
- Ajouter les informations d'un repas (ID, Nom, Ingrédients, Prix)
- Afficher les détails du repas
- Mettre à jour les données du repas
- Supprimer les repas du système

### 👥 Gestion des Employés
- Enregistrer les employés (ID, Nom, Âge, Poste, Salaire)
- Afficher les détails des employés avec détection du statut Manager
- Modifier les informations des employés
- Supprimer les enregistrements des employés
- **Fonctionnalité spéciale** : Identifie si un employé est Manager selon son poste

### 🗑️ Fonctionnalités Supplémentaires
- Supprimer tous les enregistrements en une fois
- Option de retour au menu principal dans chaque sous-menu
- Validation des choix de menu

## 🛠️ Détails Techniques

- **Langage** : C
- **Structures de données** : Structures personnalisées pour Restaurant, Repas et Employé
- **Entrée/Sortie** : Interface console utilisant printf/scanf
- **Gestion mémoire** : Stockage de données à instance unique (pas de persistance fichier)


## 📝 Menu Principal

| Option | Description |
|--------|-------------|
| [1] | Gestion Restaurant (Ajouter des éléments) |
| [2] | Afficher (Consulter les enregistrements) |
| [3] | Modifier (Mettre à jour les enregistrements) |
| [4] | Supprimer (Effacer les enregistrements) |
| [5] | Quitter (Fermer l'application) |


## 🧪 Exemple d'Utilisation

```
--------- Menu Principal ---------
[1] : Gestion Restaurant
[2] : Afficher
[3] : Modifier
[4] : Supprimer
[5] : Quitter
Veuillez choisir un numero: 1

--------- Menu Restaurant ---------
[1] : Ajouter Restaurant
[2] : Ajouter Repas
[3] : Ajouter Employé
[4] : Retour au menu Principal
Veuillez choisir un numero:
```

## 👨‍💻 Auteurs

- **COLONEL**
- **BAKI**
- **OUSSAMA**

## 📅 Création

2024


## 💻 Langage de Programmation

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
