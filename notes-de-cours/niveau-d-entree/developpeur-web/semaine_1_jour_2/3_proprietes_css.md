## Propriétés CSS courantes

> Cette section couvre certaines des propriétés CSS les plus courantes et leur utilisation, telles que les propriétés de police, les propriétés de couleur et les propriétés de modèle de boîte.

Le CSS permet aux développeurs web d'appliquer des styles, tels que des polices, des couleurs et des espacements, aux éléments HTML d'une page web. Cela leur permet de créer des pages Web visuellement attrayantes et conviviales.

Les propriétés CSS sont les règles de style individuelles qui peuvent être appliquées aux éléments d'une page Web. Ces propriétés spécifient le style et la disposition des éléments, tels que leur taille, leur couleur et leur positionnement.

Par exemple, la propriété `font-family` peut être utilisée pour spécifier la police qui doit être utilisée pour un élément de page Web, comme ceci :

```
h1 {
    font-family: Arial;
}
```

Dans l'exemple ci-dessus, la propriété `font-family` est appliquée à tous les éléments `<h1>` de la page Web, définissant leur police à Arial.

De même, la propriété color peut être utilisée pour spécifier la couleur d'un élément, comme ceci :

```
a {
    color: #333;
}
```

Dans l'exemple ci-dessus, la propriété color est appliquée à tous les éléments <a> de la page Web, définissant leur couleur sur un gris foncé.

Il existe de nombreuses propriétés CSS différentes qui peuvent être utilisées pour contrôler le style et la disposition des éléments de la page Web. Ces propriétés peuvent être utilisées en combinaison pour créer des conceptions complexes et sophistiquées.

### Propriétés des polices :
    
Les propriétés de la police sont utilisées pour contrôler l'apparence du texte sur une page Web.

Voici quelques propriétés de police courantes :

- `font-family` : spécifie la police à utiliser pour le texte
- `font-size` : spécifie la taille de la police
- `font-weight` : spécifie le degré de gras de la police.

La propriété `font-family` est utilisée pour spécifier la police à utiliser pour le texte. Elle accepte une liste de noms de polices séparés par des virgules. Le navigateur utilisera la première police de la liste qui est disponible sur l'ordinateur de l'utilisateur. Si aucune des polices spécifiées n'est disponible, le navigateur utilisera une police par défaut.

Par exemple, le code suivant spécifie les polices Arial et Verdana comme famille de polices pour tous les éléments `<p>` de la page Web :

```
p {
    font-family: Arial, Verdana;
}
```

La propriété `font-size` est utilisée pour spécifier la taille de la police. Elle peut être spécifiée dans une variété d'unités, telles que les pixels (px), les ems (em) et les pourcentages (%).

Par exemple, le code suivant spécifie une taille de police de 16 pixels pour tous les éléments `<h2>` de la page Web :

```
h2 {
    font-size: 16px;
}
```

La propriété `font-weight` est utilisée pour spécifier le degré de gras de la police. Elle accepte un nombre ou une valeur de mot-clé, les nombres ou les valeurs de mot-clé plus élevés indiquant une police plus grasse.

Par exemple, le code suivant spécifie un poids de la police en gras pour tous les éléments `<h3>` de la page Web :

```
h3 {
    font-weight: bold;
}
```

In addition to the font properties outlined above, there are also other font properties that can be used to control the appearance of text on a web page, such as `font-style`, `font-variant`, and `font-stretch`.

### Propriétés de couleur :

Les propriétés de couleur CSS sont utilisées pour spécifier la couleur du texte et d'autres éléments sur une page Web.

Il existe plusieurs façons de spécifier les couleurs en CSS, notamment en utilisant des mots-clés de couleur, des valeurs hexadécimales et des valeurs RVB.

Les mots-clés de couleur sont des couleurs prédéfinies auxquelles on a attribué des noms, tels que "rouge", "vert" et "bleu". Ces couleurs peuvent être utilisées en spécifiant le nom de la couleur comme valeur de la propriété color, comme ceci :

```
a {
    color: red;
}
```

Les valeurs hexadécimales sont des codes à six chiffres qui représentent les couleurs. Ces valeurs sont généralement préfixées par le symbole "#", et peuvent être utilisées pour spécifier des couleurs comme ceci :

```
p {
    couleur: #FF4F4F;
}
```

Les valeurs RVB sont des codes à trois chiffres qui représentent les couleurs en fonction de leurs valeurs rouge, verte et bleue. Ces valeurs sont généralement écrites sous la forme "rgb(R, G, b)", où R, G et B sont des nombres compris entre 0 et 255 qui représentent respectivement les valeurs rouge, verte et bleue de la couleur. Les valeurs RVB peuvent être utilisées pour spécifier des couleurs comme ceci :

```
p {
    color : rgb(255, 0, 0);
}
```

Outre la spécification de la couleur du texte, les propriétés de couleur CSS peuvent également être utilisées pour spécifier la couleur d'autres éléments sur une page Web, tels que les arrière-plans, les bordures et les cellules de tableau.

Par exemple, la propriété background-color peut être utilisée pour spécifier la couleur d'arrière-plan d'un élément, comme ceci :

```
form {
    background-color: #FF0000;
}
```

La propriété border-color peut être utilisée pour spécifier la couleur de la bordure d'un élément, comme ceci :

```
input {
    border-color : #25706B ;
}
```

And the color property can be used to specify the text color of a table cell, like this:

```
td {
    color: #1C1C1C;
}
```

CSS fournit également un certain nombre de **fonctions** liées aux couleurs qui peuvent être utilisées pour manipuler les couleurs, comme les fonctions rgb() et hsl(), qui vous permettent de spécifier les couleurs en utilisant différents modèles de couleurs.

Par exemple, la fonction `rgb()` peut être utilisée pour ajuster les valeurs rouge, verte et bleue d'une couleur, comme ceci :

```
label {
color: rgb(255, 0, 0);  /* red */
color: rgb(255, 128, 0);  /* orange */
color: rgb(255, 255, 0);  /* yellow */
}
```

La fonction `hsl()` peut être utilisée pour spécifier les couleurs en utilisant les valeurs de teinte, de saturation et de luminosité, comme ceci :

```
h6 {
    color: hsl(0, 100%, 50%);  /* red */
    color: hsl(30, 100%, 50%);  /* orange */
    color: hsl(60, 100%, 50%);  /* yellow */
}
```

[Passez à la leçcon suivante >>](https://github.com/Le-BootCamp-Grow/supports-de-cours/blob/main/notes-de-cours/niveau-d-entree/developpeur-web/semaine_1_jour_2/4_unites_css.md)