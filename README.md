# **HTML/CSS**

## ** structure d'une page Html **

  - title
  - Head  / Métadonnées
  - header
  - Body
  - style
  - section
  - div
  - footer


#  Définitions générales Css :

  #### Class :
  Éléments central du html / css, les classes permettent de sélectionner plusieurs éléments et de leur appliquer du style dans l’ensemble.
  On définit à travers les classes, des propriétés communes à plusieurs éléments.

  #### Id :
  dentité de la balise, l’attribut ID permet d’identifier un balise précisément. Elle va nous permettre d’appliquer du style qui ne doit apparaître que sur cet élément.

  #### Typo / Font / Police de caractère :
  La police de caractère correspond à ce que l’on nomme en css la font-family.
  Ce sont les visuels de caractère qui vont nous permettre de changer l’affichage du texte.
  On peut les récupérer sur  google font ou Dafont et les charger via un système de balise <link> ou directement dans le css via ce que l’on appel les media queries.



#  Terminologies Html / Css :
  ``` html
<head> : Le head contient toutes les <meta> ou métadonnée. Ce sont les informations structurelles de la page qui n'apparaîtront pas directement à l'écran mais qui sont nécessaire pour le bon fonctionnement de la page.

 <body> : Représente le corps de la page HTML.(un seul par document)

 <header> : Partie haute de la page web/html. Contient en général le <h1> et la navigation <nav>

 <link>  : balise servant à charger du contenus CSS -- police + feuille de style

 <p> définit un paragraphe.

 <span> : pour sélectionner une partie du texte que l’on veut modifié.

 <strong> / <b> : affiche un texte en gras

- <u> : souligne un texte

- <i> : affiche le texte en italique

- <em> : italique ou gras pour un texte ( dépend du navigateur )

- <div> :définit une division ou une section,appelé aussi calque
```

**.container :** la classe container va nous servir à définir un espace donné qui contient les données dans une partie de la page. C’est une classe que l’on définit soi même.  
 ### ATTRIBUTS :
 les attributs sont les informations notées a l'interieur d'une balise.

- float → left / right :
Mettre une image en habillage du texte
positionner un élément à droite ou à gauche d’un autre.
inconvénients : sort du flux → certaines propriétés ne fonctionnent pas et les éléments ne sont plus relatif entre eux.
font-family :change la police de caractères

### DISPLAY :

| Balises | Definition |
| --- | --- |
| inline           | aligne les éléments les uns à la suite des autres.
| blok             | réserve tout l’espace disponible sur la ligne, illustré par une marge   qui remplis l’espace.|
| inline-block     | lorsque des éléments inline-block sont côte à côte, ils se mettent à la suite et ensemble, forment un block. |
