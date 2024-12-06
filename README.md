# **Eryndor**

## **Description**
**Eryndor** est un jeu en réalité virtuelle (VR) qui plonge le joueur dans un univers fantastique riche et vivant, inspiré des jeux de rôle et des aventures en monde ouvert. Le joueur incarne un héros en quête de fragments du **Coeur d'Eryndor**, une mustérieuse relique ancienne dispersée à travers un royaume magique. En explorant des plaines sauvages, en résolvant des énigmes dans des donjons périlleux, et en combattant des créatures mythologiques, le joueur devra affronter des boss redoutables, découvrir des secrets cachés et améliorer son équipement pour atteindre son but ultime.


## **Installation**

### Prérequis
- **Plateforme** : Le jeu est développé pour la réalité virtuelle. Tu auras besoin d'un casque VR compatible et ses contrôleurs.
- **Système d'exploitation** : Windows 10 ou supérieur.
- **VR Setup** : Un environnement VR prêt avec des capteurs et une configuration correcte des contrôleurs.
- **Version de Unity** : La version de Unity pour le développement d'Eryndor est `2022.3.52f1` (pas nécessaire si vous télécharcher l'éxecutable du jeu ici)

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

Ulthar, le forgeron légendaire, incarne la force et la presévérence. Ses créations ne sont pas que des outils pour les aventuriers, mais des oeuvres imprégnées de l'histoire et du destin d'Eryndor.

### La sorcière Aelya
#### Lore
Aelya, surnommée la Sorcière des Arcanes, est une figure énigmatique et respectée du royaume d'Eryndor. Maîtraisse des arts magiques, elle habite une tour isollée à la lisière des Plaines Oubliées, où elle offre ses services aux aventuriers dignes de sa confiance.
#### Origines
Aelya est issue d'une lignée de mages puissants qui avaient juré de protéger le Coeur d'Eryndor. Après la fragmenetation du Coeur, elle s'est isolé, cherchant à comprendre l'origine de ce désastre et à restaurer l'équilibre magique du royaume. Ses recheches l'ont amenée à maîtriser des magies anciennes, oubliées depuis des siècles.
#### Rôles Actuel
Aelya est une alliée précieuse pour les aventuriers. Elle fournit des enchantements, enseigne des sorts puissants et partage ses connaissances sur les mystères d'Eryndor. Elle est également une gardienne de secrets liés aux Donjons des Cinq Echos et à leurs magie protectrice.
#### Personnalité
Aelya est aussi sage que mystérieuse. D'apparence froide et distante, elle est en réalité une allliée bienveillante pour ceux qui gagnent sa confiance. Elle parle peu, préférant guider les aventuriers par ses actions et ses énigmes. Sa patience est légendaire, mais elle n'a aucune tolérance pour les imprudents ou les égoïstes.
#### Sa plus Grande Peur
Aelya craint que le déséquilibre magique causé par la fragmentation du Coeur d'Eryndor ne conduise à l'effondrement total du royaume. Elle travaille sans relâche pour enseigner aux aventuriers comment maîtriser les forces magiques nécessaires à leur quête.
#### Interraction avec le joueur
- **Enchantements** : Aelya propose d'enchanter les armes et armures du joueur, augementant leur puissance ou ajoutant des effets spéciaux, comme des flammes ou des boucliers magiques.
- **Apprentissage de Sort** : Elle enseigne au joueur  des compétences magiques, comme des attaques élémentaires, des boucliers protecteurs ou des sorts de guérison.
- **Quête Magiques** : Aelya envoie parfois le joueur dans des lieux magiques oubliés pour récupérer des reliques ou des ingrédients nécessaires à ses rituels.
- **Révélations Mystiques** : En discutant avec elle, le joueur découvre des informations cruciales sur les Donjons des Cinq Echos, les origines du Coeur d'Eruyndor et les créatures corrompues qui hantent le royaume.
#### Sa Tour
La tour d'Aelya est un lieu unique dans Eryndor. Remplie de livres anciens, d'artefacts magiques et d'orbres brillant, elle est un havre de savoir et de puissance. L'intérieur de la tour semble défier les lois de la physique, offrant des passsages secrets et des visions mystiques pour ceux qui s'y aventurent.

