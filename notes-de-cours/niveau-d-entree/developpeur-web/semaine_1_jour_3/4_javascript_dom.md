## Using JavaScript to Manipulate the HTML DOM

Le HTML DOM (Document Object Model) est une représentation d'un document HTML qui nous permet d'accéder à ses éléments et de les modifier à l'aide de langages de programmation comme JavaScript.

Dans cette leçon, nous allons apprendre à utiliser JavaScript pour manipuler le DOM HTML en ajoutant, supprimant et modifiant des éléments sur une page HTML.

Avant de commencer, il est important de comprendre comment le DOM HTML est structuré. Lorsqu'une page HTML est chargée, le navigateur crée une structure arborescente des éléments de la page, connue sous le nom d'arbre HTML DOM. On peut accéder à cette arborescence et la manipuler à l'aide de JavaScript.

Prenons un exemple simple. Considérons la page HTML suivante :

```HTML
<html>
<head>
    <title>Leçon de JavaScript</title>
</head>
<body>
    <h1>Bienvenue à la leçon de JavaScript</h1>
    <p>Cette section aborde le sujet DOM</p>
    <p>A quoi ressemble l'abre HTML DOM?</p>
</body>
</html>
```

L'arbre DOM HTML correspondant ressemblerait à ceci :

```
html
  tête
    titre
  corps
    h1
    p
    p
```

Chaque élément de l'arbre est appelé un **nœud**, et chaque nœud possède des propriétés et des méthodes auxquelles on peut accéder et qu'on peut manipuler en utilisant JavaScript.

Pour accéder à un élément dans le DOM HTML, nous pouvons utiliser la méthode `document.getElementById()`. Cette méthode prend un argument de type chaîne, qui est l'ID de l'élément auquel nous voulons accéder. Par exemple, si nous avons le HTML suivant :

```HTML
<p id="section-dom">Cette section aborde le sujet DOM</p>
```

Nous pouvons accéder à cet élément de paragraphe dans le DOM HTML en utilisant le code JavaScript suivant :

```Javascript
var sectionDom = document.getElementById("section-dom");
```

Une fois que nous avons accès à l'élément, nous pouvons utiliser ses propriétés et ses méthodes pour le modifier. Par exemple, nous pouvons utiliser la propriété `innerHTML` pour modifier le contenu de l'élément :

```Javascript
sectionDom.innerHTML = "This section is about the DOM.";
```

Cela changerait le contenu de l'élément `<p>` de "Cette section aborde le sujet DOM" à "This section is about the DOM.".

En plus de la méthode `document.getElementById()`, il existe d'autres méthodes pour accéder aux éléments du DOM HTML, comme `document.getElementsByTagName()` et `document.querySelector()`.

En plus de modifier le contenu d'un élément, nous pouvons également utiliser JavaScript pour ajouter, supprimer et modifier les attributs d'un élément. Par exemple, nous pouvons utiliser la méthode `setAttribute()` pour ajouter ou modifier un attribut :

```Javascript
sectionDom.setAttribute("class", "nouvelle-classe");
```

Cela ajoutera un attribut class à l'élément `<p>` avec la valeur "new-class".

Nous pouvons également utiliser la méthode `removeAttribute()` pour supprimer un attribut d'un élément :

```Javascript
sectionDom.removeAttribute("class");
```

Cela supprimerait l'attribut class de l'élément `<p>`.

Outre la modification des attributs, nous pouvons également utiliser JavaScript pour ajouter, supprimer et déplacer des éléments dans l'arbre DOM HTML. Par exemple, nous pouvons utiliser les méthodes `createElement()` et `appendChild()` pour ajouter un nouvel élément à la page :

```Javascript
var newElement = document.createElement("div");
newElement.innerHTML = "Ajoutons un élément div";

document.body.appendChild(newElement);
```

Ce code créerait un nouvel élément `<div>` avec le contenu "Ajoutons un élément div", et l'ajouterait à l'élément `<body>` de la page.

De même, nous pouvons utiliser la méthode `removeChild()` pour supprimer un élément de l'arbre DOM HTML :

```Javascript
document.body.removeChild(newElement);
```

Cela supprimerait l'élément `<div>` que nous avons ajouté précédemment de l'élément `<body>` de la page.

Enfin, nous pouvons utiliser la méthode `insertBefore()` pour déplacer un élément à une position différente dans l'arbre DOM HTML :

```Javascript
document.body.insertBefore(newElement, sectionDom);
```

Ainsi, l'élément `<div>` que nous avons créé précédemment sera positionné avant l'élément `<p>` avec l'ID "section-dom" dans l'élément `<body>` de la page.

Dans cette leçon, nous avons appris à utiliser JavaScript pour manipuler le DOM HTML en ajoutant, supprimant et modifiant des éléments et leurs attributs. Ces techniques sont essentielles pour créer des pages et des applications Web dynamiques et interactives.

[Passez à la section suivante >>](https://github.com/Le-BootCamp-Grow/supports-de-cours/blob/main/notes-de-cours/niveau-d-entree/developpeur-web/semaine_1_jour_3/5_pratique.md)