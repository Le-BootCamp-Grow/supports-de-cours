# CSS/CSS3 Cheat sheet
## Aide-mémoire CSS/CSS3

> This cheat sheet is made by Growcampus.
> For web developers from entry-level to senior developers.

1.  Les Sélecteurs :

```CSS
 élément {
  property: value;
}

#id {
  property: value;
}

.class {
  property: value;
}

/* Utiliser plusieurs sélecteurs */
 sélecteur1, sélecteur2 {
  property: value;
}
```

2. Le Box Model :

```CSS
/* margin : la marge */
sélecteur {
    margin: value;
    margin-top: 10px;           /* top : le haut */
    margin-right: 2em;          /* right : la droite */
    margin-bottom: 2em;         /* bottom : le bas */
    margin-left: 10px;          /* left : la gauche */

    /* abrégé */
    margin: haut droite bas gauche;
    margin: 20px 1.5rem 1.5em 20px;

    margin: haut droit-gauche bas;
    margin: 20px 1.5rem 20px;

    margin: haut-bas droite-gauche;
    margin: 20px 1.5rem;

    margin: haut-bas-droite-gauche;
    margin: 1rem;
}


/* padding : le rembourrage */
sélecteur {
    padding: value;
    padding-top: 1em;       /* top : le haut */
    padding-right: 2rem;    /* right : la droite */
    padding-bottom: 3em;    /* bottom : le bas */
    padding-left: 4rem;     /* left : la gauche */

    /* abrégé */
    padding: haut droite bas gauche;
    padding: 20px 1.5rem 1.5em 20px;

    padding: haut droite-gauche bas;
    padding: 20px 1.5rem 20px;

    padding: haut-bas droite-gauche;
    padding: 20px 1.5rem;

    padding: haut-bas-droite-gauche;
    padding: 1rem;
}


/* border : la bordure */
sélecteur {
    border: value;
    border-top: 1px;        /* top : le haut */
    border-right: 2px;      /* right : la droite */
    border-bottom: 1px;     /* bottom : le bas */
    border-left: 2px;       /* left : la gauche */

    /* abrégé */
    border: haut-droite-bas-gauche;
    border: 2px;
}
```

3. Backgrounds - Arrière-plans/Fonds :

```CSS
sélecteur {
    /* background color : couleur de l'arrière-plan */
    background-color: value;

    /* background image : image en arrière-plan */
    background-image: url("chemin/vers/image.jpg");
    background-repeat: repeat|no-repeat;                          /* arrière-plan unique ou répété */
    background-position: left|top|center|bottom|right;      /* positionnement de l'arrière-plan */

    /* abrégé */
    background: value;
}
```

 
4. Texte :

```CSS
sélecteur {
    /* color */
    color: value;
    color: red;
    color: #FFFFFF;
    color: rgb(255, 255, 255);

    /* font : police */
    font-family: "Helvetica Neue", sans-serif;      /* police - famille */
    font-size: value;                               /* taille du texte */
    font-weight: normal|bold;                       /* le poids du texte */

    /* décoration texté */
    text-decoration: none|underline|line-through;

    /* alignement du texte */
    text-align: left|center|right;
}
```


5. Display :

La propriété "display" définit le type d'affichage d'un élément HTML. Il existe plusieurs valeurs possibles pour cette propriété, dont les plus courantes sont "block", "inline" et "inline-block".

Dans ce code ci-dessous, les commentaires indiquent les différents types d'éléments auxquels les règles s'appliquent.

La première règle "display: block;" s'applique aux éléments "block", qui sont des éléments HTML qui occupent toute la largeur disponible et sont affichés sur une nouvelle ligne. Les exemples d'éléments "block" incluent les titres de section, les paragraphes, les listes et les divs.

La deuxième règle "display: inline;" s'applique aux éléments "inline", qui sont des éléments HTML qui ne prennent pas toute la largeur disponible et sont affichés sur la même ligne que leur contenu. Les exemples d'éléments "inline" incluent les liens, les images et les span.

