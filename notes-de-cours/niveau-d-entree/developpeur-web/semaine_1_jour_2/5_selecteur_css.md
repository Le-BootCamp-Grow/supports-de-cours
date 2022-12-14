## Sélecteurs CSS

> Cette section présente les différentes façons de sélectionner les éléments d'une page Web auxquels appliquer des styles, notamment à l'aide de sélecteurs d'éléments et de classes.

Les sélecteurs CSS sont utilisés pour sélectionner des éléments sur une page Web et leur appliquer des styles. Il existe plusieurs types de sélecteurs CSS, notamment les sélecteurs d'éléments, les sélecteurs de classes et les sélecteurs d'attributs.

**Les sélecteurs d'éléments** vous permettent d'appliquer des styles à tous les éléments d'un type particulier sur une page Web. Par exemple, pour appliquer des styles à tous les éléments de paragraphe d'une page Web, vous pouvez utiliser le sélecteur d'élément `p`.

```
p {
    /* vos styles ici... */
}
```

**Les sélecteurs de classe** vous permettent d'appliquer des styles à un groupe d'éléments qui ont le même attribut de classe. Cela vous permet d'appliquer les mêmes styles à plusieurs éléments d'une page sans avoir à répéter les styles pour chaque élément individuel. Pour appliquer des styles à des éléments ayant une classe particulière, vous utilisez un point, `.`, suivi du nom de la classe.

```
.classe-menu {
    /* vos styles ici... */
}
```

**Les sélecteurs d'attributs** vous permettent d'appliquer des styles aux éléments en fonction de leurs attributs et de leurs valeurs. Par exemple, vous pouvez utiliser un sélecteur d'attribut pour appliquer des styles à tous les éléments `a` qui ont un attribut `href` avec une valeur particulière.

```
    a[href="https://www.example.com/"] {
        /* vos styles ici... */
    }
```

> Tip: En HTML, un attribut est une propriété d'un élément HTML qui fournit des informations ou des instructions supplémentaires sur la façon dont cet élément doit se comporter ou être rendu. Attributes are always specified within the opening tag of an element, and are typically made up of a name and a value, separated by an equals sign. Par exemple, l'attribut `href` d'un élément `<a>` peut être utilisé pour spécifier l'URL vers laquelle le lien doit pointer, comme ceci :
> ```
> <a href="https://ecolegrow.tech">Cliquez ici</a>
> ```
>Dans cet exemple, l'attribut href est le nom de l'attribut, et https://ecolegrow.tech est la valeur de l'attribut. Lors du rendu du document HTML, la valeur de l'attribut href sera utilisée pour déterminer l'endroit où le lien doit pointer.

Vous pouvez également combiner plusieurs sélecteurs pour créer des règles plus spécifiques d'application des styles. Par exemple, vous pouvez combiner un sélecteur d'élément et un sélecteur de classe pour appliquer des styles uniquement à certains éléments ayant une classe particulière.

```
p.ma-classe {
    /* vos styles ici... */
}
```

Ce ne sont là que quelques exemples des types de sélecteurs CSS que vous pouvez utiliser pour appliquer des styles aux éléments d'une page Web. Il existe de nombreux autres sélecteurs que vous apprendrez à connaître au cours de ce camp d'entraînement.

[Passez à la leçcon suivante >>](https://github.com/Le-BootCamp-Grow/supports-de-cours/blob/main/notes-de-cours/niveau-d-entree/developpeur-web/semaine_1_jour_2/6_pratique.md)