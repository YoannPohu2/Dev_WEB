# Éléments de citation et de citation HTML

Dans ce chapitre, nous passerons en revue les éléments HTML <blockquote>, <q>, <abbr>, <address>, <cite> et <bdo>.

# HTML <blockquote> pour les citations
L'élément HTML <blockquote>définit une section citée à partir d'une autre source.
Les navigateurs indentent généralement <blockquote>les éléments.
exemples:
<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
</blockquote>


# HTML <q> pour les citations courtes
La balise HTML <q> définit une courte citation.
Les navigateurs insèrent normalement des guillemets autour de la citation
exemples:
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>

# HTML <abbr> pour les abréviations
La balise HTML <abbr>définit une abréviation ou un acronyme, comme « HTML », « CSS », « M. », « Dr. », « ASAP », « ATM ».

Le marquage des abréviations peut fournir des informations utiles aux navigateurs, aux systèmes de traduction et aux moteurs de recherche.

Astuce : utilisez l'attribut de titre global pour afficher la description de l'abréviation/acronyme lorsque vous passez la souris sur l'élément. 
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>

# <adresse> HTML pour les informations de contact
La balise HTML <address>définit les coordonnées de l'auteur/propriétaire d'un document ou d'un article.
Les informations de contact peuvent être une adresse e-mail, une URL, une adresse physique, un numéro de téléphone, un identifiant de réseau social, etc.
Le texte de l' <address>élément est généralement rendu en italique et les navigateurs ajouteront toujours un saut de ligne avant et après l' <address>élément.
exemple:

<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>

# HTML <cite> pour le titre de l'œuvre
La <cite>balise HTML définit le titre d'une œuvre créative (par exemple un livre, un poème, une chanson, un film, une peinture, une sculpture, etc.).
Remarque : Le nom d’une personne n’est pas le titre d’une œuvre.
Le texte de l' <cite> élément est généralement rendu en italique .
Exemple
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>

# HTML <bdo> pour le remplacement bidirectionnel
BDO signifie Bi-Directional Override.

La balise HTML <bdo>est utilisée pour remplacer la direction actuelle du texte :
Exemple
<bdo dir="rtl">This text will be written from right to left</bdo>