La troisième règle "display: inline-block;" s'applique aux éléments "inline-block", qui sont des éléments HTML qui prennent toute la largeur disponible, mais sont affichés sur la même ligne que les éléments "inline". Les exemples d'éléments "inline-block" incluent les boutons, les champs de formulaire et les éléments de navigation.

```CSS
sélecteur {
    /* block elements */
    display: block;

    /* inline elements */
    display: inline;

    /* inline-block elements */
    display: inline-block;
}
```

6.  Le Flexbox :

```CSS
/* appliquer au container */
sélecteur {
    display: flex;
    flex-direction: row | column;
    justify-content: flex-start | flex-end | center | space-between | space-around;
    align-items: flex-start | flex-end |center | baseline | stretch;
}


/* appliquer à l'élément enfant */
sélecteur {
    flex: value;
    order: value;
    flex-grow: value;
    flex-shrink: value;
    flex-basis: value;
    align-self: auto | flex-start | flex-end | center | baseline | stretch;
}

```

7.  Le Grid :

```CSS
/* appliquer au container */
sélecteur {
    display: grid;
    grid-template-rows: value;
    grid-template-columns: value;
    grid-gap: value;

    /* appliquer à l'élément enfant */
    grid-row-start: value;
    grid-row-end: value;
    grid-column-start: value;
    grid-column-end: value;

    /* alignement des éléments enfants */
    justify-items: start | center | end;
    align-items: start | center | end;

    /* align content */
    justify-content: start | center | end | space-around | space-between | space-evenly;
    align-content: start | center | end | space-around | space-between | space-evenly;
}
```

8. Les transitions :

```CSS
sélecteur {
    /* propriété */
    transition-property: value;

    /* durée */
    transition-duration: value;

    /* fonction de chronométrage */
    transition-timing-function: ease | ease-in | ease-out | ease-in-out;
}
```

9.  Les animations :

```CSS
/* keyframes */
@keyframes animation-name {
  0% {
    /* styles */
  }
  50% {
    /* styles */
  }
  100% {
    /* styles */
  }
}

exemple {
    /* animation */
    animation-name: nom-animation;
    animation-duration: value;
    animation-timing-function: ease |ease-in |ease-out | ease-in-out;
    animation-delay: value;
    animation-iteration-count: value;
    animation-direction: normal | reverse | alternate | alternate-reverse;
    animation-fill-mode: none | forwards | backwards | both;
    animation-play-state: running | paused;
}
```

10. Media Queries :

Les media queries en CSS permettent de définir des styles différents en fonction des caractéristiques de l'appareil ou de l'écran sur lequel une page web est affichée. Cela permet aux développeurs de créer des mises en page et des designs adaptatifs qui s'ajustent automatiquement aux différentes tailles d'écran.

Les media queries utilisent la propriété "media" en CSS pour définir les règles en fonction des caractéristiques de l'appareil. Les caractéristiques les plus courantes incluent la largeur de l'écran, l'orientation (portrait ou paysage) et la densité de pixels.

Les règles définies dans une media query ne sont appliquées que si les caractéristiques spécifiées sont respectées. Par exemple, une règle peut être définie pour appliquer un style différent pour les écrans plus larges que 768 pixels.

Les media queries sont essentielles pour créer des designs web adaptatifs et réactifs qui fonctionnent bien sur tous les appareils, qu'il s'agisse d'ordinateurs de bureau, de tablettes ou de téléphones portables.

```CSS
/* device width */
@media only screen and (max-width: 768px) {
  /* vos styles ici... */
}

/* device orientation */
@media only screen and (orientation: landscape) {
  /* vos styles ici... */
}

/* print */
@media print {
  /* vos styles ici... */
}

/* high resolution displays */
@media only screen and (-webkit-min-device-pixel-ratio: 2),
       only screen and (min--moz-device-pixel-ratio: 2),
       only screen and (-o-min-device-pixel-ratio: 2/1),
       only screen and (min-device-pixel-ratio: 2),
       only screen and (min-resolution: 192dpi),
       only screen and (min-resolution: 2dppx) {
  /* vos styles ici... */
}
```

