# Largeur de bordure CSS

La "border-width" propriété spécifie la largeur des quatre bordures.

La largeur peut être définie comme une taille spécifique (en px, pt, cm, em, etc.) ou en utilisant l'une des trois valeurs prédéfinies : fine, moyenne ou épaisse :

p.one {
  border-style: solid;
  border-width: 5px;
}

p.two {
  border-style: solid;
  border-width: medium;
}

p.three {
  border-style: dotted;
  border-width: 2px;
}

p.four {
  border-style: dotted;
  border-width: thick;
}

# Largeurs latérales spécifiques

La border-width propriété peut avoir d'une à quatre valeurs (pour la bordure supérieure, la bordure droite, la bordure inférieure et la bordure gauche) :

p.one {
  border-style: solid;
  border-width: 5px 20px; /* 5px top and bottom, 20px on the sides */
}

p.two {
  border-style: solid;
  border-width: 20px 5px; /* 20px top and bottom, 5px on the sides */
}

p.three {
  border-style: solid;
  border-width: 25px 10px 4px 35px; /* 25px top, 10px right, 4px bottom and 35px left */
}