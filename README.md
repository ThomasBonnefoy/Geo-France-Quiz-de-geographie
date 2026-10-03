# Geo France – Quiz de géographie

## Contexte du projet

Ce projet a été réalisé dans le cadre d’une **SAE** (*Situation d’Apprentissage et d’Évaluation*, **1.01 – 1.02 – Quiz de géographie*) de développement en Processing, au sein du **BUT Informatique**, à l’**IUT Lyon 1 – site de Bourg-en-Bresse**.

La SAÉ est le dispositif pédagogique qui structure les projets du BUT : l’IUT confie aux étudiants un projet conséquent, réalisé en équipe, qui reproduit les conditions d’un travail réel : cahier des charges, gestion de projet, travail collaboratif et livrable évalué. Ces situations d’apprentissage constituent l’un des principaux vecteurs d’évaluation de la formation, en **contrôle continu**.

L’objectif est de mettre en œuvre un projet de développement conséquent, en groupe, en portant une attention particulière à :
- la qualité et l’organisation du code
- l’ergonomie et l’expérience utilisateur
- la finalisation complète des fonctionnalités
- la gestion du travail en équipe

Le projet s’inscrit dans un **cadre strictement pédagogique**.

---

## Présentation du projet

Dans ce contexte, nous avons développé **Geo France**, une **application interactive de quiz de géographie** basée sur la **carte de la France métropolitaine**.

L’objectif de l’application est de proposer une approche ludique et interactive de l’apprentissage de la géographie, en s’appuyant sur :
- l’exploration de la carte
- des questions variées
- des interactions directes avec les départements

---

## Objectifs pédagogiques

- Manipuler une carte SVG dans Processing  
- Utiliser les classes `PShape`  
- Structurer un projet autour de classes et de données externes  
- Concevoir une application interactive orientée utilisateur  
- Travailler en équipe avec une répartition claire des tâches  

---

## Fonctionnement de l’application

L’application **Geo France** s’articule autour de plusieurs modes, conformes au sujet imposé par la SAE.

### Mode apprentissage
- Parcours libre de la carte  
- Mise en évidence visuelle des départements  
- Découverte progressive des informations géographiques  

### Quiz de localisation
- Questions simples de type « Où se situe ce département »
- Réponse par clic direct sur la carte
- Vérification automatique des réponses

### Quiz avec images
- Identification de monuments ou paysages  
- Association image – département  
- Questions générées automatiquement  

### Questions multiples
- Placement de plusieurs éléments  
- Interaction successive ou simultanée selon le mode  
- Validation progressive des réponses  

### Mode puzzle
- Reconstitution de la carte  
- Déplacement et placement des départements  
- Vérification des positions correctes  

L’accent a été mis sur la **finalisation complète des fonctionnalités implémentées**, conformément aux consignes de la SAE.

---

## Architecture et logique du programme

Le projet est organisé autour de :
- classes dédiées à la carte et aux départements  
- gestion des états de l’application (menus, modes de jeu)  
- séparation claire entre l’affichage, la logique de jeu et les données  

Les données géographiques (départements, images) sont chargées depuis des **fichiers externes**, facilitant l’évolution du projet.

---

## Organisation du travail

Projet réalisé en groupe dans le cadre de la SAE.

### Travail de groupe et contribution personnelle

Le projet a été réalisé en travail de groupe avec une répartition des tâches définie en amont.

### Membres du groupe

* [Yann Madry](https://github.com/yann-madry)
* Adam Bounouara
* [Thomas Bonnefoy](https://github.com/ThomasBonnefoy)

Ma contribution personnelle s’est concentrée principalement sur :
- la gestion de la carte  
- l’implémentation du mode puzzle  
- la conception de l’interface utilisateur  
- la gestion du volume sonore  

Cette répartition m’a permis de travailler sur des aspects centrés sur la **logique, la conception et la robustesse** du programme.

---

## Documents

Les documents associés au projet sont disponibles à la racine du dépôt :
- `consignes.pptx` : consignes de la SAE  
- `compte_rendu.pdf` : compte rendu du projet 

---

## Implémentation

L’implémentation de l’application a été réalisée en **Processing (Java)**.  
Le dossier `code/` contient l’ensemble des fichiers source (`.pde`), organisés par fonctionnalités et classes.

Les fichiers audio utilisés lors du développement ne sont pas inclus dans ce dépôt afin de limiter la taille du projet, certains d’entre eux rendant le dépôt trop volumineux.

---

## Suite du projet

Comme tout projet académique, certaines améliorations pourraient être envisagées :
- amélioration de l’ergonomie et du design visuel  
- enrichissement de la base de données géographiques  
- ajout de nouveaux types de questions  
- optimisation des performances et du chargement des ressources  
- ajout d’une sauvegarde du record  

Ces points constituent des **pistes d’évolution** plutôt que des manques bloquants.