Aely, la sorcière des Arcanes, est une gardienne de la magie et une alliée précieuse. Elle représente la quête de connaissance et de puissance, offrant aux aventuriers des outils et de leçons nécessaires pour triompher des ténèbres d'Eryndor
### Les erudit de la bibliothèque
#### Lore
Les Erudits de la Bibliothèques d'Alderan sont les gardiens du savoir du royaume d'Eryndor. Installé dans une majestueuse bibliothèque au coeur de la Cité d'Alderan, ils consacrent leur vie à l'étude, à la préservation et à la transimission des connaissances anciennes.
#### Origines
La bibliothèque d'Alderan a été fondée par les premiers mages et érudits du royaume, qui souhaitaient préserver l'histoire, la magie, et les récits héroïques d'Eryndor. Après la fragmentation du Coeur d'Eryndor, les Erudits ont joué un rôle essentiel en documentant les changements dans le royaume et en recherchant des solutions pou réparer ce qui a été brisé.
#### Rôles Actuel
Les Erudit ne sont pas des combattants, mais leur contribution est cruciale pour les aventuriers. Ils fournissent des cartes détaillées, des indices sur les Donjons des Cinq Echos et des récits sur les créatures et les pièges qui attendent les héros. Leur savoir est une arme invisible, capable de guider les plus courageux vers la victoire.
#### Personnalité
- **Maître Daryus, l'historien** : Expert en récits anciens et en légendes, il peut raconter les origines des donjons et révéler des indices cruciaux sur leurs secrets.
- **Lyra, la cartographe** : Elle dessine des cartes précises du royaume, aidant les aventuriers à naviguer dans les zones inconnues et à découvrir des passages cachés.
- **Thalos, le naturaliste** : Spécialiste des créatures et des plantes d'Eryndor, il fournit des informations sur les faiblesses des ennemis et sur l'utilisation des ressources naturelles.
- **Auren, le mage-érudit** : Il étudie la magie ancienne et offre des conseils sur les artéfacts magiques et les sorts nécessaires pour affronter les dangers des donjons.
#### La Bibliothèques d'Alderan
La bibliothèques est un lieu grandiose, rempli d'étagères imposantes, de livres anciens et d'artefacts mystiques. Des lumières magiques flottent dans l'air, éclairant les tables où les érudits travaillent sans relâche. Certains aventuriers y trouvent même des journaux laissés par d'autres héros, contenant des récit d'aventures passées et des avertissements pour ceux qui suivent leurs traces.
#### Interraction avec le joueur
- **Cartes et Indices** : Les Erudits fournissent des cartes détaillées et des informations sur les Donjons des Cinq Echos, aidant le joueur à planifier ses explorations.
- **Identification des Objets** : Les artefacts ou objets mystérieux découverts dans les donjons peuvent être identifiés par les Erudits, révélant leur utilité ou leur histoire
- **Histoires et Quêtes** : En discutant avec les Erudits, le joueur peut apprendre des récit sur l'histoire d'Eryndor et recevoir des quêtes secondaires, comme retrouver un livre perdu ou explorer un site oublié.
- **Conseils Stratégiques** : Avant d'entrer dans un donjon, les Erudits peuvent fournir des informations sur les pièges et les créatures spécifiques qu'il contient.

Les Erudits de la Bibliothèques d'Alderan incarnent la sagesse collective et la quête de vérité. Sans leur savoir, les aventuriers seraient aveugles face aux défis d'Eryndor. Grâce à leur guidance, les héros peuvent affronter les ténèbres avec un esprit éclairé et une détermination renouvelée.

