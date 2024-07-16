# styles HTML - CSS

CSS signifie feuilles de style en cascade.

Le CSS permet d'économiser beaucoup de travail. Il permet de contrôler la mise en page de plusieurs pages Web à la fois.

Qu'est-ce que CSS ?
Les feuilles de style en cascade (CSS) sont utilisées pour formater la mise en page d'une page Web.

Avec CSS, vous pouvez contrôler la couleur, la police, la taille du texte, l'espacement entre les éléments, la manière dont les éléments sont positionnés et disposés, les images d'arrière-plan ou les couleurs d'arrière-plan à utiliser, les différents affichages pour différents appareils et tailles d'écran, et bien plus encore !

Le terme « cascading » signifie qu'un style appliqué à un élément parent se transmet à tous ses éléments enfants, sauf si un autre style est spécifié pour ces enfants. Par exemple :

Si vous définissez la couleur du texte du corps (<body>) sur « bleu », tous les titres (<h1>, <h2>, etc.) et paragraphes (<p>) dans le corps seront également en bleu, à moins que vous ne spécifiiez une autre couleur pour ces éléments

HTML
<body>
    <h1>Titre principal</h1>
    <p>Ce texte sera en bleu.</p>
    <div>
        <p>Ce texte sera également en bleu.</p>
    </div>
</body>
CSS
body {
    color: blue;
}

Si vous définissez la taille de la police d'un conteneur (<div>), tous les éléments à l'intérieur de ce conteneur auront la même taille de police, sauf si spécifié autrement.
HTML
<div class="container">
    <h2>Sous-titre</h2>
    <p>Ce texte aura une taille de police de 16px.</p>
    <span>Ce texte aussi.</span>
</div>
CSS
div.container {
    font-size: 16px;
}

Pour changer le style d'un élément enfant, il suffit de spécifier une règle CSS pour cet élément.
<body>
    <h1>Titre principal</h1> <!-- Ce texte sera en rouge. -->
    <p>Ce texte sera en bleu.</p>
</body>
CSS
body {
    color: blue;
}
h1 {
    color: red;
}

# CSS externe
Une feuille de style externe est utilisée pour définir le style de nombreuses pages HTML.

Pour utiliser une feuille de style externe, ajoutez un lien vers celle-ci dans la <head>section de chaque page HTML :
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>


