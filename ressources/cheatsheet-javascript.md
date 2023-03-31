# CSS/CSS3 Cheat sheet
## Aide-mémoire CSS/CSS3

> This cheat sheet is made by Growcampus.
> For JavaScript development from entry-level to advanced concepts.

# HTML Cheat sheet
## Aide-mémoire HTML

> This cheat sheet is made by Growcampus.
> For web developers from entry-level to senior developers.

1.  Les Variables :

-   Utilisez le mot-clé `var`, `let` ou `const` pour déclarer une variable.
-   Les variables déclarées avec `var` ont une portée fonctionnelle, tandis que celles déclarées avec `let` et `const` ont une portée de bloc `{ }`.
-   Utilisez `let` pour les variables qui changeront et `const` pour celles qui ne changeront pas.

2. Les Types de données :

-   JavaScript dispose de six types de données primitives : `string` (chaîne de caractères), `number` (nombre), `boolean` (booléen), null, undefined (non défini) et symbol (symbole).
-   Les objets, ("Object" en anglais), sont un type de données de référence et comprennent les tableaux ("array" en anglais), les fonctions ("function" en anglais) et les objets ("object" en anglais).

3. Les Opérateurs :

-   Les opérateurs arithmétiques (`+`, `-`, `*`, `/`, `%`) effectuent des opérations mathématiques.
-   Les opérateurs de comparaison (`==`, `!=`, `===`, `!==`, `<`, `>`, `<=`, `>=`) comparent des valeurs.
-   Les opérateurs logiques (`&&`, `||`, `!`) combinent plusieurs conditions.
-   Les opérateurs d'affectation (`=`, `+=`, `-=`, `*=`, `/=`, `%=`) affectent des valeurs.

4. Les Conditionnelles :

-   Utilisez les instructions `if` pour exécuter du code en fonction d'une condition.
-   Utilisez `else` pour exécuter le code si la condition `if` n'est pas remplie.
-   Utilisez `else if` pour exécuter le code si une autre condition est remplie.
-   Utilisez l'opérateur ternaire (`condition ? valeur1 : valeur2`) comme raccourci pour les instructions if simples.

5. Les Boucles :

-   Utilisez les boucles `for` pour exécuter le code un nombre déterminé de fois.
-   Utilisez les boucles `while` pour exécuter le code tant qu'une condition est vraie.
-   Utilisez les boucles `do...while` pour exécuter le code au moins une fois, puis tant qu'une condition est vraie.
-   Utiliser les instructions `break` et `continue` pour contrôler le comportement de la boucle.

 6. Les Fonctions :

-   Utilisez `function` pour déclarer une fonction.
-   Les fonctions peuvent prendre des arguments `function faireLaSomme(num1, num2)` et des valeurs de retour.
-   Les expressions de fonction permettent de créer des fonctions anonymes.
-   Utiliser les fonctions fléchées, "arrow functions", comme raccourci pour les expressions de fonction.

7.  Tableaux :

-   Utilisez `[]` pour créer un tableau vide ou pour initialiser un tableau avec des valeurs.
-   Utilisez les méthodes de tableau telles que `push()`, `pop()`, `shift()` et `unshift()` pour modifier les tableaux.
-   Utiliser `slice()` pour créer une copie d'un tableau ou pour extraire une partie d'un tableau.
-   Utiliser `forEach()`, `map()`, `filter()` et `reduce()` pour manipuler les tableaux.   

8. Objets :

-   Utilisez `{}` pour créer un objet vide ou pour initialiser un objet avec des propriétés.
-   Utilisez la notation par points, "dot notation" en anglais, (`object.property`) ou la notation par crochets, "bracket notation" (`object['property']`) pour accéder aux propriétés de l'objet.
-   Utilisez `delete` pour supprimer une propriété d'un objet.
-   Utilisez `Object.keys()`, `Object.values()` et `Object.entries()` pour manipuler les objets.

9.  Les classes :

-   Utiliser le mot-clé `class` pour définir une classe.
-   Utiliser la méthode `constructor` pour créer des objets.
-   Utiliser `extends` pour créer une sous-classe.
-   Utiliser `super()` pour appeler le constructeur parent.

10. La Programmation asynchrone :

-   Utiliser `setTimeout()` et `setInterval()` pour exécuter du code après un délai ou à des intervalles déterminés.
-   Utiliser `Promise` et `async/await` pour gérer les opérations asynchrones.
-   Utiliser `fetch()` pour effectuer des requêtes HTTP et gérer les réponses.

11. Scope - La Portée :

-   La portée globale fait référence aux variables qui sont accessibles dans l'ensemble du programme.
-   La portée locale fait référence aux variables qui ne sont accessibles qu'à l'intérieur d'une fonction ou d'un bloc spécifique.
-   Utilisez `var` pour déclarer des variables de portée globale et `let` ou `const` pour déclarer des variables de portée locale.