### Le mercenaire Karos
#### Lore
Karos est un guerrier solitaire connu dans tout Eryndor pour son habilité au combat et sa nature énigmatique. Mercenaire de renom, il offre ses services aux aventuriers capables de payer son prix ou de proouver leurs valeur par des actes héroïques.
#### Origines
On sait peu de choses sur le passé de Karos. Certains racontent qu'il était autrefois un chevalier déchu, trahi par ses alliés et forcé de survivre seul. D'autres disent qu'il a toujours été vagabond, explorant les terres en quête de défis. Ce qui est sûr, c'est que son expérience et son instinct lui on permis de surviver dans les environnements les plus hostiles d'Eryndor.
#### Rôles Actuel
Karos est allié potentiel pour les aventuriers. Bien qu'il préfère travailler en solitaire, il est prêt à se battre aux côtés de ceux qu'il considère dignes de sa lame. Il est souvent trouvé dans des tavernes ou des campements isolés, où il attend le prochain contrat ou l'opportunité de se mesurer à des ennemis redoutables.
#### Personnalité
Karos est taciturne et direct. Il parle peu, préférant laisser ses actions parler pour lui. Il a un code d'honneur strict : il ne travaille pas pour ceux qu'il considère comme malhonnêtes ou cruels. Malgré son apparence froide, il possède un profond respect pou rles aventuriers courageux et un sens de la justice qui guide ses choix.
#### Compétences et Forces
Karos est un maître du combat rapproché, maniant une lame imposante avec une précision redoutable. Il est également un stratège expérimenté, capable d'analyser rapidement les forces et les faiblesses d'un adversaire. Sa présence sur le champ de bataille peut changer le cours d'un combat.
- **Attaques Dévastatrices** : Ses coups puissants peuvent briser les défenses les plus solides.
- **Techniques Spéciales** : Karos possède des mouvements uniques qu'il utilise pour désarmer ou neutraliser rapidement ses ennemis.
- **Instinct de Survie** : Habitué à combattre seul, il sait se défendre contre plusieurs ennemis à la fois.
#### Interraction avec le joueur
- **Allié Temporaire** : Karos peut accompagner le joueur dans des donjons ou des quêtes difficiles, offrant un soutien de combat inestimable.
- **Entrainement** : Il propose parfois des sessions d'entraînement au joueur, enseignant des techniques de combat avancées ou offrant des conseils tactiques.
- **Quêtes Spécifiques** : Karos peut demander l'aide du joueur pour régler des affaires personnelles, comme traquer un ennemi de longue date ou récupérer un objet précieux.
#### Son Campement
Karos installe souvent son campement près des Plaines Oubliées ou aux abords des Donjons des Cinq Echos. Son camp est simple, équipé de tout ce dont un guerrier pourrait avoir besoin : une forge rudimentaire, des armes soigneusement entretenues, et des provisions. Ces campements servent de refuge temporaire pour les aventuriers en quête de repos ou d'information.

Karos, le Mercenaire Vagabond, est un allié précieux pour ceux qui partagent ses valeurs et un adversaire redoutable pour ceux qui s'opposent à lui. Sa lame et son expérience sont des atouts qui peuvent faire la différence dans la quête pour restaurer le Coeur d'Eryndor.

## **Donjons**
### La crypte des âmes silencieuse

### La forêt des murmures perdus

### La caverne des flammes éternelles

### Le temple des vents déchaînés

### Le sanctuaire des eaux endormies

