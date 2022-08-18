# Jeu de serpent Part2
Ce jeu est construit sur deux jours (20 et 21) - au jour 21, nous traitons de l'héritage et du découpage de liste

Dans la partie 2 du jeu du serpent, nous allons nous attaquer aux 4 dérniers étapes:

## 1.Détectons la collision avec la nourriture 
  Notre serpent devrait etre capable de diriger vers un morceau de nourriture, qui sera une cercle bleu, et que chaque fois touche la nourriture, le cercle se déplace vers un nouvel emplacement aléatoire sur l'écran.
## 2.Créons un tableau de bord 
  Pouvoir écrire un texte dans notre programme qui garde une trace de la parition, du nombre des morceaux de nourriture que nous avons réusi à manger.
  Le score doit etre s'actualiser à chaque fois que nous touchons un nouveau morceau de nourriture et c'est va y rester et continuer à se mettre à jours chaque fois qu'on touche un nouveau nourriture. 
## 3.Détectons la collision avec le mur 
  Détecter une collision avec un mur. Nous voulons le serpent une fois qu'il a dépassé un certain point qui est trés proche des quatres murs pour déclencher la séquence de jeu.
  Donc nous avons créer une boite limitequi dit 280px et -280px pour l'axe des X ainsi pour les Y 280px à -280px. Puis dés que la tete du serpent touche l'un de ces positions alors on peut dire que le serpent à pratiquement frappé le mur et déclencher la fin du jeu.
## 4.Détectons la collision avec la queue
  Comme un seroent devient de plus en plus long, il est plus probable qu'à un moment donné, la tete puisse toucher une partie de la queue. Et dansce jeu cela signifie que la partie est terminée.
