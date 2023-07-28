
# Projet CDA - Mars 2023 à Mars 2024

## Étape 1 : Réflexions, idées de projets
Ce document a pour but de ranger vos idées concernant le sujet du projet.

Exemples :

- Gestionnaire de location de véhicule
- Gestionnaire de parc immobilier

Possibilités :

- Création d'un site qui rassemble l'ensemble des créations liées aux IA générative, (image, texte, vidéo, document) en libre accès. Les utilisateurs inscrits pourront déposer leur création etc… les utilisateurs non inscrits pourront utiliser toutes les données présentent sur le site… accessoirement intégré un prompt pour utiliser certaines IA sur le site même, "UN SEUL SITE, PLUSIEURS TYPES D'IA GENERATIVE"
- Création d'un site de streaming léger pour les streamers
- Planning TV internet (Twitch, YouTube).
- Comment créer un site Web qui regroupe tous les animés pour éviter de payer trop d'abonnement et juste payer un abonnement.

## Étape 2 : Création Personnas

Stats twitch: 
Analyse rapide :

### Alex Lior
https://fr.semrush.com/persona/edit/1e500281-a8d1-46ee-8fe0-faab3a62f4bc/
![](https://md.picasoft.net/uploads/upload_39ae886ceddfa7c6a7e15c9148ecb9d5.png)

### Barbara Laroche
https://fr.semrush.com/persona/edit/adb8b5b4-603a-4ff4-8e05-742a2b3351bb/
![](https://md.picasoft.net/uploads/upload_3d80c206bdeb9dd30a90de02141edc6b.png)

### Stan Laroche
https://fr.semrush.com/persona/edit/6020be91-dace-4032-b4ed-a7c8c6127f79/
![](https://md.picasoft.net/uploads/upload_08d8987292a7905e2e5d53883dd6080e.png)

### Anne Bitel
https://fr.semrush.com/persona/edit/edca7ebc-e629-4000-a162-16a91b87cf2b/
![](https://md.picasoft.net/uploads/upload_473ece555de847f7e6d6f70e53ab4459.png)

## Étape 4 : Brainstorming
![](https://cdn.discordapp.com/attachments/1045343696486412338/1101078679167184966/IMG_0370.jpg)
https://cdn.discordapp.com/attachments/1045343696486412338/1101078679167184966/IMG_0370.jpg
![](https://cdn.discordapp.com/attachments/1045343696486412338/1101078678403813416/IMG_0372.jpg)
https://cdn.discordapp.com/attachments/1045343696486412338/1101078678403813416/IMG_0372.jpg
![](https://cdn.discordapp.com/attachments/1045343696486412338/1101078678785499216/IMG_0371.jpg)
https://cdn.discordapp.com/attachments/1045343696486412338/1101078678785499216/IMG_0371.jpg


## Étape 5 : Liste des fonctionnalités

### Créateur veut créer un planning
1. Le créateur peut ajouter un contenu à son planning :
	1. Le créateur dispose d'un calendrier, lors d'un clic sur un contenu, ce contenu est ajouté au programme selon l'horaire/jour de sortie
	2. Le créateur ajoute directement depuis le calendrier un contenu, en cliquant sur une date/heure sélectionnée
    
### Créateur veut préparé la mise en prod
2. Le créateur peut préchargé ces vidéos pour être diffusé en temps et en heure sur la plateforme.
    1. Il peut définir une date/heure de sortie
    2. Il peut ajoute une miniature
    3. IL peut ajouter un titre
    4. Il peut ajouter une description
    5. etc ...
    6. (les vidéos sont automatiquement ajouté sur le planning)"


### Créateur veut partager son planning

* Le créateur peut partager son planning à ces followers


### Créateur veut partager son planning

* Le créateur peut partager son planning à ces followers

### L'utilisateur viewer veut regarder un programme

* L'utilisateur accède à un catalogue de programmes ou directement au contenu :
    * L'utilisateur peut lancer le programme ou un contenu du programme
        * TODO:
    * L'utilisateur ajoute le programme à son agenda
        *  TODO: 
    * Live dans un programme
        * TODO: l'utilisateur peut couper le live
    * Le live n'existe plus dans le programme annoncé
        * prévenir l'utilisateur
        * faire passer la vidéo "sécurité"

        
### Dictionnaire des termes

| Vidéos              | Récurrence          | Créateur            | Viewer             | Programme   |     |
|:------------------- | ------------------- | ------------------- | ------------------ | ----------- | --- |
| Durée site source   | Nom de l'émission   |                     |                    | Viewer      |     |
| Name du vidéaste    | Horaire             | Pseudo              | Pseudo             | Avis        |     |
| Title               | Jours de la semaine | Youtube             | Type de contenu    | Partage     |     |
| Commentaires        | Plateforme          | Twitch              | Youtube            | Miniature   |     |
| Heure de sortie     | Nom de la vidéo     | Nombre de Followers | Twitch             | TV          |     |
| Nombre de likes     | Quotidien           | Likes               | Follow             | Description |     |
| Nombre de dislikes  | Hebdomadaire        | Pubs                | Likes              | Titre       |     |
| Nombre de vues      | Mensuel             | Heures d'activités  | Abonnement         | Heure       |     |
| Commentaires        | Trimestriel         | Personnalité        | Heures d'activités | Jour        |     |
| Catégorie de vidéos | Semestriel          | Pays                | Pays               |             |     |
| Date de démarrage   | Annuel              | Émissions           | Age                |             |     |
|                     |                     | Age                 |                    |             |     |


### remarque pour le MCD

le pays d'un utilisateur est utile pour les stats (à voir en V2)
Dans le planning les lives programmés ne doivent pas dépasser sur une autre vidéo
    exemple : live programmé à 19h (durée indéterminée), vidéo programmé à 20h 
        alerte -> prévenir que la prochaine vidéo débutera à 19h (5 minutes avant)
        alerte ->  au moment du début de la vidéo, continuer sur le live ou couper et passer à la vidéo
            si l'utilisateur choisi de continuer la vidéo sera décalé sinon il passera à la vidéo


### Users stories


# Choix des techno
Typescript non négociable.
## Desktop :
### ReactJs : 
   Dynamique, facile d'apprentissage, grosse communautée derrière, Taux de satisfaction de 84%, DOM virtuel, Composants réutilisables
### Python : 
Multifonction, très apprécié, Multithread
## Choix du front : 
React car c'est très dynamique, facile d'apprentissage avec des composants réutilisables donc assez rapide à mettre en oeuvre.
![](https://md.picasoft.net/uploads/upload_05fe778d145c994003726205a91dc169.png)

  ## API :
### Django : 
Rapide, bien documenté, faible courbe d'apprentissage, grosse sécurité, grosse communauté, Multithread, bon ORM

### Laravel : 
Excellente Doc,Intégration rapide, Performant, Sécuriser, Manque de continuité entre les version, Qualité mitigé, pas très riche pour les appli mobile, courbe d'apprentissage élévée
    
### Ruby on rails : 
Flexibilité, Communauté, complexe et vitesse d'execution plus lente que la moyenne

### Express NodeJs: 
Unithread, Grosse courbe d'apprentissage

## Choix de l'api 
Nous avons décidés de prendre DJANGO parce qu'il a un large écosytème ainsi que de nombreuses bibliothèques qui facilite le développement d'API REST.
Bonnes performances de développement avec une syntaxe claire et expressive, Python a une grande bibliothèque standard.
Python est un langage productif, ce qui signifie qu'il permet de développer rapidement des applications fonctionnelles.

Python est un langage multiplateforme, il peut être utilisé pour créer des API REST qui fonctionnent sur différentes plateformes (macOS, Linux, Windows).
Flexibilité: Python offre la possibilité d'étendre les fonctionnalités de base du langage en utilisant des modules et des bibliothèques tierces & Capacité d'intégration avec d'autres langages et technologies.
Migration et portabilité : Python facilite la migration et la portabilité des API REST.
Scalabilité horizontale : Une stratégie couramment utilisée pour améliorer la scalabilité des API REST en Python consiste à adopter une approche de déploiement distribué, où plusieurs instances de l'API sont exécutées sur différents serveurs ou machines virtuelles. 
 ## Mobile : 
 React native
![](https://md.picasoft.net/uploads/upload_1dc744aa0211727d3c5fb494a06e6f11.png)


### Maquette
 Figma : https://www.figma.com/file/mtB6edybd5q3FTOzidEgrF/Planner-team-library?type=design&mode=design&t=hkdFSCQL42t6hH6V-0