11. Pseudo-classes :

Les pseudo-classes CSS sont des sélecteurs qui ciblent les éléments HTML dans un état particulier ou une relation avec un autre élément.

Par exemple, la pseudo-classe ":hover" cible un élément lorsque le curseur de la souris est positionné dessus, la pseudo-classe ":active" cible un élément lorsqu'il est cliqué, et la pseudo-classe ":first-child" cible le premier enfant d'un élément parent.

Les pseudo-classes sont utiles pour appliquer des styles spécifiques à des états ou des relations particulières, ce qui permet de créer des effets interactifs et de personnaliser la mise en page des éléments HTML.

Il existe de nombreuses pseudo-classes CSS, y compris des pseudo-classes de lien (":link", ":visited", ":hover", ":active"), des pseudo-classes de contenu ("::before", "::after", "::first-letter", "::first-line"), des pseudo-classes de formulaire (":checked", ":focus", ":disabled", ":enabled"), et bien plus encore.

Les développeurs peuvent utiliser les pseudo-classes CSS pour ajouter des styles interactifs et dynamiques à leur page web, ce qui peut améliorer l'expérience utilisateur et rendre le contenu plus attractif.

```CSS
/* états du lien */
a:link { /* lien non visité */ }
a:visited { /* lien visité */ }
a:hover { /* survoler le lien avec la souris */ }
a:active { /* lien sélectionné */ }

/* États des formulaires */
input:focus { /* est centré sur l'élément */ }
input:required { /* champ est obligatoire */ }
input:disabled { /* l'élément est désactivé */ }

/* éléments enfants */
parent > child { /* enfant direct */ }
parent descendant { /* n'importe quel descendant */ }

/* éléments pairs/impairs */
tr:nth-child(odd) { /* ligne impaire (appliqué au tableau ici) */ }
tr:nth-child(even) { /* ligne paire (appliqué au tableau ici) */ }

/* premiers/derniers éléments */
:first-child { /* premier élément */ }
:last-child { /* dernier élément */ }

```

12. Préfixes des fabricants navigateurs :

```CSS
/* Firefox */
-moz-border-radius: value;

/* Safari/Chrome */
-webkit-border-radius: value;

/* Opera */
-o-border-radius: value;

/* IE9+ */
border-radius: value;
```

13. Variables CSS :

```CSS
/* define variable */
:root {
  --main-color: #ff0000;
}

/* usage de la variable */
element {
  color: var(--main-color);
}

```

Voici quelques concepts et unités CSS plus avancés pour votre antisèche CSS/CSS3 :

14. Unités CSS :

**Unités fixes** :
-   px : pixels (par rapport à la résolution de l'écran)
-   in : pouces
-   cm : centimètres
-   mm : millimètres
-   pt : points (1/72 de pouce)
-   pc : picas (1/6 de pouce)

**Unités relatives** :
-   em : par rapport à la taille de la police de l'élément (par exemple, 1em = 100% de la taille de la police)
-   rem : par rapport à la taille de la police de l'élément racine
-   vw : par rapport à 1 % de la largeur de la fenêtre de visualisation
-   vh : par rapport à 1 % de la hauteur de l'écran
-   vmin : 1% de la plus petite dimension de la fenêtre d'affichage
-   vmax : par rapport à 1 % de la plus grande dimension de la fenêtre d'affichage

15. Les Gradients en CSS :

```CSS

sélécteur {
    /* linear gradient : gradient linéaire */
    background: linear-gradient(direction, color-stop1, color-stop2, ...);
    /* radial gradient : gradient en cercle*/
    background: radial-gradient(shape, size, position, color-stop1, color-stop2, ...);
}
```

16. Ombres en CSS :

```CSS
sélecteur {
   /* box shadow */
    box-shadow: h-shadow v-shadow blur spread color inset;

    /* text shadow */
    text-shadow: h-shadow v-shadow blur color; 
}
 ```