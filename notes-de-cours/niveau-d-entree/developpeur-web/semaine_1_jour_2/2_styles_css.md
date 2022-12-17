## Styles CSS

> Cette leçon présente les différentes façons d'appliquer des styles CSS aux éléments d'une page Web, notamment à l'aide de styles en ligne, de styles internes et de feuilles de style externes.

Comme nous l'avons vu dans la dernière leçon, CSS (Cascading Style Sheets) est un langage de feuille de style utilisé pour contrôler la présentation des éléments sur une page Web. Les développeurs l'utilisent pour ajouter des couleurs, des polices, des mises en page et d'autres styles visuels aux pages Web. Les styles CSS sont appliqués aux éléments HTML d'une page Web pour en modifier l'aspect et la convivialité.

Il existe trois façons d'appliquer des styles CSS aux éléments HTML :

Les styles en ligne : Les styles en ligne sont appliqués directement à l'élément HTML à l'aide de l'attribut style. Ils sont écrits sous la forme d'une série de paires propriété : valeur séparées par des points-virgules. Par exemple :

```
<p style="color: blue; font-size: 16px;">Nous venons d'ajouter un style de base à ce paragraphe.</p>
```

Styles internes : Les styles internes sont définis dans l'élément `<style>` de la section `<head>` du document HTML. Ils sont appliqués aux éléments de la page Web à l'aide de sélecteurs CSS. Par exemple :

```
<head>
    <style>
    p {
        color: blue;
        font-size: 16px;
    }
    </style>
</head>

<body>
    <p>This is a paragraph</p>
</body>
```

Feuilles de style externes : Les feuilles de style externes sont des fichiers CSS distincts qui sont liés au document HTML à l'aide de l'élément `<link>` dans la section `<head>` du document HTML. Elles sont appliquées aux éléments de la page Web à l'aide de sélecteurs CSS. Par exemple :

```
<head>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <p>This is a paragraph</p>
</body>
```

Dans le fichier styles.css, les styles de l'élément `p` seraient définis comme suit :

```
p {
    color: blue;
    font-size: 16px;
}
```

En général, il est recommandé d'utiliser des feuilles de style externes pour tous vos styles CSS, car elles offrent le plus de facilité de maintenance et de flexibilité. Toutefois, les styles en ligne et les styles internes peuvent s'avérer utiles dans certaines situations, notamment pour appliquer des styles à un seul élément ou à un petit groupe d'éléments.

Nous espérons que ces notions de bases vous seront utiles et vous donneront un bon aperçu de la manière d'appliquer des styles CSS aux éléments HTML

[Passez à la leçon suivante >>](https://github.com/Le-BootCamp-Grow/supports-de-cours/blob/main/notes-de-cours/niveau-d-entree/developpeur-web/semaine_1_jour_2/3_proprietes_css.md)