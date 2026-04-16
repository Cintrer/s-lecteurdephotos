## Enoncé

Afficher une liste de photos sélectionnable d'un clic de souris, avec un message indiquant le nombre de photos sélectionnées à chaque instant.

## Consignes

### HTML

Dans l'en-tête de  la page :

* Ajouter un titre au programme : "Sélecteur de Photos".

Dans la partie principale de la page :

* Créer une liste (*id : photo-list*) affichant toutes les photos du dossiers *images*.
* Ajouter un paragraphe (*id : total*) avec le message "Vous avez sélectionné 0 photo(s)", le chiffre 0 devant s'afficher en italique.

### CSS

* Le nombre de photos sélectionnées doit s'afficher en rouge et en gras.
* Les photos doivent s'afficher les unes à côté des autres sur une largeur de 800 pixels, sans les puces, avec une marge de *1em* et un padding de *0.5em*.
* Au survol d'un élément de la liste *photo-list*, la couleur de fond devient grise (*silver*).
* Quand un élément de la liste *photo-list* à la classe *selected*, la couleur de fond devient verte (*forestgreeen*).
* Le changement de couleur de fond d'un élément de la liste *photo-list* doit s'animer.

### Interactions

* Quand on clique sur un élément de la liste *photo-list*, l'élément en question se voit affecter la class *selected* et le message avec le nombre de photos sélectionnées se met à jour. Un deuxième clic inverse l'opération.

## Détails

* Nommer correctement le gestionnaire d'évènements pour qu'il ait un sens.


## Fonctions utiles

* Utiliser la méthode querySelectorAll pour sélectionner les différentes photos: https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_document_queryselectorall_class
* Utiliser le mot clé this, pour sélectionner l'élément qui a déclencher l'évènement