# HTML Attributes

Les attributs HTML fournissent des informations supplémentaires sur les éléments HTML.

Attributs HTML
Tous les éléments HTML peuvent avoir des attributs
Les attributs fournissent des informations supplémentaires sur les éléments
Les attributs sont toujours spécifiés dans la balise de début
Les attributs sont généralement fournis sous forme de paires nom/valeur comme : nom="valeur"

# L'attribut href
La <a>balise définit un lien hypertexte. L' hrefattribut spécifie <l'URL> de la page vers laquelle le lien pointe :
<a href="https://www.w3schools.com">Visit W3Schools</a>

# L'attribut src
La <img>balise permet d'intégrer une image dans une page HTML. L' <src> attribut spécifie le chemin d'accès à l'image à afficher :
<img src="img_girl.jpg">

Il existe deux manières de spécifier l'URL dans l' src attribut 

# 1. URL absolue 
- Liens vers une image externe hébergée sur un autre site Web. Exemple : src="https://www.w3schools.com/images/img_girl.jpg" .

# 2  URL relative 
- Liens vers une image hébergée sur le site Web. Ici, l'URL n'inclut pas le nom de domaine. Si l'URL commence sans barre oblique, elle sera relative à la page actuelle. Exemple : src="img_girl.jpg". Si l'URL commence par une barre oblique, elle sera relative au domaine. Exemple : <a src="/images/img_girl.jpg"></a>.

# Les attributs de largeur et de hauteur

La <img> balise doit également contenir les attributs widthet height, qui spécifient la largeur et la hauteur de l'image (en pixels) :

<img src="img_girl.jpg" width="500" height="600">

# L'attribut alt

L'attribut required altde la <img> balise spécifie un texte alternatif pour une image, si l'image ne peut pas être affichée pour une raison quelconque. Cela peut être dû à une connexion lente, à une erreur dans l' srcattribut ou à l'utilisation d'un lecteur d'écran par l'utilisateur.

<img src="img_girl.jpg" alt="Girl with a jacket">

# L'attribut style

L' <style> attribut est utilisé pour ajouter des styles à un élément, tels que la couleur, la police, la taille, etc.

<p style="color:red;">This is a red paragraph.</p>

# L'attribut lang

Vous devez toujours inclure l' langattribut à l'intérieur de la <html> balise, pour déclarer la langue de la page Web. Cela est destiné à aider les moteurs de recherche et les navigateurs.

L'exemple suivant spécifie l'anglais comme langue : 
<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>

# L'attribut du titre
L' title attribut définit des informations supplémentaires sur un élément.

La valeur de l'attribut titre s'affichera sous forme d'info-bulle lorsque vous passerez la souris sur l'élément 

<p title="I'm a tooltip">This is a paragraph.</p>

# Nous suggérons : Toujours utiliser des attributs en minuscules le W3C recommande des attributs minuscules dans HTML et exige des attributs minuscules pour des types de documents plus stricts comme XHTML. !!!!

# Résumé du chapitre
Tous les éléments HTML peuvent avoir des attributs
L' hrefattribut de <a>spécifie l'URL de la page vers laquelle le lien mène
L' srcattribut de <img>spécifie le chemin vers l'image à afficher
Les attributs widthet de fournissent des informations sur la taille des imagesheight<img>
L' altattribut de <img>fournit un texte alternatif pour une image
L' styleattribut est utilisé pour ajouter des styles à un élément, tels que la couleur, la police, la taille, etc.
L' langattribut de la <html>balise déclare la langue de la page Web
L' titleattribut définit des informations supplémentaires sur un élément