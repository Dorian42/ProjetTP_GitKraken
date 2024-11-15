# Dorian
Question n°1 : 
Décrivez l’interface de GitKraken et indiquez le rôle de chaque section principale.
Il y a des différents plusieurs interfaces notamment à gauche :
Local : Dépôt local, sur votre machine.
Remote : Dépôt distant (sur GitHub).
Code Patch : Ensemble de changements (modifications du code).
Issue : Suivi des bugs, des tâches ou des fonctionnalités dans le projet.
Teams : Groupes de collaborateurs ayant des permissions spécifiques sur un dépôt.
Tags : Marques spéciales dans l'historique des commits pour identifier des versions ou des points importants.
Submodule : Un dépôt Git inclus dans un autre projet Git.

VOIR IMAGE 1


Mais aussi, en haut il y plusieurs onglets :

VOIR IMAGE 2

Launchpad : Est une plateforme de développement et de gestion de projets, particulièrement utilisée dans l'écosystème des logiciels open source. 
Elle fournit des outils pour le suivi des bogues, la gestion des traductions, et le contrôle de version.
Release Notes : Sont des documents qui détaillent les changements effectués dans une nouvelle version d'un logiciel. 
ProjetTP_GitKraken : C’est mon repository, par défaut il n’y en a pas




Question n°2 :
Capturez et expliquez les étapes pour créer un dépôt avec GitKraken. Quelles options sont disponibles lors de l'initialisation d'un dépôt ?

VOIR IMAGE 3
Il faut aller sur GitKraken -> file -> Initialize a Repository -> Ensuite il faut choisir l’emplacement du dépôt.


Choisir l'emplacement du dépôt
Sélection du dossier : Une fenêtre vous demande de spécifier où vous souhaitez créer le dépôt local. Vous devez choisir un répertoire sur votre ordinateur qui contiendra le projet ou sinon vous pouvez choisir un autre emplacement.
-	Vous pouvez soit créer un nouveau dossier ou choisir un dossier existant.
-	Si le dossier spécifié n'existe pas encore, GitKraken le créera pour vous.

VOIR IMAGE 4

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Etape 2 : Travail sur les branches et les commits
Question 3 : Expliquer l'intérêt de créer des branches dans un projet Git.
Les branches sont essentielles dans un projet Git pour séparer les différentes tâches de développement, faciliter la collaboration entre plusieurs développeurs. Elles permettent une gestion fluide du travail et structuré.

Question 4 : Expliquez comment faire un commit avec GitKraken et capturez l'écran de votre commit.

VOIR IMAGE 5
Il faut aller sur la branche ou l’on veut faire le commit donc ici «main »

VOIR IMAGE 6
Et ensuite en bas à droite sur « initial commit » et update message






Question 5 : Pourquoi est-il important de pousser les branches vers le dépôt distant ?
Expliquez comment effectuer cette opération dans GitKraken.
Pour pousser les branches vers un dépôt distant est essentiel pour le travail collaboratif, la gestion des versions et la sécurité des données dans un projet Git. Cela vous permet non seulement de sauvegarder votre travail, mais aussi de collaborer efficacement avec d'autres développeurs.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Etape 3 : Gestion de merge et résolution de conflits

Question 6 : Décrivez ce qu’est un conflit Git et dans quelles situations il survient.
Un conflit Git se produit lorsque Git ne peut pas fusionner automatiquement deux ensembles de modifications incompatibles. Cela se produit généralement lorsqu'il y a des modifications concurrentes dans deux branches sur les mêmes parties du code.

Question 7 : Expliquez, étape par étape, la méthode de résolution de conflits dans GitKraken. Fournissez des captures d’écran pour illustrer.

Il faut faire un clic droit sur le fichier feature -> Fast-forward origin/feature to feature ->

VOIR IMAGE 7 & 8








Il faut cliquer sur le fichier sur le README.md car il y a une erreur orange

VOIR IMAGE 9

Il faut cliquer sur les 2 modifications pour les fusionner et ensuite cliquer sur SAVE en haut à droite en vert.

 VOIR IMAGE 10

Question 8 : Que signifie le terme “commit de merge” ?