## **Boss**
### Le gardien sépulcral
Le Gardien Sépucral est l'un des premiers grands défis auxquels le joueur sera confronté dans *Eryndor*. Chargé de protéger l'un des fragments du Coeur d'Eryndor, ce boss imposant hante une mausolée antique, rempli d'obscurité et de pièges mortels.
#### Apparence
Le Gardien Sépucral est une entité massive et terrifiante, un amalgame d'os, de métal rouillé et de magie obscure. Son corps est enveloppé d'une aura noire, et ses yeux brillent d'un éclat spectral. Il brandit une gigantesque hallebarde corrodée et porte une arlure partiellement détruire, évoquant un ancien chevalier maudit.
#### Origines
Selon les légendes, le Gardien Sépulcral était autrefois un chevalier d'élite jurant fidélité au royaume d'Eryndor. Après la fragmentation du Coeur, il fut corrompu par les énergies sombres émanant des éclats dispersés. Transformé en une sentinelle sans âme, il est condamné à défendre son fragment conte quiconque tenterait de le récupérer.
#### Comportement
Le Gardien est une force implacable, combinant puissance brute et tactiques stratégiques. Bien qu'il semble lent à première vue, ses attaques sont dévastatrices st son intelligence tactiques le rend imprévisible.
- **Patrouille** : Avant le combat, le Gardien arpente son mausolée dans un silence menaçant, surveillant tout intrus.
- **Combativité** : Une fois engagé, il attaque sans relâche, utilisant la portée de sa hallebarde pour maintenir ses adversaires à distance.
#### Compétences
- **Coup de Hallebard** : Une attaues puissante en balayage, capable de toucher plusieurs cibles à la fois et d'infliger des dégâts massifs.
- **Frappe Spectrale** : Le Gardien canalise une énergie sombre dans son arme et frappe le sol, créant une onde de choc magique qui traverse la pièce.
- **Appel des Ombres** : Il invoques des âmes torturées pour distraire et attaquer le joueur, forçant ce dernier à gérer plusieurs ennemis à la fois.
- **Carapace Squelettique** : A mesure que ses points de vie diminuent, il renforce son armure avec des os environnants, réduisant les dégâts subis.
#### Stratégie pour le Battre
1. **Esquiver ses Balayages** : Rester mobile est crucial pour éviter les attaques larges de sa hallebarde.
2. **Exploiter les Fenêtres d'Ouverture** : Après une frappe au sol ou une invocation, le Gardien est vulnérables pendant quelques secondes.
3. **Gérer les Ombres** : Il est vital de neutraliser les âmes invoquées rapidement pour éviter d'être submergé.
4. **Armes Améliorées** : Des équipements bénis ou chargés de magie sacrée infligent des dégâts accrus au Gardien
#### Environnment
Le combat conter le Gardien se déroule dans une salle funéraire massive. Le sol est jonché d'ossements et les murs sont ornés de bas-reliefs représentant les batailles anciennes. Des piliers effondrés et des flammes spectrales offernt des couvertures temporaires, mais les zones sombres cachent parfois des pièges.
#### Récompenses
- **Fragment du Coeur d'Eryndor** : Le fragment protégé par le Gardien.
- **Hallebarde Sépulcrale** : Une version allégée de l'arme du boss, utilisable par le joueur.
- **Reliques Maudites** : Des objets magiques imprégnés d'énergie sombre, utiles pour renforcer les compétences ou créer des objets puissants.

Le Gardien Sépulcral représente une épreuve essentielle, testant les compétences du joueur en combat stratégique et en gestion des ressources. Sa défaite marque un tournant dans la quête pour restaurer Eryndor, prouvant que le héros est capable d'affronter les ténèbres les plus profondes.

