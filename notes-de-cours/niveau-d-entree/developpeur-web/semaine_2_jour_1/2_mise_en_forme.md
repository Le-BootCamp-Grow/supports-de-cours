## Formatage HTML

### Texte en gras et en italique

Pour créer du texte en gras en HTML, vous pouvez utiliser l'élément `<strong>` ou l'élément `<b>`. Les deux éléments créent un texte qui apparaît en gras dans le navigateur, mais l'élément `<strong>` est considéré comme plus correct sur le plan sémantique, car il indique que le texte est important. L'élément `<b>` est plutôt utilisé à des fins stylistiques.

Voici un exemple d'utilisation de l'élément `<strong>` pour créer un texte en gras :

```
<p>Voici un paragraphe <strong>important</strong> ici.</p>
```

Le texte "important" apparaîtra en gras dans le navigateur.

Pour créer du texte en italique en HTML, vous pouvez utiliser l'élément `<em>` ou l'élément `<i>`. Les deux éléments créent du texte qui apparaît en italique dans le navigateur, mais l'élément `<em>` est considéré comme plus correct sur le plan sémantique, car il indique que le texte est accentué, voire mis en valeur. L'élément `<i>` est plutôt utilisé à des fins stylistiques.

Voici un exemple d'utilisation de l'élément `<em>` pour créer un texte en italique :

```
<p>Voici un exemple de <em>texte accentué</em> ici.</p>
```

Le texte "texte accentué" apparaîtra en italique dans le navigateur.

### Sauts de ligne et lignes horizontales

Pour créer un saut de ligne en HTML, vous pouvez utiliser l'élément `<br>`. Cet élément est une balise auto-fermante, ce qui signifie qu'il n'a pas de balise de fermeture. Lorsque l'élément `<br>` est utilisé, il crée un saut de ligne dans le texte et déplace le texte suivant sur une nouvelle ligne.

Voici un exemple d'utilisation de l'élément `<br>` pour créer un saut de ligne :

```
<p>Je crée un texte ici.<br>Je renvoie ce texte ci sur une nouvelle ligne.</p>
```

Pour créer une ligne horizontale en HTML, vous pouvez utiliser l'élément `<hr>`. Cet élément est une balise auto-fermante, ce qui signifie qu'il n'a pas de balise de fermeture. Lorsque l'élément `<hr>` est utilisé, il crée une ligne horizontale qui s'étend sur la largeur du conteneur dans lequel il est placé.

Voici un exemple d'utilisation de l'élément `<hr>` pour créer une ligne horizontale :

```
<p>Je crée un texte ici.</p>
<hr>
<p>Ce texte se trouve sous une ligne horizontale.</p>
```

### Texte préformaté

Le texte préformaté est un texte qui s'affiche dans une police de largeur fixe et qui conserve les espaces et les sauts de ligne. Cela peut être utile pour afficher des extraits de code ou tout autre texte nécessitant une mise en page spécifique.

Pour créer du texte préformaté en HTML, vous pouvez utiliser l'élément `<pre>`. Cet élément indique au navigateur de traiter le texte qu'il contient comme étant préformaté. Voici un exemple d'utilisation de l'élément `<pre>` :

```
<pre>
Ceci s'agit d'un texte préformaté.
Il sera affiché dans une police à largeur fixe et conservera les espaces et les sauts de ligne.
</pre>
```

### Les Guillemets

Le langage HTML fournit plusieurs éléments pour marquer les citations, notamment l'élément `<blockquote>` pour les longues citations et l'élément `<q>` pour les courtes citations en ligne.

L'élément `<blockquote>` est utilisé pour marquer un bloc de texte qui est une citation d'une autre source. Il est généralement mis en retrait et rendu dans une police ou une couleur différente pour le distinguer du reste du texte. Voici un exemple d'utilisation de l'élément `<blockquote>` :

```
<blockquote>
  "J'ai le rêve qu'un jour mes quatre enfants vivront dans une nation où ils ne seront pas jugés pour la couleur de leur peau, mais pour leur caractère." - Martin Luther King
</blockquote>
```

L'élément `<q>` est utilisé pour marquer une courte citation en ligne. Il est généralement rendu avec des guillemets autour de lui. Voici un exemple d'utilisation de l'élément `<q>` :

```
<p>Selon la célèbre citation, "Le courage n'est pas l'absence de peur, mais la capacité de vaincre ce qui fait peur."</p>
```

L'attribut `cite` peut être utilisé avec l'élément `q` pour indiquer la source de la citation. La valeur de l'attribut `cite` doit être une URL qui pointe vers la source de la citation.

Voici un exemple d'utilisation de l'attribut `cite` avec l'élément `<q>` :

```
<q cite="https://citations.ouest-france.fr/citation-albert-einstein/imagination-importante-savoir-7686.html">L'imagination est plus importante que le savoir.</q>
```

> Notez que l'attribut `cite` n'est pas affiché à l'utilisateur. Il est destiné à fournir des informations supplémentaires sur la citation aux navigateurs, moteurs de recherche et autres logiciels.

[Passez à la section suivante >>](https://github.com/Le-BootCamp-Grow/supports-de-cours/blob/main/notes-de-cours/niveau-d-entree/developpeur-web/semaine_2_jour_1/3_commentaires.md)