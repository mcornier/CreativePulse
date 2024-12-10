# CreativePulse

*CreativePulse* est un projet expérimental qui vise à proposer un environnement de jeu multijoueur dans lequel les utilisateurs peuvent concevoir et personnaliser leurs propres modèles 3D. L’objectif est d’offrir une plateforme flexible, permettant de créer divers types de jeux (par exemple, des combats spatiaux, des courses de véhicules, etc.) en mettant l’accent sur la créativité et la personnalisation.

## Objectifs du projet

- **Personnalisation 3D** : Permettre aux utilisateurs de générer leurs propres modèles 3D (vaisseaux, véhicules, objets divers).
- **Multijoueur temps réel** : Utiliser des technologies comme SignalR pour connecter plusieurs joueurs (6, 8, 10, 12 ou plus) dans une même partie, leur permettant d’interagir et de se confronter.
- **Technologies Web** : Exploiter Node.js pour la logique serveur, WebGL pour l’affichage 3D dans le navigateur, et SignalR pour la communication temps réel.
- **Extensibilité** : Concevoir le projet de manière à pouvoir ajouter facilement de nouveaux types de jeux, de modes, ou d’environnements, sans se limiter à un univers spatial.

## Technologies clés

- **Node.js** : Pour la partie serveur (gestion des salons, synchronisation, logique de jeu).
- **WebGL** : Pour le rendu 3D dans le navigateur, offrant des visuels en temps réel sur une large gamme d’appareils.
- **SignalR** : Pour une communication temps réel bidirectionnelle entre le serveur et les clients, garantissant une faible latence et une expérience multijoueur fluide.

## Structure initiale du projet

```
CreativePulse/
 ├─ server/
 │   ├─ index.js          // Point d'entrée du serveur Node.js
 │   ├─ game-logic.js     // Logique de base du jeu (initialisation, règles, etc.)
 │   ├─ signalr-hub.js    // Configuration du hub SignalR
 │   └─ ...
 ├─ client/
 │   ├─ index.html        // Page d'accueil du client
 │   ├─ app.js            // Code client, initialisation WebGL, connexion SignalR
 │   ├─ rendering/        // Code de rendu WebGL, shaders, etc.
 │   └─ models/           // Modèles 3D de base, templates pour les créations
 ├─ assets/
 │   ├─ textures/
 │   ├─ shaders/
 │   └─ ...
 ├─ README.md
 └─ package.json
```

## Évolutions possibles

- **Éditeur 3D simplifié** : Permettre aux utilisateurs de concevoir leurs modèles 3D directement dans un éditeur intégré au jeu.
- **Systèmes de score, classements** : Ajouter des mécaniques de progression, des palmarès, et des récompenses pour encourager la compétition.
- **Soutien multi-plateforme** : Assurer une compatibilité sur PC, tablettes, et éventuellement mobiles.
- **Intégration IA / Génération procédurale** : Explorer des systèmes de génération de contenu automatisés (véhicules, environnements) pour inspirer ou guider la création des joueurs.

## Contribution

Toute personne intéressée peut contribuer aux idées, au code, à la conception de modèles 3D ou aux tests. Des directives de contribution, des templates d’issues et des plans de roadmap seront ajoutés au fur et à mesure de l’évolution du projet.

---

Ce fichier README n’est qu’une base et sera mis à jour au fur et à mesure de l’avancement du projet.