### Le protecteur de la sylve
Le protecteur de la Sylve est le second boss majeur d'*Eryndor*. Ce gardien millénaire veille sur un fragment du Coeur d'Eryndor dissimulé dans une clairière enchantée, au coeur d'une forêt dense et mystérieuse. Mi-créature, mi-esprit, il est un avatar de la nature, à la fois majestueux et redoutable.
#### Apparence
Le Protecteur de la Sylve est une entité gigantesque composé d'écorce vivante, de vignes mouvantes, et de cristaux lumineux incrustrés dans son corps. Ses yeux luisent d'une lumière émeraude, reflétant la sagesse et la colère de la forêt qu'il protège. Il porte sur son dos un arbre ancien, dont les branches s'animent pour attaquer les intrus.
#### Origines
Créé par les anciens druides d'Eryndor pour protéger la nature conter les envahisseurs, le Protecteur de la Sylve est devenu l'ultime gardien de la forêt après la fragmentation du Coeur. Le fragment qu'il garde amplifie sa puissance et son lien avec la végétation environnante, mais l'a également rendu méfiant et agressif envers tous ceux qui pénètrent son domaine.
#### Comportement
Le Protecteur agit comme un juge implacable, testant la valeur de ceux qui osent s'approcher de son sanctuaire. Il attaque quiconque ne respecte pas l'équilibre de la forêt.
- **Territorial** : Il ne tolère aucune intrusion et utilisera les plantes de la forêt pour repousser les aventuriers avant même qu'ils atteignent son sanctuaire.
- **Colère de la Nature** : Une fois engagé, il utilise l'environnement à son avantage, rendant le combat dynamique et imprévisible.
#### Compétences
- **Attaqie des Branches** : Les branches de l'arbre sur son dos frappent violemment, infligent des dégâts à distance et immobilisant temporairement le joueur.
- **Vignes Enserrantes** : Des racines surgissent du sol pour entraver les mouvements du joueur, rendant l'esquive plus difficile.
- **Souffle de la Sylve** : Une attaque en zone où il libère un nuage de spores empoisonnées, forçant le joueur à chercher une zone dégagée.
- **Régénération Sylvestre** : Le Protecteur peut canaliser l'énergie de la forêt pour se soigner partiellement, obligeant le joueur à l'interrompre.
#### Stratégie pour le Battre
1. **Eviter les Racines** : Observer les mouvements du sol pour anticiper l'apparition des vignes et rester mobile.
2. **Cibler les Cristaux** :  Les cristaux incrustés dans son corps sont des points faibles qui amplifient les dégâts infligés.
3. **Uriliser le Feu** : Les armes imprégnés de feu ou d'énergie déstructrice sont particulièrement efficaces contre sa carapace d'écorce.
4. **Exploiter les Espaces Ouverts** : Eviter de se retrouver coincé dans les zones encombrées de végétation.
#### Environnement
Le combat se déroule dans une clairière circulaire entourée d'arbres massifs. Les racines, lianes et fleurs géantes présentes dans l'arène interagissent avec les actions du Protecteur, créant des obstacles et des dangers supplémentaires. Des clairières lumineuses apparaissent temporairement pour offrir un réput au joueur.
#### Récompenses
- **Fragment du Coeur d'Eryndor** : Protégé par le Protecteur.
- **Epée Sylvestre** : Une arme légère et rapide, imprégné de l'énergie naturelle, idéale pour des attaques rapides et infligeant des dégâts aux ennemis magiques.
- **Amulette de la Sylve** : Un talisman qui augmente la régénération de santé ou améliore la résistance aux poisons et malédictions.
#### Lien avec l'Histoire
La défaite du Protecteur de la Sylve représente plus qu'un simple triomphe : c'est une preuve que le joueur peut équilibrer force et respect de la nature. Cette victoire ouvre un passage vers les secrets de la forêt et fournit des indices essentiels sur la véritables nature du Coeur d'Eryndor.

Le Protecteur de la Sylve est un adversaire redoutable, mais aussi une incarnation de la beauté et de la fureur de la nature, offrant un combat mémorable dans l'aventure du joueur

