# FeelingsComment

Cette application à été réalisé dans le cadre d'un projet universitaire en groupe.

## Application de sentiment d'un commentaire

Cette application repose sur un modèle développé en python qui retourne si un commentaire saisie est positif ou négatif.
La partie front-end à été développé sur le framework Flask en Python et HTML/CSS.

Lorsque l'utilisateur arrive sur la page, il lui est possible de saisir un unique commentaire. Dans le cas ou l'utilisateur souhaite saisir et analyser plusieurs commentaires, il est possible d'ajouter une nouvelle zone de saisie à chaque clic sur un bouton le mentionnant.


Après avoir saisi et transmit le formulaire, l'utilisateur est redirigé vers une page contenant un tableau dont les catégories correspondent aux commentaires, au résultat retourné du modèle (Positif ou Négatif), ainsi que la possibilité de corriger dans le cas ou le modèle retourne un mauvais résultat.

Dans le cas ou le modèle retourne une mauvaise prédiction, le commentaire est ajouté aux données d'apprentissage afin de corriger le modèle et lui permettre une meilleure prédiction.
