# **Eryndor**

## **Description**
**Eryndor** est un jeu en réalité virtuelle (VR) qui plonge le joueurs dans un univers fantastique riche et vivant, inspiré des jeux de rôle et des aventures en monde ouvert. Le joueur incarne un héros en quête de fragments du **Coeur d'Eryndor**, une mustérieuse relique ancienne dispersée à travers un royaume magique. En explorant des plaines sauvages, en résolvant des énigmes dans des donjons périlleux, et en combattant des créatures mythologiques, le joueur devra affronter des boss redoutables, découvrir des secrets cachés et améliorer son équipement pour atteindre son but ultime.


## **Installation**

### Prérequis
- **Plateforme** : Le jeu est développé pour la réalité virtuelle. Tu auras besoin d'un casque VR compatible et ses contrôleurs.
- **Système d'exploitation** : Windows 10 ou supérieur.
- **VR Setup** : Un environnement VR prêt avec des capteurs et une configuration correcte des contrôleurs.
- **Version de Unity** : La version de Unity pour le développement d'Eryndor est `2022.3.52f1`

### Récupération du projet Unity
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

## **PNJ**
### Le maître des aventuries
#### Lore
Le Maître des Aventuriers, également connu sous le nom de Kaelion l'Ecrairé, est une figure emblématique de la Cité d'Alderan. Jadis un aventurier d'une renommée sans égale, Kaelion a exploré les moindres recoins du royaume d'Eryndor, vaincu des créatures mythiques et survécu aux dangers des Donjons des Cinq Echos. Il est aujourd'hui le guide des nouveaux héros qui aspirent à suivre ses traces.
#### Origine
Né dans un village reculé des Plaînes Oubliées, Kaelion a découvert très jeune une affinité particulière avec la magie et l'épée. Après la destruction de son village par une horde de créatures obscures, il a juté de consacrer sa vie à protéger Eryndor. Ses exploits l'ont conduit à devenir une légende vivante.
#### Rôle Actuel
Installé dans une grande salle ornée de trophée de ses aventures passées, Kaelion dispense des conseils, des quêtes et des défis aux aventuriers. Il est à la fois mentor, stratège et historien. En échange de leurs efforts, il récompense les joueurs avec des équipements rares ou des fragments d'histoires oubliées.
#### Personnalité
Kaelion est un homme sage et bienveillant, mais il reste exigeant envers ceux qu'il juge dignes de devenir de véritables aventuriers. Son discours inspire courage et persévérence, et il n'hésite pas à raconter ses propres échecs pour enseigner les leçons.
#### Sa plus Grande Crainte
Malgré sa sagesse et son expérience, Kaelion porte en lui un lourd fardeau : il est le dernier gardien du Coeur d'Eryndor. Ayant auterdois échoué à protéger l'intégralité du royaume, il craint qu'une nouvelle génération d'aventuriers ne soit pas à la hauteur des défis qui les attendent.
#### Interactions avec le joueur
- **Introduction** : Kaelion acceuille le joueur dans la Guilde des Aventuriers et explique l'importance des fragments du Coeur d'Eryndor.
- **Quêtes Secondaires** : Il propose des quêtes de chasse, de récupération d'objets rares, et de reconnaissance de zones inexplorées.
- **Mentorat** : Il enseigne au joueur les bases du combat et les stratégies spécifiques pour affronter les boss des donjons.

 Kaelion, le Maître des Aventuriers, est plus qu'un simple guide : il est une source d'inspiration pour tous ceux qui cherchent à devenir des héros dans le monde d'Eryndor.

### Le forgeron Ulthar
#### Lore
Ulthar est le maître-forgeron d'Eryndor, réputé pour son savoir-faire inégale et ses créations d'armes et d'armures imptégnées de magies ancienne. Installé dans sa forge, au coeur de la Cité d'Alderan, il est un allié essentiel pour tout aventurier cherchant à suivivre aux dangers du royaume.
#### Origines
Ulthar est né dans une lignée de forgerons installée depuis des générations à Alderan. Cependant, il a surpassé ses ancêtres grâce à sa cursioté insatiable pour les anciennes techniques de forge perdues et sa facination pour les minerais rares. Après avoir découvert l'existance du Mithral Céleste dans un des Donjons des Cinq Echos, il a consacré sa vie à repousser les limites de son art.
#### Rôles Actuel
Ulthar est le pilier de la communauté des aventuriers. Sa forge est l'endroit où les héros viennent renforcer leurs armes, améliorer leurs armures ou confectionner des équipements spéciaux à partir des ressources récoltées. C'est aussi in gardien de secrets, car ses connaissances sur les matériaux rares et les artéfacts perdus sont inestimables pour comprendre l'histoire d'Eryndor.
#### Personnalité
Ulthar est un homme bourru mais juste. Derrière son apparence sévère se cache une âme passionnée, profondément respectueuse des aventuriers qui osent braver les dangers. Il a un faible pour les jeunes héros qui lui rappellent sont propre courage d'antant, mais n'hésite jamais à les pousser à depasser leurs limites.
#### Sa plus Grande Fierté
La création de l'Eclat d'Ombracier, une lame légendaire qui, selon la légende, serait capable de sceller ou de détruire le mal. Cette arme repose dans un endroit secret qu'Ulthar ne dévoilera qu’au héros qu’il jugera digne de la manier. 
#### Interraction avec le joueur
- **Amélioration d'Equipement** : Ulthar peut renforcer les armes et armures du joueur grâce au minerais et matériaux rares récoltés dans les donjons.
- **Confection Spéciales** : Avec des plans spécifiques ou des ressources uniques, il peut forger des objets exceptionnels, comme des amulettes protectrices ou des armes magiques.
- **Histoires Cachées** : En parlant avec lui, le joueur peut découvrir des fragments de l'histoire d'Eryndor et des secrets sur les Donjons des Cinq Echos.
- **Quêtes Spécifiques** : Ulthar envoie parfois le joueur à la recherche de minerais oubliés ou de composants nécessaires à ses créations.
#### Sa Relation avec Kaelion  
Ulthar respecte profondément Kaelion, qu’il considère comme un symbole d’honneur et de courage. Ensemble, ils représentent les deux piliers du soutien aux aventuriers : la sagesse stratégique et la force matérielle. Leur amitié, forgée dans les épreuves, est une source d’inspiration pour ceux qui les croisent.

Ulthar, le forgeron légendaire, incarne la force et la presévérence. Ses créations ne sont pas que des outils pour les aventuriers, mais des oeuvres imprégnées de l'histoire et du destin d'Eryndor.

### La sorcière Aelya
#### Lore
#### Origines
#### Rôles Actuel
#### Personnalité
#### Sa plus Grande Fierté
#### Interraction avec le joueur

### Les erudit de la bibliothèque
#### Lore
#### Origines
#### Rôles Actuel
#### Personnalité
#### Sa plus Grande Fierté
#### Interraction avec le joueur

### Le mercenaire Karos
#### Lore
#### Origines
#### Rôles Actuel
#### Personnalité
#### Sa plus Grande Fierté
#### Interraction avec le joueur

## **Boss**
### Le gardien sépulcral

### Le protecteur de la sylve

### Le dragon de la sylve

### L'aigle de la tempête

### Le serpent des abysses

## **Mobs**

## **Donjons**
### La crypte des âmes silencieuse

### La forêt des murmures perdus

### La caverne des flamme éternelles

### Le temple des vents déchînés

### Le sancutaire des eaux endormies

## **Matériaux**
### Récoltables
### Armes
### Armures

## **Licences**
Ce projet est sous la licence **MIT**. Consulte le fichier `LICENSE` pour plus de détails.