### Le dragon de braise
Le Dragon de Braise est l'un des boss les plus redoutables d'*Eryndor*, incarant la puissance brute et la fureur des flammes. Gardien d'un fragment du Coeur d'Eryndor, il règne dans une caverne volcanique où la chaleur suffocante et les rivières de lave mettent à l'épreuve le courage et les compétences des aventuriers.
#### Apparence
Le Dragon de Braise est une immense créature écarlate recouverte d'écailles ardentes. Ses ailes membraneuses, bordées de flammes, illuminent la caverne lorsqu'il les déploie. Ses yeux brillent d'un feu incandescent, et chaque battement de son souffle envoie des étincelles et des flammes dans les airs. Son corps est orné de cicatrices et de runes luminescentes, vestiges de batailles passées.
#### Origines
Créature légendaire née du magma des montagnes d'Eryndor, le Dragon de Braise. Le fragment amplifie sa puissance, rendant ses flammes impossibles à éteindre. Il est vu comme un fléau par les villages environnants, mais aussi comme un symbole de grandeur et de respect.
#### Comportement
Le Dragon de Braise est une force incontrôlable, guidée par son instinct territorial et une colère brûlante envers les intrus.
- **Vol Dominant** : Il commence souvent le combat en s'élevant dans les airs, rendant difficile de l'atteindre directement.
- **Rage Pyrotechnique** : Plus le combat dure, plus le dragon devient agressif, augementant la fréquence et l'intensité de ses attaques.
#### Compétences
- **Soufle de Feu** : Un torrent de flammes dévastateur qui balaie l'arène, forçanct les joueur à essquiver ou à se réfugier derrière des rochers.
- **Pluis de Braise** : Le dragon s'élève dans les airs et libère une pluie de météores incandescents, infligeant des dégâts massifs en zone.
- **Coup de Queue** : Un balayage rapide avec sa queue écailleuse, efficace pour repousser les adversaires qui s'approchent trop près.
- **Aura de Chaleur** : a simple présence augemente la température de l'arène, drainant lentement la santé du joueur s'il reste immobile trop longtemps.
- **Eruption de lava** : Le dragon frappe le sol, provoquant des geysers de lave qui jaillissent aléatoirement dans l'arène.
#### Stratégie pour le battre
1. **Se Protéger des Flammes** : Porter des équipements résistants à la chaleur ou utiliser des potions de protection contre le feu est crucial.
2. **Observer les Attaques Aériennes** : Anticiper ses mouvements dans les airs pour éviter ses assauts dévastateurs.
3. **Utiliser des Armes à Distance** : Pendant qu'il vole, les arcs ou les sorts permettent de continuer à infliger des dégâts.
4. **Exploiter les Failles** : Après une attaque comme le Souffle de Feu, il devient vulnérable pendant quelques secondes.
#### Environnement
Le combat a lieu dans une gigantesque caverne volcanique, remplie de lacs de lave et de colonnes de pierre incandescentes. Des rochers tombent régulièrement du plafond, créant des obstacels ou des couvertures temporaires. Le terrain change au fil du combat, avec des zones qui s'effondrent dans la lave, réduisant les options pour se déplacer.
#### Récompenses
- **Fragment de Coeur d'Eryndor** : Gardé au coeur de la caverne.
- **Ecaille de Braise** : Une ressource rare permettant de forger des armures resistantes au feu ou d'améliorer des armes avec des dégâts supplémentaires de feu.
- **Anneau de Flamboyant** : Un artefact magique augementant la résistance aux flammes et la puissance des sorts élémentaires de feu.
#### Lien avec l'histoire
La victoire sur le Dragon de Braise est un moment de gloire pour le joueur, marquant un tournant dans la quête. Cet affrontement épique symbolise la capacité du héros à surmonter les épreuves les plus intenses. De plus, les villages voisins, libérés de la menace du dragon, offrent leur aide au joueur, enrichissant les options d'artisanat et d'approvisionement.

Le Dragon de Braise, avec sa puissance mythique et son arène spectaculaire, offre l'un des combats les plus mémorables de l'aventure, mélant stratégie, habilité et résistance

### L'aigle de la tempête
L'Aigle de la Tempête est un adversaire aérien redoutable, maître des cieux et gardien d'un fragment du Coeur d'Eryndor. Niché au sommet d'une montagne balayée par des vents violents et des orages incessants, cet imposant oiseau incarne la force et la majesté de la tempête.
#### Apparence
L'Aigle de la Tempête est gigantesque, avec uenenvergure d'ailes qui couvre presque tout l'arène. Son plumage est d'un bleu électrique et semble crépiter d'énergie, tandis que ses yeux étincellent comme des éclairs prêts à frapper. Ses griffes scintillent d'un métal noir, et des éclairs dansent sur ses ailes lorsqu'il s'élève dans le ciel.
#### Origines
Créature légendaire née d'une tempête millénaire, l'Aigle de la Tempête a été choisi pour veiller sur un fragment du Coeur d'Eryndor. Ses pouvoirs sont liés aux forces élémentaires du vent et de la foudre, et il est craint autant qu'admiré par les habitants des villages environnants.
#### Comportement
L'Aigle de la Tempête domine le champ de batailles avec ses attaques aériennes rapides et imprévisibles.
- **Vol Stratégique** : Il alterne entre des attaques à haute altitude et des piqués mortels pour déstabiliser le joueur.
- **Fureur Cyclonique** : Lorsqu'il est blessé, il intensifie ses attaques, déclenchent des tempêtes encore plus violentes.
#### Compétences
- **Plongeons Electrique** : Un piqué rapide où il frappe le joueur avec ses griffes, infligeant des dégâts physique et électriques.
- **Rafales de VEnt** : 

