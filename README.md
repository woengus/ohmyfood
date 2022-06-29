 ---
 # OhMyFood
 ---
 Troisième projet openclassroom formation développeur Javascript React.

 Objectif: créer un site 100% mobile qui répertorie les menus de restaurant gastronomique, en utilisant HTML et Sass.

 Utilisation de keyframes, mixins, npm scripts
 lien du site: https://woengus.github.io/ohmyfood/index.html

 Animations imposées par le projet en css:

 Boutons

● Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
L’ombre portée devra également être plus visible.
● À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic.

Page d’accueil

● Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS. 

Pages de menu

● À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. 
● Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.
Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension.

 ---
 # Comment lancer le projet

 ---
 Installer node js si vous ne l'avez pas déja fait.

 git clone du repo

 npm install (vérifier que le dossier node_modules éxiste ainsi que package-lock.json)

 pour utiliser sass: npm install -g sass
 
 npm run sass (Pour que les fichiers scss et css soient mis à jour automatiquement et en même temps, création d'un script: sass --watch style.scss style.css)


 