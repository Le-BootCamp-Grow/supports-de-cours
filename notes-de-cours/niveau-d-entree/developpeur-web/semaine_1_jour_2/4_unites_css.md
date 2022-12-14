## Unités CSS

> Cette section explique les différentes unités qui peuvent être utilisées avec les propriétés CSS, telles que les pixels, les ems et les pourcentages.

Les unités CSS sont un moyen de spécifier la taille de certaines propriétés CSS, telles que la largeur, la hauteur et la taille de la police d'un élément. Il existe plusieurs unités différentes qui peuvent être utilisées avec les propriétés CSS, notamment les pixels, les ems et les pourcentages.

Les pixels, ou px, sont des unités de taille fixe qui sont utilisées pour spécifier la taille d'un élément en termes de nombre de pixels à l'écran. Par exemple, pour spécifier que la largeur d'un élément doit être de 100 pixels, vous devez utiliser le CSS suivant :

```
largeur: 100px;
```

Les unités `em` et `rem` sont des unités relatives utilisées pour spécifier la taille d'un élément. L'unité `em` est relative à la taille de la police de l'élément auquel elle est appliquée. Ainsi, si un élément a une taille de police de 16 pixels et que vous appliquez une valeur `em` de 2 à la propriété `width`, la largeur résultante sera de 32 pixels (2 x 16 = 32).

L'unité `rem`, quant à elle, est relative à l'élément racine du document, qui est généralement l'élément `<html>`. Cela signifie que si la taille de la police de l'élément `<html>` est de 16 pixels et que vous appliquez une valeur `rem` de 2 à la propriété height d'un objet, la hauteur résultante de l'objet sera de 32 pixels (2 x 16 = 32), tout comme avec l'unité em.

En général, l'unité `rem` est considérée comme plus prévisible et plus facile à utiliser que l'unité `em`, car elle fait toujours référence à la taille de police de l'élément racine, indépendamment de l'endroit où elle est utilisée dans le document. Cela en fait un outil utile pour créer des conceptions évolutives et réactives.

Pour spécifier que la taille de la police d'un élément doit être de 2 ems, vous devez utiliser le code CSS suivant :

```
font-size: 2em;
```

En revanche, pour spécifier que la taille de la police d'un élément doit être de 2 rems, vous devez utiliser le code CSS suivant :

```
font-size: 2rem;
```

Les pourcentages, ou %, sont des unités relatives utilisées pour spécifier la taille d'un élément en fonction de la taille de l'élément parent. Par exemple, pour spécifier que la largeur d'un élément doit correspondre à 50 % de la largeur de l'élément parent, vous devez utiliser le code CSS suivant :

```
width: 50%;
```

Il est important de noter que toutes les propriétés CSS n'acceptent pas toutes les unités. Certaines propriétés, telles que la largeur et la hauteur d'un élément, peuvent accepter les pixels, les ems et les pourcentages. D'autres propriétés, telles que la taille de la police d'un élément, n'acceptent que certaines unités, comme les pixels ou les ems. Il est important de consulter la documentation relative à une propriété CSS pour déterminer quelles unités elle accepte.

En résumé, les unités CSS sont un moyen de spécifier la taille de certaines propriétés CSS, telles que la largeur, la hauteur et la taille de police d'un élément. Il existe plusieurs unités différentes qui peuvent être utilisées avec les propriétés CSS, notamment les pixels, les ems, les rems et les pourcentages.

[Passez à la leçcon suivante >>]()