# Liens HTML

On trouve des liens dans presque toutes les pages Web. Les liens permettent aux utilisateurs de cliquer pour passer d'une page à l'autre

# Liens HTML - Hyperliens
Les liens HTML sont des hyperliens.
Vous pouvez cliquer sur un lien et accéder à un autre document.
Lorsque vous déplacez la souris sur un lien, la flèche de la souris se transforme en une petite main.

<!-- Remarque : un lien ne doit pas nécessairement être du texte. Un lien peut être une image ou tout autre élément HTML ! -->

# Liens HTML - Syntaxe
La balise HTML <a> définit un lien hypertexte. Sa syntaxe est la suivante :

<a href="url">link text</a>

L'attribut le plus important de l' <a> élément est l' hrefattribut, qui indique la destination du lien.
Le texte du lien est la partie qui sera visible pour le lecteur.
En cliquant sur le texte du lien, le lecteur sera envoyé à l'adresse URL spécifiée.
Exemple:
Cet exemple montre comment créer un lien vers W3Schools.com :

<a href="https://www.w3schools.com/">Visit W3Schools.com!</a>

Par défaut, les liens apparaîtront comme suit dans tous les navigateurs :

Un lien non visité est souligné et bleu
Un lien visité est souligné et violet
Un lien actif est souligné et rouge

Astuce : les liens peuvent bien sûr être stylisés avec CSS, pour obtenir un autre look !

# Liens HTML - L'attribut target
Par défaut, la page liée s'affiche dans la fenêtre de navigateur actuelle. Pour modifier cela, vous devez spécifier une autre cible pour le lien.

L' <target> attribut spécifie où ouvrir le document lié.

L' <target> attribut peut avoir l'une des valeurs suivantes :

<self> - Par défaut. Ouvre le document dans la même fenêtre/onglet où il a été cliqué
<_blank> - Ouvre le document dans une nouvelle fenêtre ou un nouvel onglet
<_parent> - Ouvre le document dans le cadre parent
<_top> - Ouvre le document dans le corps entier de la fenêtre

Exemple
Utilisez target="_blank" pour ouvrir le document lié dans une nouvelle fenêtre ou un nouvel onglet de navigateur :

<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>

# URL absolues et URL relatives
Les deux exemples ci-dessus utilisent une URL absolue (une adresse Web complète) dans l' hrefattribut.
Un lien local (un lien vers une page du même site Web) est spécifié avec une URL relative (sans la partie « https://www ») :

Exemple
<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>

# Liens HTML – Utiliser une image comme lien
Pour utiliser une image comme lien, il suffit de mettre le <img> tag à l'intérieur du <a>tag :
Exemple
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>

# Lien vers une adresse e-mail
Utilisez-le mailto:à l'intérieur de l' hrefattribut pour créer un lien qui ouvre le programme de messagerie de l'utilisateur (pour lui permettre d'envoyer un nouvel e-mail) :

Exemple
<a href="mailto:someone@example.com">Send email</a>

# Bouton comme lien
Pour utiliser un bouton HTML comme lien, vous devez ajouter du code JavaScript.
JavaScript vous permet de spécifier ce qui se passe lors de certains événements, comme un clic sur un bouton 

Exemple
<button onclick="document.location='default.asp'">HTML Tutorial</button>

# Titres des liens
L' title attribut spécifie des informations supplémentaires sur un élément. Ces informations sont généralement affichées sous forme d'info-bulle lorsque la souris passe sur l'élément.