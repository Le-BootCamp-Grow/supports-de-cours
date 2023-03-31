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

10. Divisions - créer une division sur la page web :

```HTML
  <div>
    <p>Voici une division.</p>
  </div>
```

11. Créer un span :

```HTML
 <p>Voici comment utiliser un <span>span</span>.</p>
```

12. Attributs :

```HTML
 <img src="image.jpg" alt="Description de l'Image" width="200" height="200">
```

13. Classes ;

```HTML
 <p class="intro">Voici une introduction.</p>

 <style>
  .intro {
    font-weight: bold;
  }
</style>
```

14. IDs :

```HTML
 <p id="para1">Voici un paragraphe.</p>

 <script>
  var para1 = document.getElementById("para1");
  para1.style.color = "red";
</script>
```

15. Le HTML Sémantique :

```HTML
 <header>
  <h1>Titre de Page</h1>
  
  <nav>
    <ul>
      <li><a href="#">Acceuil</a></li>
      <li><a href="#">À Propos</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
 </header>

 <main>
  <article>
    <h2>Titre de l'article </h2>
    <p>Voici un article.</p>
  </article>

  <aside>
    <h3>Titre Ici</h3>
    <p>Voici une division Aside.</p>
  </aside>
 </main>

 <footer>
  <p>Copyright © 2023</p>
 </footer>
```

16. Audio et Vidéo :

```HTML
 <audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  Votre navigateur ne prend pas en charge l'élément audio.
 </audio>
 <video controls>
  <source src="video.mp4" type="video/mp4">
  Votre navigateur ne prend pas en charge l'élément audio.
 </video>

17. Iframes :

```HTML
 <iframe src="https://www.example.com"></iframe>
```

18. Utiliser les balises Meta :

```HTML
 <meta name="description" content="Description de la Page">
  <meta name="keywords" content="HTML, CSS, JavaScript">
 <meta name="author" content="John Doe">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
```

19. Des balises HTML sémantiques plus avancées :

- `<section>` : représente une section d'un document ou d'une application
- `<article>` : représente une composition autonome dans un document, tel qu'un billet de blog ou un article de presse
- `<aside>` : représente le contenu qui est en relation indirecte avec le contenu qui l'entoure, tel qu'un encadré ou une boîte de rappel
- `<figure>` : représente un contenu autonome, tel qu'une image, un diagramme ou un extrait de code, qui est référencé dans le contenu principal
- `<figcaption>` : représente une légende ou une description pour un élément `<figure>`.

20. Des balises `head` et `meta` sémantiques plus avancées :

- `<base>` : spécifie l'URL de base pour tous les URL relatifs dans le document
- `<link>` : spécifie un lien vers une ressource externe, telle qu'une feuille de style ou une icône
- `<style>` : contient des règles CSS pour le document
- `<script>` : contient du code JavaScript pour le document
- `<noscript>` : contient le contenu à afficher lorsque JavaScript est désactivé
- `<meta charset="UTF-8">`  : spécifie le codage des caractères du document
- `<meta http-equiv="X-UA-Compatible" content="IE=edge, chrome=1">` : spécifie que le document actuel doit être rendu en utilisant la dernière version disponible d'Internet Explorer et assure également la compatibilité avec Google Chrome Frame.
- `<meta name="robots" content="index,follow">` : spécifie si les moteurs de recherche doivent indexer et suivre la page.

21. Formulaires plus avancés:

- `<fieldset>` : regroupe les éléments de formulaire apparentés et fournit une étiquette pour le groupe
- `<legend>` : fournit une légende ou une description pour un élément `<fieldset>`.
- `<label>` : fournit une étiquette pour un élément de formulaire
- `<select>` : crée une liste déroulante d'options
- `<option>` : spécifie une option dans un élément `<select>`.
- `<textarea>` : crée un champ de saisie de texte sur plusieurs lignes