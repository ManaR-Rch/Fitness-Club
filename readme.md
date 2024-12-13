Gestion de Salle de Sport - Application Web
Contexte du Projet
Une salle de sport cherche à moderniser son système de gestion en mettant en place une application web. Actuellement, toutes les opérations sont réalisées manuellement, ce qui entraîne des erreurs et des difficultés dans la gestion quotidienne. L'objectif est de créer un outil simple permettant de :

Gérer les membres inscrits à la salle de sport.
Planifier et afficher les activités ou équipements disponibles.
Permettre aux membres de réserver des activités ou équipements.
Objectifs du projet
Le but de ce projet est de concevoir une solution complète, en se basant sur un schéma de base de données fourni, qui inclut la modélisation des données, la configuration de l'environnement, et le développement des fonctionnalités essentielles pour la gestion de la salle de sport.

Instructions de Réalisation
1. Schéma de la Base de Données (ERD)
Analyse du schéma de base de données fourni : Vous devrez examiner le schéma fourni, qui décrit les entités principales du système et leurs relations.
Cahier des charges : Rédigez un cahier des charges décrivant :
Les entités principales : Membres, Activités, Réservations.
Les relations entre les entités : Par exemple, un membre peut réserver plusieurs activités, et une activité peut être réservée par plusieurs membres.
Les besoins fonctionnels : Quelles fonctionnalités sont nécessaires pour chaque entité (ex. ajout d'un membre, création d'une réservation, affichage des activités disponibles, etc.).
2. Conception des Tables (Bonus)
À partir du schéma de base de données, vous devrez concevoir les tables nécessaires :

Conception des tables : Créez les tables en respectant la structure donnée, incluant les clés primaires et étrangères.
Ajout d’attributs ou tables supplémentaires : Si nécessaire, ajoutez des attributs ou de nouvelles tables pour couvrir des besoins spécifiques (par exemple, gestion des abonnements ou des niveaux d'accès des membres).
3. Diagramme UML (Cas d'Utilisation)
Réalisez un diagramme de cas d'utilisation (Use Case Diagram) pour identifier :

Les acteurs principaux du système : Membre, Administrateur, etc.
Les interactions possibles entre les acteurs et le système. Par exemple :
Un membre peut consulter les activités disponibles.
Un administrateur peut ajouter ou modifier des membres et des activités.
4. Configuration de l'Environnement
Préparez l'environnement de développement nécessaire pour le projet :

Logiciels requis :
Un serveur local (par exemple, XAMPP, WAMP, ou Laragon).
Un éditeur de code (par exemple, VS Code, Sublime Text).
Création de la base de données : Utilisez les scripts SQL pour créer la base de données et ses tables.
Structure des fichiers : Organisez les fichiers de votre projet, par exemple :
/assets : pour les images, fichiers CSS/JS.
/includes : pour les fichiers PHP réutilisables.
/public : pour les pages accessibles par l'utilisateur.
5. Scripts SQL
Vous devrez rédiger des scripts SQL pour la gestion de la base de données :

Création de la base de données et des tables : Créez la base de données et toutes les tables nécessaires (membres, activités, réservations, etc.).
Opérations CRUD (Créer, Lire, Mettre à jour, Supprimer) : Rédigez des scripts pour insérer, mettre à jour, et supprimer des données dans les tables.
Jointures : Réalisez des requêtes de jointure pour lier plusieurs tables, par exemple, afficher les réservations d'un membre.
6. Fonctionnalités en PHP
Développez les fonctionnalités suivantes en PHP pour interagir avec la base de données :

Ajouter des données via des formulaires :
 des formulaires pour ajouter des membres, des activités, et des réservations.
Utilisez des requêtes SQL pour insérer ces données dans la base de données.
Afficher dynamiquement les données :
Affichez la liste des membres, des activités disponibles, et des réservations de manière dynamique à partir de la base de données.
Utilisez des requêtes SQL pour récupérer et afficher ces données sous forme de tableaux dans les pages HTML.
Structure du Projet
Voici une idée de structure pour organiser les fichiers de votre projet :


Ce projet vous permettra de mettre en place un système complet pour la gestion d'une salle de sport, incluant la gestion des membres, des activités, et des réservations. Vous devrez développer des fonctionnalités en PHP et interagir avec une base de données MySQL pour assurer la gestion dynamique de ces informations.