12. Hoisting :

-   Les variables et les fonctions JavaScript sont accessibles avant d'être déclarées, grâce à la fonction "hoisting".
-   Les variables déclarées avec `var` sont montées au sommet de leur portée, tandis que les variables déclarées avec `let` et `const` ne sont pas hissées.
-   Les déclarations de fonctions sont également montées au sommet de leur portée, alors que les expressions de fonctions ne le sont pas.

13. Coercition de type :

-   JavaScript convertit automatiquement les valeurs en un type différent lorsque c'est nécessaire, par exemple lors d'opérations sur des types de données différents.
-   Utilisez l'égalité stricte (`===`) pour comparer des valeurs sans coercition de type.

14. Manipulation d'événements :

-   Utilisez des récepteurs d'événements pour gérer les entrées de l'utilisateur, telles que les clics ou les frappes au clavier.
-   Utilisez `addEventListener()` pour attacher un écouteur d'événement à un élément.
-   Utilisez l'objet `event` pour accéder aux informations relatives à l'événement.

15. Manipulation du DOM :

-   Utiliser le modèle d'objet de document (DOM) pour manipuler le HTML et le CSS sur une page web.
-   Utilisez `document.querySelector()` et `document.querySelectorAll()` pour sélectionner des éléments sur la page.
-   Utilisez les propriétés et les méthodes de l'élément pour manipuler son contenu et son style.

16. Expressions régulières :

-   Les expressions régulières sont des modèles utilisés pour faire correspondre des combinaisons de caractères dans des chaînes.
-   Utilisez `RegExp` pour créer un objet d'expression régulière.
-   Utilisez des méthodes telles que `test()`, `exec()` et `match()` pour travailler avec des expressions régulières.

17. Gestion des erreurs :

-   Utilisez `try...catch` pour gérer les erreurs qui peuvent survenir dans votre code.
-   Utilisez `throw` pour créer une erreur personnalisée.
-   Utilisez l'objet `Error` pour obtenir des informations sur une erreur.

18. Débogage :

-   Utilisez `console.log()` pour afficher des valeurs sur la console à des fins de débogage.
-   Utilisez des points d'arrêt pour interrompre l'exécution du code à une ligne spécifique afin d'étudier l'état du programme.

### Quelques syntaxes, extraits de code et exemples simples pour compléter les concepts énumérés ci-dessus :

19. Les déclarations conditionnelles : :

```JavaScript
if (condition) {
  // le code à exécuter si la condition est vraie...
} else if (anotherCondition) {
  // le code à exécuter si une autre condition est vraie...
} else {
  // le code à exécuter si aucune condition n'est vraie...
}
```

20. Les boucles :

```JavaScript
// la boucle for
for (let i = 0; i < array.length; i++) {
  // code à exécuter lors de chaque itération
}

// la boucle while
while (condition) {
  // code à exécuter LORSQUE la condition est vraie
}

// la boucle do-while
do {
  // code à exécuter au moins une fois
} while (condition);
```

21. Fonctions :

```JavaScript
// déclaration de fonction
function nomDeFonction(argument1, argument2) {
  // code à exécuter lorsque la fonction est appelée
  return resultat;
}

// expression de fonction
const nomDeFonction = function(argument1, argument2) {
  // code à exécuter lorsque la fonction est appelée
  return resultat;
}

// arrow function : fonction fléchée
const nomDeFonction = (argument1, argument2) => {
  // code à exécuter lorsque la fonction est appelée
  return resultat;
}
```

22. Arrays - Les Tableaux :

```JavaScript
const array = [élément1, élément2, élément3];

// accès aux éléments d'un tableau
const premierElément = array[0];

// ajouter et supprimer des éléments de tableau
array.push(nouvelElément);
array.pop();
array.shift();
array.unshift(nouvelElément);

// itération sur les tableaux
array.forEach((élément, index) => {
  // code to execute on each iteration
});
```

23. Les Objets :

```JavaScript
const objet = {
  clé1: valeur1,
  clé2: valeur2,
  clé3: valeur3
};

// accéder aux propriétés des objets
const valeurDePropriété = objet.clé1;

// ajouter et supprimer des propriétés d'objets
objet.clé4 = valeur4;
delete objet.clé3;

// itération sur les propriétés d'un objet
for (let clé in objet) {
  // code à exécuter lors de chaque itération
}
```

25. Promesses :

```JavaScript
const promesse = new Promise((resolve, reject) => {
  // un code asynchrone qui peut résoudre ou rejeter la promesse
});

promesse.then((result) => {
  // code à exécuter lorsque la promesse est résolue
}).catch((error) => {
  // code à exécuter lorsque la promesse est rejetée
});
```