Un commit de merge est un commit spécial dans Git, qui enregistre la fusion de deux branches. Il a deux parents et combine les changements des deux branches concernées dans un commit unique. Il permet de suivre l'historique des fusions et de conserver une trace claire des intégrations de branches dans le projet.












---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Étape 4 : Pull Request et collaboration
Création d’une Pull Request (PR) :
Question 9 : À quoi sert une Pull Request dans le flux de travail Git ? Décrivez comment créer une PR dans GitKraken et indiquez quelles informations sont requises.

Le Pull Request est un élément central dans les flux de travail collaboratifs de Git. Elle permet une gestion structurée des modifications, favorise les révisions de code et la collaboration entre les membres de l'équipe, tout en garantissant la qualité et la traçabilité des changements dans un projet.

Pour créer une PR, il faut aller sur le GitHub et retourner dans le repository.
Il faut cliquer sur : Compare & pull request et préciser les modifications qui ont été faites.

VOIR IMAGE 11 & 12



Question 10 : Expliquez la différence entre un merge direct et une Pull Request. Pourquoi la PR est-elle plus souvent utilisée dans les projets collaboratifs ?
La différence entre un merge direct et une Pull Request réside dans le processus de revue et de validation des modifications. La PR est importante dans les projets collaboratifs car elle permet de garantir la qualité du code, d'améliorer la communication entre les développeurs. C’est une pratique qui facilite la collaboration dans des projets d’équipe.

Étape 5 : Historique et tags (2 points) Consultation de l'historique des commits : Utilisez GitKraken pour afficher l’historique des commits
Question 11 : Comment l’interface de GitKraken aide-t-elle à visualiser les branches et les commits ? Expliquez les avantages de cet affichage graphique.

L’interface graphique de GitKraken offre une visualisation claire et intuitive des branches et des commits, ce qui facilite la gestion du code source. Les développeurs, qu'ils soient débutants ou expérimentés, peuvent naviguer, comprendre et manipuler l’historique des versions d'un projet plus facilement grâce à l’affichage graphique. Cela permet également de mieux gérer les conflits de fusion, de suivre l’évolution du code, et de rendre la collaboration au sein d’une équipe plus fluide et plus transparente.


Question 12 : Quelle est l’utilité des tags dans un projet Git, et comment les crée-t-on dans GitKraken ? 

Marquer des versions spécifiques :
•	Ils permettent de marquer des versions de release (par exemple v1.0.0, v2.1.1), facilitant ainsi le suivi des différentes versions du code.
Créer des points de restauration :
•	En cas de besoin, vous pouvez revenir à un tag pour réinitialiser votre environnement de travail à un état précis du projet, ce qui est particulièrement utile dans le cadre de déploiements ou de correctifs.
 Suivi de jalons :
•	Les tags permettent de suivre des étapes importantes du projet, comme la fin d'une phase de développement, la validation de la qualité du code, ou la réalisation d’une fonctionnalité clé.
Mise en production :
•	Lorsqu'une version stable du code est prête à être mise en production, un tag peut être créé pour marquer cet état. Cela garantit qu'aucune modification ultérieure n'affectera la version mise en production, sauf si un nouveau tag est créé pour une nouvelle version.
Faciliter le versionnement sémantique (SemVer) :
•	Les tags sont couramment utilisés dans les projets qui suivent des systèmes de versionnement sémantique (SemVer), où chaque nouvelle version du projet est marquée par un tag explicite.
Comment les crée-t-on dans GitKraken ?
Créer un tag :
•	Une fois le commit sélectionné, cliquez avec le clic droit sur ce commit dans le graphique.
•	Dans le menu contextuel, sélectionnez l’option "Create Tag".
Nommer le tag :
•	GitKraken vous demandera de donner un nom au tag. Ce nom peut être quelque chose comme v1.0.0 ou un autre nom significatif pour cette version particulière.
Optionnel - Ajouter une description :
•	Vous pouvez également ajouter une description au tag (par exemple, un changelog ou des détails sur cette version). C’est une bonne pratique pour documenter l’état du code ou les modifications apportées à ce moment précis.
Créer le tag :
•	Après avoir saisi le nom du tag (et éventuellement une description), cliquez sur le bouton "Create" pour créer le tag.

VOIR IMAGE 13
