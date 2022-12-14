## Concepts de base de CSS

> Cette section couvre les concepts de base du CSS, notamment ce qu'est le CSS, pourquoi il est utilisé et comment il est utilisé pour styliser et mettre en page les pages Web.

CSS (Cascading Style Sheets) est un langage de feuille de style utilisé pour décrire l'apparence et le formatage d'un document écrit dans un langage de balisage. Le CSS est utilisé pour contrôler la présentation des éléments d'une page Web, notamment les couleurs, les polices, la mise en page et d'autres styles.

![HTML CSS stylesheet syntax class](css.png)

CSS est un langage déclaratif, ce qui signifie qu'il utilise des déclarations pour spécifier les règles et les styles qui doivent être appliqués à un document. Ces déclarations sont appelées "règles" ou "déclarations". Les règles CSS se composent de deux parties : un sélecteur et un bloc de déclaration. Le sélecteur spécifie le ou les éléments de la page auxquels la règle doit s'appliquer, et le bloc de déclaration contient les styles qui doivent être appliqués aux éléments sélectionnés.

Voici un exemple de règle CSS simple :

```
p {
    color : red ;
    font-size : 18px ;
}   
```

Dans cet exemple, le sélecteur `p` est utilisé pour sélectionner tous les éléments `p` de la page, et le bloc de déclaration spécifie que la couleur du texte doit être rouge et la taille de la police doit être de 18 pixels.

Les règles CSS peuvent être appliquées à une page Web selon trois méthodes différentes :
        
- Les styles en ligne : Les styles en ligne sont appliqués directement aux éléments HTML à l'aide de l'attribut style.
- Styles internes : Les styles internes sont définis dans la section d'en-tête d'un document HTML à l'aide de l'élément style.
- Feuilles de style externes : Les feuilles de style externes,<< stylesheet >> en anglais, sont des fichiers séparés qui contiennent des règles CSS et qui sont liés à un document HTML à l'aide de l'élément link.

Il est en général recommandé d'utiliser des feuilles de style externes pour les projets plus importants, car elles permettent une meilleure organisation et une plus grande facilité de maintenance des styles.

C'est tout pour les concepts de base de CSS. Dans la prochaine leçcon, nous aborderons les différentes façons d'appliquer des styles aux éléments d'une page Web.

[Passez à la leçcon suivante >>](https://github.com/Le-BootCamp-Grow/supports-de-cours/blob/main/notes-de-cours/niveau-d-entree/developpeur-web/semaine_1_jour_2/2_styles_css.md)