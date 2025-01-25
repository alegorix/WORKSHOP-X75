# Projet Workshop : Développement d'une MarketPlace

## **1. Briefing complet pour le projet MarketPlace**

### **Objectifs pédagogiques**
- Appliquer et approfondir les connaissances en HTML, CSS, PHP, MySQL et Bootstrap.
- Travailler en équipe pour développer un projet complet de bout en bout.
- Structurer un projet web (frontend et backend).
- Développer un système d’authentification, de gestion de contenu, de messagerie, et de transactions.

### **Description du projet**
Création d'une **MarketPlace** fonctionnelle où :
1. Les utilisateurs peuvent s'inscrire, se connecter et gérer leur compte.
2. Les vendeurs peuvent créer et gérer des annonces pour leurs produits (ajout/modification/suppression).
3. Les acheteurs peuvent rechercher des produits, consulter des annonces, et effectuer des achats.
4. Un système de messagerie permet une communication entre les acheteurs et les vendeurs.

### **Fonctionnalités principales**

#### **Phase 1 : Authentification et gestion des utilisateurs**
- Système d’inscription et de connexion.
- Gestion de profils utilisateur (vendeur et acheteur).
- Définir des rôles (vendeur, acheteur).

#### **Phase 2 : Gestion des annonces**
- Création d’un formulaire pour poster une annonce (titre, description, prix, image, catégorie, etc.).
- Affichage des produits sur la page d’accueil et les pages de recherche.
- Système de recherche et de filtrage (par prix, catégorie, etc.).

#### **Phase 3 : Messagerie**
- Système de messagerie simple entre acheteurs et vendeurs.
- Notifications pour les nouveaux messages.

#### **Phase 4 : Backoffice simplifié**
- Interface d’administration pour gérer les utilisateurs et les annonces.

#### **Phase 5 : Optimisation**
- Design responsive avec Bootstrap.
- Implémentation d’une gestion sécurisée des données (hash des mots de passe, validation des entrées utilisateur, etc.).
- Tests utilisateurs pour identifier les bugs.

---

## **2. Planning détaillé avec répartition des tâches (125 heures)**

### **Jour 1 à 2 (16h) : Planification et structuration**
- **Tâches générales :** *(Planification et collaboration)*
  - Présentation du projet, définition des fonctionnalités, et brainstorming.
  - Réalisation des wireframes (frontend) et du schéma de base de données (backend).
  - Répartition des rôles au sein des équipes (frontend, backend, etc.).
- **Backend :**
  - Conception du schéma de la base de données (tables : utilisateurs, annonces, messages, catégories).
  - Préparation de la connexion à la base de données avec PDO ou MySQLi.
- **Frontend :**
  - Réalisation des wireframes en utilisant des outils comme Figma ou des croquis papier.
  - Mise en place de la structure HTML/CSS de base (header, footer, etc.).

---

### **Jour 3 à 6 (32h) : Développement de l’authentification et gestion utilisateur**

- **Backend :**
  - Mise en place du système d’inscription : validation des champs, enregistrement des utilisateurs dans la base de données avec un mot de passe hashé.
  - Développement du système de connexion (sessions PHP).
  - Ajout d’une fonctionnalité pour modifier les profils utilisateur (mot de passe, avatar, etc.).

- **Frontend :**
  - Design des pages de connexion et d’inscription avec Bootstrap.
  - Création du tableau de bord utilisateur (profil, paramètres).
  - Gestion des messages d’erreur/succès (ex. “mot de passe incorrect”).

- **Autre :**
  - Tests des fonctionnalités d’inscription et de connexion.
  - Validation des données utilisateurs côté client (JavaScript).

---

### **Jour 7 à 10 (32h) : Gestion des annonces**

- **Backend :**
  - Développement d’un système CRUD (Create, Read, Update, Delete) pour les annonces.
  - Gestion du téléchargement d’images (avec vérification de type et taille).
  - Mise en place de requêtes pour afficher les annonces sur la page d’accueil et les pages de recherche (pagination incluse).

- **Frontend :**
  - Design du formulaire de publication d’annonces (Bootstrap, CSS).
  - Mise en place de l’affichage des annonces (grille de produits avec image, prix, description).
  - Ajout de filtres (prix, catégories) avec une interface intuitive.

- **Autre :**
  - Tests pour s’assurer que les annonces s’enregistrent et s’affichent correctement.
  - Préparation de données de test dans la base de données.

---

### **Jour 11 à 13 (24h) : Messagerie**

- **Backend :**
  - Création des tables pour gérer les messages (ex. table `messages` avec ID expéditeur, ID destinataire, contenu, timestamp).
  - Développement d’un système de messagerie : 
    - Envoyer un message.
    - Charger les conversations entre utilisateurs.
  - Gestion des notifications (ex. nouveaux messages non lus).

- **Frontend :**
  - Design de l’interface de messagerie avec Bootstrap (liste des conversations à gauche, messages à droite).
  - Mise en place d’un formulaire pour envoyer des messages.

- **Autre :**
  - Tests des messages entre utilisateurs (envoyer, lire, répondre).
  - Création de données fictives pour simuler des conversations.

---

### **Jour 14 (8h) : Backoffice**

- **Backend :**
  - Développement d’une page pour l’administration (liste des utilisateurs et annonces).
  - Ajout de fonctionnalités pour suspendre des utilisateurs ou supprimer des annonces.

- **Frontend :**
  - Design de l’interface d’administration (tableaux pour gérer les données).
  - Ajout de boutons (supprimer, modifier, suspendre) avec des confirmations JavaScript.

- **Autre :**
  - Tests des actions d’administration (supprimer, suspendre, etc.).

---

### **Jour 15 (8h) : Tests et déploiement**

- **Backend :**
  - Tests de sécurité : injection SQL, failles XSS.
  - Optimisation des requêtes SQL pour les performances.
- **Frontend :**
  - Tests d’affichage responsive avec différents appareils.
  - Vérification des formulaires et des messages d’erreur.
- **Autre :**
  - Préparation pour le déploiement (hébergement local ou en ligne, transfert des fichiers).
  - Documentation de l’installation pour les utilisateurs.

---

### **Jour 16 (5h) : Présentation finale**

- **Autre :**
  - Préparation des slides ou supports de présentation.
  - Chaque groupe présente :
    - Fonctionnalités principales développées.
    - Problèmes rencontrés et solutions trouvées.
    - Démonstration live du site.

---

## **Répartition générale des rôles**

- **Backend :** Gestion des données et des fonctionnalités dynamiques (authentification, annonces, messagerie, backoffice).
- **Frontend :** Création des interfaces utilisateur avec HTML, CSS, JavaScript, et Bootstrap.
- **Autre (Tests et organisation) :** Collaboration, tests, déploiement, wireframes, présentation.