### Le serpent des abysses
Le Serpent des Abysses est un gardien redoutable des profondeurs, niché dans une grotte immergée où l'obscurité règne en maître. Protecteur d'un fragment du Coeur d'Eryndor, il incarne les mysthères et les dangers des eaux profondes.
#### Apparence
Cet immense serpent marin possède des écailles noires luisantes, réfléchisant une lumière bleutée lorsqu'il se meut dans l'eau. Ses yeux  rouges luisent dans l'obscurité, et ses crocs acérés dégagent une brume empoisonnée. Son coprs serpentin est couvert de cicatrices, vestiges des combats passés, et des algues matines s'accrochent à ses écailles.
#### Origines
Le Serpent des Abysses est une créature ancestrale née des profondeurs insondables d'Eryndor. Il est dit qu'il a été créé par els dieux pour protéger les secrets engloutis de l'océan et maintenir l'équilibre des forces mariens. Ce rôle sacré en fait une entité vénérée et redoutée par les marins.
#### Comportement
Le Serpent des Abysses utilise son environnement aquatique pour dominer le combat, alternant entre des attaques furtives et brutales.
- **Chasseur Patient** : Il attend que le joueur s'aventure trop loin ou fasse une erreur pour frapper rapidement.
- **Tactique de Submersion** : Il alterne entre les pronfondeurs et la surface, rendant le combat imprévisible.
#### Compétences
- **Frappe Eclair** : Une attaque rapide où le serpent surgit des profondeurs pour mrdre violement.
- **Brume Venimeuse** : Il libère une brume toxique qui empoisonne lentement le joueur, forçant à une esquive rapide ou à l'usage d'antidotes.
- **Mur d'Eau** : Une onde de choc qui repousse le joueur et pertube la visibilité sosu l'eau.
- **Enroulement Mortel** : Il tente d'enrouler son corps autour du joueur pour l'immobiliser et infliger des dégâts continus.
- **Appel des Profondeurs** : Lors de son attaque ultime, il invoque des tourbillons qui attirent le joueur vers des pièges ou zones dangereuses.
#### Stratégie pour le Battre
1. **Maîtriser le Combat Subaquatique** : Adapter ses déplacements dans l'eau pour éviter ses attaques et maintenir une bonne visibilité.
2. **Anticiper ses Aparitions** : Observer les ondulations de l'eau pour repérer son arrivé et contre-attaquer au bon moment.
3. **Utiliser des Armes Appropriées** : Les armes rapides et résistantes à l'eau sont essentielles pour ce combat.
4. **Gérer le Poison** : Préparer des antidotes ou des équipements réduisant les effets de son venin est crucial pour survivre.
#### Environnement
L****e combat se déroule dans une grotte sous-marine complexe, avec des tunnels étroits, des poches d'air pour reprendre son souffles, et des plantes bioluminescentes qui éclairent faiblement l'arène. Les courants marins ajoutent un défi supplémentaire, affectant les déplacemets du joueur.
#### Récompenses
- **Fragment du Coeur d'Eryndor** : La récompense centrales pour avoir vaincu le gardien aquatique.
- **Dent Abyssale** ****: Un matériau rare pour améliorer les armes avec des propriétés aquatiques ou empoisonnées.
- **Cape des Abyssale** : Un équipement qui améliore les capacités de nage et la résistance au poison.
#### Lien avec l'Histoire
En vainquant le Serpent des Abysses, le joueur prouve sa capacité à affronter les dangers des eaux profondes et surmonte ses peurs. Ce combat représente la confrontation directe avec les mystères inconnus et la bravoure nécessaire pour les affronter.

Les habitants des villages côtiers honorent le joueur en lui révélant des secrets sur les légendes marines et en partageant des objets rares en signe de gratitude.

Le Serpent des Abysses offre une expérience palpitant et unique, où la stratégie et la maîtrise des combats aquatiques sont mises à l'épreuve. 

## **Mobs**

## **Matériaux**
### Récoltables
### Armes
### Armures

## **Licences**
Ce projet est sous la licence **MIT**. Consulte le fichier `LICENSE` pour plus de détails.
