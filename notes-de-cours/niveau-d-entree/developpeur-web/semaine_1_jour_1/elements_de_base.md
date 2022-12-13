## Éléments de texte de base

Le langage HTML comprend plusieurs éléments permettant de marquer le texte, tels que `<p>` pour les paragraphes, `<strong>` pour le texte en gras et `<em>` pour l'accentuation. Here are some examples:

> NB: `<strong>` et `<em>` constituent des éléments sémantiques de HTML5. Ils permettent de mettre du texte en gras et en italique, et de mettre l'appuie et l'accentuation (voire l'emphase) sur le texte affecté. En revanche, en HTML, avant le HTML5, `<b>` et `<i>` ont été utilisés pour mettre le texte en gras et en italique respectivement. Cependant, ces derniers n'apportent pas de signification au texte affecté.

```
<p>Voici un paragraphe.</p>

<strong>Ce texte est en gras.</strong>

<em>Ce texte est accentué.</em>
```

Le HTML comprend plusieurs éléments pour les titres et sous-titres, tels que `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>` et `<h6>`. Voici quelques exemples d'utilisation :

```
<h1>Voici un exemple de titre d'une page</h1>
<h2>Voici un exemple de sous-titre d'une page</h2>
<h3>Voici un autre sous-titre</h3>
<h4>Et juste un autre sous-titre</h4>
<h5>Et encore un autre sous-titre</h5>
<h6>Et un dernier sous-titre</h6>
```

## Éléments de base des liens

Le langage HTML comprend l'élément `<a>` pour créer des liens vers d'autres pages web ou vers des emplacements spécifiques sur la même page web.

Pour créer un lien vers une autre page Web, vous utilisez l'élément `<a>` et spécifiez l'URL de destination dans l'attribut href. Par exemple, pour créer un lien vers Google, vous devez utiliser le code suivant :

```
<a href="https://www.google.com">Aller à Google</a>
```

Pour créer un lien vers un emplacement spécifique de la même page Web, vous utilisez l'attribut id de l'élément cible et spécifiez la valeur id dans l'attribut href de l'élément `<a>`. Par exemple, si vous avez un titre avec l'id de "grand-titre", vous pouvez créer un lien vers celui-ci en utilisant le code suivant :

```
<h1 id="grand-titre">Ma Première Page</h1>

<a href="#grand-titre">Va à Ma Première Page</a>
```

## Éléments d'image de base

Le langage HTML comprend l'élément `<img>` pour afficher des images sur une page Web. Pour utiliser l'élément `<img>`, vous devez préciser la source de l'image à l'aide de l'attribut *src* et fournir le texte *alt* de l'image à l'aide de l'attribut *alt*. Le texte *alt* est utilisé pour fournir une alternative textuelle à l'image, et il est affiché si l'image ne peut pas être chargée ou si l'utilisateur utilise un lecteur d'écran.

```
<img src="mon-image.jpg" alt="Un beau paysage">
```

## Éléments de base des listes

Le langage HTML comprend deux types de listes : les listes ordonnées et les listes non ordonnées. Une liste ordonnée est utilisée pour afficher une liste d'éléments dans un ordre spécifique et elle est créée à l'aide de l'élément `<ol>`. Chaque élément de la liste est marqué à l'aide de l'élément `<li>`. Par exemple :

```
<ol>
    <li>Premier article</li>
    <li>Deuxième article</li>
    <li>Troisième article</li>
</ol>
```

Une liste non ordonnée est utilisée pour afficher une liste d'éléments qui n'ont pas d'ordre spécifique, et elle est créée à l'aide de l'élément `<ul>`. Chaque élément de la liste est marqué à l'aide de l'élément `<li>`. Par exemple :

```
<ul>
    <li>Premier article</li>
    <li>Deuxième article</li>
    <li>Troisième article</li>
</ul>
```

> Astuces : 
> - Le `<li>` représente chaque 'ligne' de la liste. 
> - `<ul>` signifie << unordered list >> en anglais.
> - `<ol>` signifie << ordered list >> en anglais.

Le langage HTML comprend des éléments permettant de créer des tableaux pour afficher des données sous forme de tableaux. Un tableau est créé à l'aide de l'élément `<table>`, et il est constitué de lignes et de colonnes. Une ligne est créée à l'aide de l'élément `<tr>` et une colonne est créée à l'aide de l'élément `<td>`. Voici un exemple de tableau simple :

```
<table>
    <tr>
        <td>Ligne 1, Colonne 1</td>
        <td>Ligne 1, Colonne 2</td>
    </tr>
    <tr>
        <td>Ligne 2, Colonne 1</td>
        <td>Ligne 2, Colonne 2</td>
    </tr>
    <tr>
        <td>Ligne 3, Colonne 1</td>
        <td>Ligne 3, Colonne 2</td>
    </tr>
</table>
```

## Éléments de base du formulaire

Le langage HTML comprend des éléments permettant de créer des formulaires, qui permettent aux utilisateurs de saisir des données et de les soumettre au serveur. Un formulaire est créé à l'aide de l'élément `<form>` et se compose de champs de saisie, tels que des champs de texte, des boutons radio et des cases à cocher. Chaque champ de saisie est créé à l'aide d'un élément spécifique, tel que `<input>`, `<textarea>` et `<select>`.

L'élément `<input>` est utilisé pour créer une variété de champs de saisie, tels que des champs de texte, des boutons radio et des cases à cocher. Le type de champ de saisie est spécifié à l'aide de l'attribut type. Par exemple, pour créer un champ de texte, vous devez utiliser le code suivant :

```
<input type="text" placeholder="Entrez votre nom">
```

L'élément `<textarea>` est utilisé pour créer un champ de texte à plusieurs lignes, dans lequel l'utilisateur peut saisir plusieurs lignes de texte. It is typically used for longer pieces of text, such as comments or descriptions. Pour créer un élément `<textarea>`, vous devez utiliser le code suivant :

```
<textarea placeholder="Entrez votre message"></textarea>
```

L'élément `<select>` est utilisé pour créer une liste déroulante d'options, dans laquelle l'utilisateur peut sélectionner une ou plusieurs options. Chaque option de la liste est créée à l'aide de l'élément `<option>`. Pour créer un élément `<select>` comportant cinq options, vous devez utiliser le code suivant :

```
<select>
    <option>Option 1</option>
    <option>Option 2</option>
    <option>Option 3</option>
    <option>Option 4</option>
    <option>Option 5</option>
</select>
```

Pour traiter les données saisies par l'utilisateur et les soumettre au serveur, vous devez ajouter un bouton d'envoi au formulaire. Pour ce faire, vous utilisez l'élément `<button>` et vous spécifiez le type de bouton à l'aide de l'attribut type. Pour créer un bouton d'envoi, vous devez utiliser le code suivant :

```
<button type="submit">Envoyer</button>
```

NB : Pour vos formulaires, vous pouvez aussi créer un bouton submit (ou n'importe quel bouton pour n'importe quel autre but) en utilisant l'élément `<input>`. Voici une façon de le faire :

```
<input type="submit" value="Envoyer la demande" />
```

[Passez à l'unité suivante >>]()