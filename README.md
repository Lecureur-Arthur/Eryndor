# **Eryndor**

## **Description**
**Eryndor** est un jeu en réalité virtuelle (VR) qui plonge le joueurs dans un univers fantastique riche et vivant, inspiré des jeux de rôle et des aventures en monde ouvert. Le joueur incarne un héros en quête de fragments du **Coeur d'Eryndor**, une mustérieuse relique ancienne dispersée à travers un royaume magique. En explorant des plaines sauvages, en résolvant des énigmes dans des donjons périlleux, et en combattant des créatures mythologiques, le joueur devra affronter des boss redoutables, découvrir des secrets cachés et améliorer son équipement pour atteindre son but ultime.

## **Fonctionnalités**
- **Exploration en VR** : Un monde ouvert richement détaillé, où chaque zone, village, et donjon offre des défis uniques et des opportunités de progression.
- **Système de combat dynamique** : Utilisation des contrôleurs VR pour effectuer des attaques, parer, et esquiver dans des affrontements intenses conter des créatures et des boss.
- **Evolution du personnage** : Déblocage de compétences et amélioration d'équipement à mesure que le joueur progresse dans le jeu.
- **PNJ interactifs** : Renconters avec des personnages importants qui offrent des quêtes secondaires, des informations et des récompenses rares.
- **Quêtes scénarisées** : Des missions de longue haleine, des énigmes à résoudre, et des batailles épiques contre des boss pour récupérer des fragments du Coeur d'Eryndor.
- **Personnalisation** : Le joueur peut améliorer son armement, ses compétences et son apparence au fil des réussites.

## **Zones Principales**
- **La Cité d'Alderan** : Un point de départ central avec des PNJ (Personnage Non Joueur) qui offernt des quêtes, des informations, et des équipements.
- **Les Plaines Oubliées** : Un vaste terrain de chasse où le joueur peut s'entraîner, récolter des ressources, et combattre des créatures.
- **Les Donjons des Cinq Echos** : Des donjons énigmatiques où chaque pièce du Coeur d'Eryndor est cachée, avec des énigmes, des pièges, et des combats de boss.

## **Commandes** 
- **Déplacements** : Utilise les contrôleurs VR pour te déplacer à travers le monde d'Eryndor. Suis les intructions à l'écran pour naviguer en toute fluidité.
- **Combat** : Effectue des attaques en balançant tes bras, pare avec un geste défensif, et esquive les attaques ennemies en bougeant ton corps.
- **Interaction** : Appuie sur les boutons de ton contrôleur pour interagir avec les PNJ, ouvrir des coffres, et résoudre des énigmes.
- **Menu** : Utilise le joystick pour avvéder au menu principal, où tu peux sauvegarder ta progression, gérer ton inventaire et consulter la carte du royaume.

## **Installation**

### Prérequis
- **Plateforme** : Le jeu est développé pour la réalité virtuelle. Tu auras besoin d'un casque VR compatible et ses contrôleurs.
- **Système d'exploitation** : Windows 10 ou supérieur.
- **VR Setup** : Un environnement VR prêt avec des capteurs et une configuration correcte des contrôleurs.
- **Version de Unity** : La version de Unity pour le développement d'Eryndor est ``` 2022.3.52f1```

### Installation
1. **Clone du Repository**
    - Clone ce repository sur ton ordinateur à l'aide de la commande suivante ;
        ```bash
        git clone https://github.com/Lecureur-Arthur/Eryndor.git
        ```
    
2. **Installation des Dépendances**
    - Assure-toi d'avoir installé Unity avec les packages VR requis (SteamVR, Oculus, ect.).
    - Ouvre le projet dans Unity et installe toutes les dépendances nécessaires.
    - Pour les utilisateurs de SteamVR, assure-toi que ton environnement SteamVR est correctement configuré.

3. **Lancer le Jeu**
    - Une fois les dépendances installées et le projet ouvert dans Unity, clique sur "Play" pour tester le jeu dans l'éditeur.
    - Si tu souhaites créer une version standalone, utilise les options de build de Unity pour générer une version exécutable.

## **Structure du repository**
```
/Eryndor
│
├── Assets/            # Tous les assets du jeu (modèles, textures, scripts, etc.)
├── Scenes/            # Les scènes du jeu
├── Scripts/           # Tous les scripts du jeu
│   ├── Combat/        # Scripts de combat
│   ├── Quests/        # Scripts de gestion des quêtes
│   └── UI/            # Scripts de l’interface utilisateur
├── Documentation/     # Documentation technique et de conception
├── README.md          # Ce fichier
└── ProjectSettings/   # Paramètres de Unity
```

## **Licences**
Ce projet est sous la licence **MIT**. Consulte le fichier `LICENSE` pour plus de détails.
