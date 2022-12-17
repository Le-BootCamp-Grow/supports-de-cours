## Exemples

- Exemple 1 :

Disons que nous voulons ajouter un formulaire simple à notre page Web qui demande à l'utilisateur son nom. Nous pouvons utiliser JavaScript pour créer une invite qui s'affiche lorsque l'utilisateur clique sur un bouton.

Voici le code pour le bouton et l'invite :

```
<button onclick="prompt('Veuillez entrer votre nom')">Cliquez ici pour entrer votre nom</button>
```

L'invite apparaîtra lorsque l'utilisateur cliquera sur le bouton, et il pourra saisir son nom dans le champ de texte.

- Exemple 2 :

Supposons maintenant que nous voulions afficher le nom de l'utilisateur sur la page Web après qu'il l'ait saisi dans l'invite. Nous pouvons utiliser JavaScript pour récupérer la saisie de l'utilisateur et l'insérer dans le document HTML.

Voici le code permettant de récupérer la saisie de l'utilisateur et de l'insérer dans le document HTML :

```
<button onclick="var nomUtilisateur = prompt('Please enter your name'); document.getElementById('nom-affiche').innerHTML = nomUtilisateur">Cliquez ici pour entrer votre nom</button>

<p id="nom-affiche"></p>
```

Lorsque l'utilisateur clique sur le bouton, l'invite apparaît et il peut saisir son nom. Une fois qu'il aura soumis son nom, le code JavaScript saisira l'entrée et l'insérera dans le document HTML, plus précisément dans l'élément avec l'id de "nom-affiche".

### Activité : Une simple liste de choses à faire

Pour cet exercice, nous allons créer une simple liste de tâches à faire. L'utilisateur peut entrer ses tâches dans une invite, et ensuite les tâches seront ajoutées à une liste sur la page web.

Tout d'abord, créons le HTML de la liste de tâches :

```
<h1>Ma liste de choses à faire</h1>
<ul id="liste-de-taches"></ul>
```

Ensuite, nous ajouterons un bouton qui déclenchera l'invitation à l'utilisateur à saisir ses tâches :

```
<button onclick="addTask()">Add a task</button>
```

Enfin, nous créerons la fonction JavaScript qui saisira l'entrée de l'utilisateur, l'ajoutera à la liste et effacera l'invite pour que l'utilisateur puisse ajouter d'autres tâches :

```
function ajouteTaxhe() {
var tache = prompt('Entrer une tache');
var tacheaFaire = document.getElementById('liste-de-taches');
tacheaFaire.innerHTML += '<li>' + tache + '</li>';
prompt.value = '';
}
```

Essayez d'ajouter plusieurs tâches à votre liste de tâches et voyez comment la liste se met à jour sur la page Web.

[Suivant : Exercez vous ! >>]()