Petite astuce : pour fixer notre header tout en haut sans s'embêter à lui faire recouvrir toute la largeur de la page via des propriétés left et right, et sans mettre une immense marge au corps de notre site pour éviter qu'il passe sous le header, nous pouvons directement utiliser la classe sticky-top proposée par Bootstrap. Cette classe va coller notre header en haut de la page, tout en le considérant comme un élément relatif du site : pas besoin de propriétés supplémentaires !

<header class="sticky-top ...">
    ...
</header>