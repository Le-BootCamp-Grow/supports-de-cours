# HTML Cheat sheet
## Aide-mémoire HTML

> This cheat sheet is made by Growcampus.
> For web developers from entry-level to senior developers.

1.  Structure de base HTML :

```HTML
 <!DOCTYPE html>
 <html>
   <head>
     <title>Titre de Page</title>
   </head>
   <body>
     <!--Content Goes Here-->
   </body>
 </html>
 ```

2. Créer des titres :

```HTML
 <h1>Titre 1</h1>
 <h2>Titre 2</h2>
 <h3>Titre 3</h3>
 <h4>Titre 4</h4>
 <h5>Titre 5</h5>
 <h6>Titre 6</h6>
```

3. Créer un paragraphe :

```HTML
 <p>Voici un paragraphe.</p>
```

 
4. Créer un lien :

```HTML
 <a href="https://www.ecolegrow.tech">Texte du lien</a>
 <a href="mailto:email@ecolegrow.tech">Envoyez-moi un e-mail</a>
 <a href="tel:123-456-7890">Appelez-moi</a>
```

Pour créer un lien qui, lorsqu'il est cliqué, ouvre l'URL spécifiée dans l'attribut href dans une nouvelle fenêtre ou un nouvel onglet du navigateur :

```HTML
 <a href="https://www.ecolegrow.tech" target="_blank">Texte du lien</a>
```
 
Pour créer un lien avec un attribut title qui affiche une info-bulle lorsque l'utilisateur survole le lien :

```HTML
 <a href="https://www.example.com" title="Link Title">Texte du lien</a>
```

Pour créer un lien qui, lorsqu'il est cliqué, fait défiler l'utilisateur jusqu'à la section de la page dont l'ID est spécifié dans l'attribut href :

```HTML
 <a href="#section1">Aller à la Section 1</a>
```

Créer un lien qui, lorsqu'il est cliqué, télécharge le fichier spécifié dans l'attribut href. Le type de fichier peut être remplacé par n'importe quel type de fichier (par exemple, .docx, .png, etc.) :

```HTML
 <a href="document.pdf">Télécharger PDF</a>
```


5. Créer une image :

```HTML
 <img src="image.jpg" alt="Description de l'Image">
```

 6. Créer une liste non-ordonnée (à puces) :

```HTML
 <ul>
   <li>Article 1</li>
   <li>Article 2</li>
   <li>Article 3</li>
 </ul>
```

Créer une liste ordonnée (numérotée) :

```HTML
 <ol>
   <li>Article 1</li>
   <li>Article 2</li>
   <li>Article 3</li>
 </ol>
```

7.  Créer une table :

```HTML
 <table>
   <thead>
     <tr>
       <th>Header 1</th>
       <th>Header 2</th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td>Row 1, Column 1</td>
       <td>Row 1, Column 2</td>
     </tr>
     <tr>
       <td>Row 2, Column 1</td>
       <td>Row 2, Column 2</td>
     </tr>
   </tbody>
 </table>
```

8. Créer un formulaire :

```HTML
 <form action="/envoyer-formulaire" method="POST">
   <label for="name">Nom:</label>
   <input type="text" id="name" name="name">
   <br>
   <label for="email">E-mail:</label>
   <input type="email" id="email" name="email">
   <br>
   <label for="message">Message:</label>
   <textarea id="message" name="message"></textarea>
   <br>
   <input type="submit" value="Envoyer">
 </form>
```

9.  Faire un commentaire :

```HTML
 <!--Voici un commentaire-->
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