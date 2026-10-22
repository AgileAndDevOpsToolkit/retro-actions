
```
Voici un lien vers un tableau Google Sheet : https://docs.google.com/spreadsheets/d/1h77vQFeWivKEI3N1m9A-tZE3ybWDHz-qRb3N-qGtVIE/edit?usp=sharing
Dans un premier temps je voudrais que tu transformes ce tableau en fichier JSON :
[{Equipe : [{"Développement des compétences et partage de connaissances" : [ "Solliciter un expert externe", "Organiser une formation pour l'équipe", ...]}..}, {Produit : ...}, ...]
Je veux pouvoir filtrer les data par colonne. Au passage, dis-moi ce que tu penses de cette structure json que je te propose.
Ensuite, fais un site sous forme d'une page unique HTML/CSS/JS qui permet de filtrer les actions de rétro.
La première page du site contient le schéma que je mets en pièce jointe : si on clique sur un des éléments du schéma : équipe, Produit, Contexte, plan, ça affiche une autre page qui présente la liste des catégories liées au périmètre sélectionnée. Cette liste est affichée sous forme de gros badges cliquables (car il y a peu de catégories par périmètre). Ensuite si on clique sur une catégorie, ça affiche une nouvelle page avec une liste d'actions de rétro sous forme de badges. Les actions de rétro ne sont pas cliquables, c'est la fin de la navigation. On doit pouvoir revenir en arrière dans la navigation.
Programme bien
```

```
Pourquoi quand l'écran est pas large on a en plus en bas du schéma des grandes bulles ?
Même avec écran pas large, le schéma de base reste cliquable donc pas besoin de ces bulles.
De plus, sur le schéma, enlève l'affichage du nombre d'actions, on a pas besoin de cet info.
Enfin, la flèche n'a pas la bonne orientation : tu l'as mise horizontale mais elle doit être dans la direction cohérente avec l'extrémisé de la ligne noire
```

```
En fait je veux le fichier html et les datas du catalogue d'avions de rétro séparées dans un fichier .json
```