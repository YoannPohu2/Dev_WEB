# Documents HTML
Tous les documents HTML doivent commencer par une déclaration de type de document : <!DOCTYPE html>.  !

Le document HTML lui-même commence <html>et se termine par </html>.

La partie visible du document HTML est comprise entre <body>et </body> = élément définit le corps du document.

<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>

   ###### les éléments HTML ##########
Un élément HTML est défini par une balise de début, du contenu et une balise de fin.


# Titres HTML Les titres sont importants
Les en-têtes HTML sont définis avec les balises <h1>to <h6> sont des titres ou des sous titres que vous souhaiter afficher sur une page Web.
Les moteurs de recherche utilisent les titres pour indexer la structure et le contenu de vos pages Web.
Les utilisateurs parcourent souvent une page en fonction de ses titres. Il est important d'utiliser des titres pour montrer la structure du document.
<h1>Les titres doivent être utilisés pour les titres principaux, suivis des <h2>titres, puis des titres moins importants <h3>, et ainsi de suite

# Titres plus grands
Chaque titre HTML possède une taille par défaut. Cependant, vous pouvez spécifier la taille de n'importe quel titre avec l' styleattribut, en utilisant la propriété CSS font-size:
<h1 style="font-size:60px;">Heading 1</h1>

<h1>définit le titre le plus important. 
<h6>définit le titre le moins important :

# Paragraphes HTML
Les paragraphes HTML sont définis avec la balise <p> 
L'élément HTML <p> définit un paragraphe.
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

# Règles horizontales HTML
La <hr> balise définit une rupture thématique dans une page HTML et est le plus souvent affichée sous la forme d'une règle horizontale.
La <hr> balise est une balise vide, ce qui signifie qu'elle n'a pas de balise de fin.
# Sauts de ligne HTML
L'élément HTML <br>définit un saut de ligne.
À utiliser <br>si vous souhaitez un saut de ligne (une nouvelle ligne) sans commencer un nouveau paragraphe :
<p>This is<br>a paragraph<br>with line breaks.</p>

# Le problème du poème
Ce poème s'affichera sur une seule ligne :
<p>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</p>

# Solution - L'élément HTML <pre>
L'élément HTML  <pre>définit un texte préformaté.
Le texte à l'intérieur d'un <pre>élément est affiché dans une police à largeur fixe (généralement Courier) et préserve les espaces et les sauts de ligne :

<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>


# Liens HTML
Les liens HTML sont définis avec la <a>balise :
<a href="https://www.w3schools.com">This is a link</a>


# Images HTML
Les images HTML sont définies avec la <img>balise.

Le fichier source ( src), le texte alternatif ( alt), widthet heightsont fournis comme attributs :
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">

# Éléments HTML vides
Les éléments HTML sans contenu sont appelés éléments vides.

La <br>balise définit un saut de ligne et est un élément vide sans balise de fermeture :
<p>This is a <br> paragraph with a line break.</p