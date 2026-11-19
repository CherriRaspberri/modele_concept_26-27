# LA TRIBUNE

Ce site présente la faisabilité d'un *concept d'expérience multimédia* présenté dans le cours *582-501MO Conception d'une expérience multimédia* au collège Montmorency enseigné par Thomas O Fredericks.

- [Lien vers le site web](https://jocrevier.github.io/JeuDeLimposteur/)
- [Lien vers le GitHub du projet](https://github.com/CherriRaspberri/modele_concept_26-27)

## Équipe

- **Jonathan Crevier** : Programmation
- **Olivier Laliberté** : Technique
- **Emmanuel Ricard** : Esthétique
- **Cédric Sirois-tanguay** : Scénario

## Résumé du projet

***La tribune*** est un jeu social de bluff basé sur le jeu du Caméléon. Dépendemment de son rôle, chaque joueur doit soit éliminer l'imposteur ou tenter de survivre jusqu'à la fin des rondes.

Au début du jeu, chaque joueur reçoit un rôle :
- **Commun** : Ce rôle tente de trouver l'imposteur le plus rapidement possible.
- **Imposteur** : Ce rôle tente de se camoufler à travers la foule.

Le jeu a des règles simples : 

1. Chaque ronde, une grille de 12 mots s'affiche sur l'écran central. 
2. Un mot secret commun est distribué à chaque joueur **commun**. 
3. À tour de rôle, chaque joueur, incluant l'imposteur, doivent écrire un mot qui se rapproche du mot secret. Chaque mot s'affiche ensuite sur l'écran central.
4. Une fois terminé, une phase de délibération est déclenchée et les joueurs peuvent argumenter sur qui serait l'imposteur. 
5. Chaque joueur doit voter pour la personne qui serait l'imposteur. La personne la plus votée est retirée de la partie.
6. Si l'imposteur est retiré, les **communs** gagnent. Sinon, la partie continue.

Au cours du jeu, les joueurs vont devoir interagir avec leur cellulaire et en personne. Le cellulaire sert à entrer des réponses qui seront affichées en temps réel sur l'écran central.



## Le parcours de l'interacteur

### Prérequis :
- *être au minimum 4 personnes.*
- *Avoir un téléphone portable qui a accès à internet.*

### Déroulement : 

Les interacteurs entrent dans la salle et prennent place. Sur l'écran central, un URL (ou un code QR) est affiché avec un room code. Les interacteurs doivent se connecter en allant sur le site web de la manière voulue et en entrant le room code. Ils doivent entrer un nom d'utilisateur et choisir une couleur qui les représentent.

Une fois l'authentification terminée, un court paragraphe de règles est affiché. L'interacteur en prend compte et lit les règles. Sur son cellulaire, un bouton "Je suis prêt" est affiché. Tous les interacteurs doivent appuyer sur leur bouton pour pouvoir commencer le jeu.

Un rôle secret est attribué à chaque joueur. Tous les joueurs sont des "communs", mais un joueur est "l'imposteur".

Le jeu se joue en un nombre de rondes égales au nombre de joueurs moins un. Par exemple, si il y a 5 joueurs, 4 rondes seront jouées.

À chaque ronde, ces étapes se répètent :

1. Sur l'écran central, les interacteurs voient une grille de 12 mots tous reliés avec le même thème. Les "communs" reçoivent un mot commun secret. L'imposteur n'en reçoit pas.

2. Chaque interacteur se voit attribuer un nombre aléatoire entre 1 et le nombre de joueurs. Ce nombre indique dans quel ordre les interacteurs doivent écrire leur mot "indice".

3. Quand le chiffre de l'interacteur s'affiche à l'écran, l'interacteur a 20 secondes pour trouver son mot "indice". Une boîte de texte s'affiche sur son écran de cellulaire. L'utilisateur entre son mot "indice" sur son cellulaire. Une fois trouvé, son mot reste affiché à l'écran, à côté de la grille de mots.

4. Une fois que chaque interacteur a écrit son mot, une minuterie de 1 minute s'affiche. Les joueurs doivent débattre sur qui éliminer. Sur chaque écran, une liste de tous les joueurs est affichée. Chaque interacteur va voter qui éliminer secrètement.

5. Une fois la minuterie terminée, les résultats sont affichés sur l'écran central. L'interacteur voté est éliminé et retiré de la partie.

Si l'imposteur est éliminé, le jeu prend fin automatiquement et les joueurs "communs" remportent la partie. Sinon, une prochaine ronde est jouée, et chaque interacteur garde son rôle.

Si l'imposteur arrive à rester en vie jusqu'à ce qu'il reste uniquement 2 joueurs, l'imposteur remporte la partie. S'il le veut, l'interacteur imposteur peut se prendre en photo. Le nom d'utilisateur et la photo prise par celui-ci sont gardées dans un "panthéon" des anciens imposteurs gagnants.

L'interaction avec l'installation prend fin.
