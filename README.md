# Orientation pour les dévellopeurs du projet LUMA

# 1. Typographie et fonts (Pour les dev) 🖋
## 🎯 Objectif : Look africain moderne, éducatif, accessible.
## Polices 
+ Ubuntu → moderne, arrondie, chaleureuse.
+ Poppins → lisible et professionnel.
+ Mukta → sobre, facile à lire.

## Utilisation dans le code (orientation) 👨🏾‍💻👩🏼‍💻
+ pour les titres : Ubuntu
+ pours les sous-titres : Mukta
+ pour les paragraphes : Poppins

# 2. Charte graphique (identité visuelle africaine) 🪶
## Couleur primaires de l'application
+ Orange - #FF8C42
+ Bleu pétrole - #1E4D6B
+ Blanc - #FFFFFF

## Utilisation dans le code (orientation au choix mais doit intégrer les principes)
+ Couleur primair des titres : orange ou bleu
+ Couleur primaire des sous-titres : orange
+ Couleur primaire du texte(paragraphes) : bleu
+ Courleur de fond (Background) : blanc ou bleu

# 3. Format des questions : ⁉
+ 60 questions en 6 étapes
+ Chaque question = 5 choix possibles (A, B, C, D, E)
    - A = Je déteste
    - B = Je n'aime pas
    - C = Neutre/indifférent
    - D = J'aime
    - E = J'adore
+ Les choix se font par selection d'un boutton radio

# 4. Fonctionnalités : 🚂
## Pages
+ page accueil
+ page a propos
+ page quizz
+ page résultat
    - n'est pas sur le menu
    - à afficher à l'utilisateur à la fin du quizz
+ page équipe
+ page profil : 
    - pour chaque membre du projet
    - en gros s'il y'a 10 membre d'équipes il faudra 10 sous pages
    - des sous page de la catégorie équipe
+ page contact

## Fonctionnalités & rendus
+ Progression animée pour le quizz : formulaire multi-étape avec barre de progression
+ Loader à l'ouverture du site

# 5. Intégration dans son environnement local ⏬
## Etape 0 : Explication 
+ chaque développeur du projet à une branche créer pour sa partie
+ chaque les branche de dev seront du style : dev-profilegithub [ex: dev-noumecha]
+ **Toujours travailler sur sa branche pour éviter les conflits** 

## Etape 1 : Téléchargement et intégration
+ Télécharger le projet dans son environnement local avec un : git clone https://github.com/Byt3Lab/luma
+ Faire un checkout pour aller sur sa branche : git checkout [nom-de-branche]
+ C'est bon tu peux taffer 🤩

## Etape 3 : pousser ses modifications en ligne
+ faire un commit normal : je sais que tu sais le faire (toujours faire son commit :D) après des modifications sur sa branche
+ vérifier s'il n'y a pas de conflit : avec git diff master
+ avant de pousser en ligne ses modification il faut toujours faire : git merge nom-devotre-branche
    - ceci pour intégrer les modification à la branche principale et être à jour avec ses modifications
+ puis creer un pull request :
     - étape 1 pour la pull : git push -u origin nom-devotre-branche
     - ensuite tu vas sur le lien que git t'aura donner dans le terminal pour creer ta pull request
     - tu ajoute une description des mofifications que tu as apporté au projet
     - tu clique sur **create a pull request**
     - après tu attends juste :D
+ une fois ta pull request créer l'admin du projet fera le reste - il intégrera tes modification à la branche principale
+ et puis bim c'est tout :D

# 6. Optionnelle 😁
+ Si tu veux voir l'évolution globale du projet en temps réelle et tester les choses
+ fait juste un git checkout master puis git pull 
+ puis double clique sur index.html pour voir à quoi ressemble le projet 😁🤩
