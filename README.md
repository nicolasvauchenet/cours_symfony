# Cours Symfony 6

## 01 - Mise en place de Symfony 6 et Tests Fonctionnels

### Objectif

À la fin de cette journée, vous devriez être en mesure de mettre en place un projet Symfony 6 de base, de créer une page
d'accueil, d'utiliser le système de templates Twig, et de rédiger des tests fonctionnels pour valider votre page
d'accueil.

### Contenu

- Présentation et historique de Symfony.
- Politique de releases de Symfony.
- Installation et configuration de Symfony CLI.
- Installation et configuration de Symfony 6 avec Symfony CLI.
- Mise en pratique : Installer Symfony CLI et créer un nouveau projet Symfony 6 sur son environnement de développement.
- Le Controller.
- Mise en pratique : Création d'une page d'accueil avec un contrôleur simple (Page d'accueil du blog) avec le bundle
  Maker.
- Les templates Twig.
- Mise en pratique : Utilisation d'un système de templates Twig basique mais complet.
- Les tests fonctionnels.
- Mise en pratique : Écriture de tests fonctionnels pour valider la page d'accueil.

## 02 - Entités, Tests Unitaires et Intégration

### Objectif

À la fin de cette journée, vous devriez être en mesure de créer des entités persistées en base de données, d'écrire des
tests unitaires pour les entités, de créer des formulaires avec des tests fonctionnels associés, et de valider et
persister des données.

### Contenu

- Introduction à Doctrine et création d'entités.
- Configuration de la base de données.
- Mise en pratique : Configuration de la base de données et création des Entités (Articles, Catégories) avec le bundle
  Maker.
- Les tests unitaires.
- Mise en pratique : Écriture de tests unitaires pour les entités.
- les FormTypes et leur intégration dans Twig.
- Mise en pratique : Création d'un FormType pour la création d'articles et tests fonctionnels associés.
- Validation et persistance des données.
- Mise en pratique : Ajout et modification d'article en base de données.
- Tests d'intégration.
- Mise en pratique : Tests d'intégration pour valider la création et la modification d'articles.

## 03 - Services et Dépendances

### Objectif

À la fin de cette journée, vous devriez comprendre le concept de services dans Symfony, savoir utiliser l'injection de
dépendances pour gérer les services, créer des services personnalisés, écrire des tests unitaires pour les services, et
gérer des événements avec Event Subscribers.

### Contenu

- Compréhension du concept de services dans Symfony.
- Utilisation de l'injection de dépendances pour gérer les services.
- Mise en pratique : Création de services personnalisés (Service de Gestion des uploads).
- Mise en pratique : Création de services personnalisés (Service de Gestion des Commentaires).
- Mise en pratique : Écriture de tests unitaires pour les services.
- Gestion des événements avec Event Subscribers.
- Mise en pratique : Gestion des événements avec Event Subscribers (Ajout d'un Article nouvellement créé dans la table
  des Articles mis en avant).

## 04 - Fonctionnalités Avancées et Sécurité

### Objectif

À la fin de cette journée, vous devriez être en mesure de gérer l'authentification et les utilisateurs, de gérer les
permissions et l'accès aux ressources, d'utiliser les Embedded Formtypes pour des formulaires complexes, d'écrire des
tests fonctionnels pour valider les fonctionnalités, et de comprendre les principes de sécurité en Symfony.

### Contenu

- Gestion de l'authentification et des utilisateurs.
- Mise en pratique : Gestion de l'authentification et des utilisateurs (Authentification par formulaire).
- Gestion des permissions et de l'accès aux ressources.
- Mise en pratique : Gestion des permissions et de l'accès aux ressources (Gestion des permissions pour les articles).
- Utilisation d'Embedded Formtypes pour des formulaires complexes.
- Mise en pratique : Utilisation d'Embedded Formtypes pour des formulaires complexes (édition d'articles).
- Mise en pratique : Écriture de tests fonctionnels pour valider les fonctionnalités (l'authentification).
- Sécurité - protection contre les vulnérabilités (protection contre les attaques CSRF).
- Sécurité - protection contre les vulnérabilités (protection contre les attaques XSS).
- Sécurité - protection contre les vulnérabilités (protection contre les attaques par injection SQL).
- Mise en pratique : Sécurité - protection contre les vulnérabilités (protection contre les attaques CSRF, XSS et par
  injection SQL).

## 05 - Tests Avancés, Bonnes Pratiques et Déploiement du Projet

### Objectif

À la fin de cette journée, vous devriez être capable de mettre en œuvre des tests avancés (tests d'intégration, tests de
performance), d'appliquer les bonnes pratiques de développement Symfony, d'optimiser les performances, de gérer les
erreurs et les logs, et de déployer une application Symfony.

### Contenu

- tests avancés - tests de performance.
- Mise en pratique : tests avancés - tests de performance (tests de chargement des pages).
- Application des bonnes pratiques de développement (structure de répertoire, documentation du code, PSR).
- Mise en pratique : Application des bonnes pratiques de développement (structure de répertoire, documentation du code,
  validation PSR).
- Optimisation des performances.
- Mise en pratique : Optimisation des performances (mise en cache des vues).
- Gestion des erreurs et des logs.
- Mise en pratique : Gestion des erreurs et des logs (journalisation des actions).
- Déploiement d'une application Symfony.
- Mise en pratique : Déploiement d'une application Symfony (mise en ligne du blog).
