## 1. Présentation

A quel besoin répondons-nous ?

Nous mettons en place un site internet pour une association participant à un rallye (Europ'Raid) pour collecter des dons.

-> Description super intéressante :

L'europraid est un rallye solidaire fait en Peugeot 205. Ce rallye est fait en 22 jours à travers l'Europe (10 000 km parcouru) et permet de distribuer 70 kg de matériel collecté en France, à destination de personnes démunis dans une vingtaine de pays d'Europe . Ce rallye est réalisé par 3 coéquipiers. 

L'application web va permettre de collecter des dons, écrire des articles de blog, envoyer des newsletter aux sponsors. Bref pour présenter l'équipe, le rallye ou tout simplement leur but, travailler l'image de marque de l'association et communiquer.

## 2. Parcours utilisateur
Décris le parcours utilisateur: 

![picture](Desktop/Parcours_utilisateur.png)

I. Considérer: Particuliers: "Je recherche des associationsà soutenir. Je souhaite faire un don."
               Entreprises: "je souhaite améliorer mon image de marque/notoriété"

II. Evaluer: Je découvre le site de l'équipe "Raidators" participant à un rallye solidaire.

III. Faire un don/suivre: Je souhaite participer à leur mouvement en faisant un don (matériel ou financier). Je souhaite les suivre pour voir leur avancée dans la collecte.

IV. Recommander/bouche à oreille: Particuliers: Je recommande à mes amis. J'en parle dans mon entourage.
                                  Entreprises: je propose à mes partenaires/fournisseurs.
 

## 3. Concrètement et techniquement

- Création d'un site internet en rails ( faisant appelle à nos connaissances acquises ces dernières semaines (des commentaires sur les articles/aimer les articles/les partager)

Site accessible à la partie sponsors/users/particuliers:
- Espace login pour que les sponsors puissent se connecter et récupérer un justificatif précisant la nature de son don (espace utilisateur avec mot de passe),
- Espace "Mon profil": logo, nom de l'entreprise, description
- Une page de justificatif paiement
- La possibilité au éventuel sponsors de voir les disponibilité d'espace où mettre leur logo sur la voiture (uploader son logo)
- Newsletter

Site accessible à l'administrateur:
- Une interface pour administrateur (creation d'article/evenement, accès à la base de donnée)


Site accessible au publique (possibilité de voir les pages suivantes sans être connecté):
- Présentation du projet/ équipe/ sponsors actuels
- Une page pour voir articles/evenement
- Une page permettant le paiement des dons.
- La possibilité au éventuel sponsors de voir les disponibilité d'espace où mettre leur logo sur la voiture 



### 3.1. Base de données
Comment tu vois la base de données de l'application ?

- Des "Users". 
- Des "Articles/Evenements" à référencer et tracker dans la BDD.
- Des "Administrateurs"
- Des "participants"

### 3.2. Front
Quels sont les composants dont vous aurez besoin ? Aurez-vous besoin d'un peu de front dynamique avec JavaScript pour la faire fonctionner ? 

Nous aurons surement besoin de front dynamique afin de rendre le site plus esthétique et attractif.

### 3.3. Backend
De quoi avez-vous besoin pour le backend ? Quelles sont les APIs en back que vous allez brancher et utiliser ?

- Stripe
- Devise
- Heroku
- Exporter CSV Postgresql
- Mailer Sendgrid
(Notification SMS ou commentaire ?)
- Wicked_pdf pour les devis et autre document
- ActivStorage
- Dotenv
(Ajout de vidéos ?)

### 3.4. Mes besoins techniques
Balance ici tes compétences, puis tes besoins pour les 3-4 personnes restantes.

J'ai déjà une équipe.


## 4. La version minimaliste mais fonctionnelle qu'il faut avoir livré la première semaine

Les visiteurs peuvent s'enregistrer sur le site pour faire des dons. Lorsqu'ils sont inscrits, ils ont accès à leur profil avec le justificatif de paiement dessus. Nous nous occuperons d'envoyer des mails à la mains pour communiquer avec les inscrits.
Le site internet avec les pages globales.

## 5. La version que l'on présentera aux jury
La deuxième semaine vous allez ajouter des fonctionnalités pour améliorer l'expérience utilisateurs de votre application. Quelles fonctionnalités tu aimerais bien ajouter ?

Site avec toutes les fonctionnalités en 3.2

## 6. Notre mentor

Notre mentor est Charlotte Favier (La big bosse)