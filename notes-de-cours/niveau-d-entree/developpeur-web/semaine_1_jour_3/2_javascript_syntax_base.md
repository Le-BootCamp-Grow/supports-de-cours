## Syntaxe JavaScript de base, y compris les variables, les types de données, les opérateurs et les structures de contrôle.

> Dans cette section, vous découvrirez la syntaxe de base de JavaScript, notamment les variables, les types de données, les opérateurs et les structures de contrôle.

- Variables : Les variables sont utilisées pour stocker des valeurs de données dans un programme. Elles sont déclarées à l'aide des mot-clés `var`, `let` et `const` suivi du nom de la variable. Par exemple : `let x = 5` ;

- Types de données : JavaScript possède différents types de données, notamment les nombres, les chaînes de caractères, les booléens et les objets. Les nombres sont utilisés pour représenter des valeurs numériques, les chaînes de caractères sont utilisées pour représenter du texte, les booléens peuvent être soit vrais soit faux, et les objets sont utilisés pour stocker des données complexes.

- Opérateurs : Les opérateurs sont utilisés pour effectuer des opérations sur les valeurs de données. JavaScript dispose de plusieurs opérateurs, notamment des opérateurs arithmétiques (par exemple +, -, *, /), des opérateurs de comparaison (par exemple ==, ===, !=, >, <) et des opérateurs logiques (par exemple &&, ||, !).

- Structures de contrôle : Les structures de contrôle sont utilisées pour contrôler le flux d'un programme. JavaScript dispose de diverses structures de contrôle, y compris les instructions `if`, les instructions `switch` et les boucles `for`.

### Examples:

- Les variables:

```
// declaring a variable
var x = 5;

// updating the value of a variable
x = 10;
```

- Les types de données:

```
// nombres
var x = 5;
let y = 10.5;

// chaînes de caractères
let prenom = "John";
let message = 'Hello World!';

// booléens
let isValid = true;
let isInvalid = false;

// objects
let person = {
  name: "John",
  age: 25,
  isMale: true
};
```

- Les operateurs:

```
// opérateurs arithmétiques
let somme = x + y;   // 15
let diff = x - y;  // 5
let prod = x * y;  // 50
let divi = x / y;  // 2

// opérateurs de comparaison
let x = 5 == 10; // false
let y = 10 === "10"; // false
let z = 5 != 10; // true
let a = 10 > 5; // true
let b = 5 < 10; // true

// opérateurs logiques
var x = (5 == 5) && (10 > 5); // true
var y = (5 == 5) || (10 > 5); // true
var z = !(5 == 5); // false
```

- Lestructures de contrôle:

```
// l'instruction if
if (x > 10) {
  // fais quelque chose
}

// l'instruction if-else
if (x > 10) {
  // fais quelque chose
} else {
  // fais quelque chose d'autre
}

// l'instruction  switch
switch (x) {
  case 1:
    // fais quelque chose
    break;
  case 2:
    // fais quelque chose
    break;
  default:
    // fais quelque chose par défaut
}

// la boucle for
for (var i = 0; i < 10; i++) {
  // do something
}
```

[Passez à la section suivante >>](https://github.com/Le-BootCamp-Grow/supports-de-cours/blob/main/notes-de-cours/niveau-d-entree/developpeur-web/semaine_1_jour_3/3_fonctions_objects_tab.md)