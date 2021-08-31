# grid css: CSS Moderne
Une grille CSS (CSS Grid) peut être définie comme un ensemble croisé de lignes verticales et horizontales. La disposition CSS Grid sépare une page en sections principales. La propriété Grid CSS3 propose un système de disposition basé sur une grille comportant des lignes et des colonnes, qui facilite la conception de pages Web sans positionnement ni flottement. La disposition de la grille nous donne un moyen de créer des structures de grille représentées en CSS, pas en HTML.

## La propriété: Display
Pour rendre élément à un conteneur **grid**, nous devons appliquer la propriété **display** avec les valeurs(**grid** ou **inline-grid**)
* grid: pour lui donner le comportement d'un élément de type block
* inline-grid: pour lui donner le comportement d'un élément de type inline
## La propriété: grid-template-columns
La propriété **grid-template-columns** nous permet de fixer le nombre de colonnes au sein d'un conteneur grid, on peut combiner plusieurs type de mesures en ensemble par exemple (px, pt, %,em, rem,...)
**NB** mais le mieux est utilisé le même type de mesure pour ne pas se perdre.
## La propriété: grid-template-rows
La propriété **grid-template-rows** nous permet de fixer la taille des lignes au sein d'un conteneur grid et elle ne gère pas le nombre de ligne car le nombre de ligne est geré automatiquement, on peut combiner plusieurs type de mesures en ensemble également aussi par exemple (px, pt, %,em, rem,...).
## La propriété grid-column-gap
La propriété **grid-column-gap** permet de gerer la goutière entre les colonnes dans un conteneur grid
## La propriété grid-row-gap
La propriété **grid-row-gap** permet de gerer la goutière entre les lignes dans un conteneur grid.

## La propriété grid-gap
La propriété **grid-gap** est la combinaison des deux premières propriétés précedantes 
<code> { grid-gap: valeurrows valeurcolumns }</code>, on peut aussi les combinées avec <code>{grid-gap: valeur}</code>

## La fonction repeat 
La fonction **repeat()** nous évite de faire de répetition des valeurs des propriétés css. Elle prend deux paramètres: le premier est le nombre de répétition et le deuxième des la valeur à répéter. 

## La propriété: grid-column-start
La propriété **grid-column-start** permet de specifier la **ligne de grid** où l'élément doit commencer(horizontalement) en commençant à compter à partir de 1.

## La propriété: grid-column-end
La propriété **grid-column-end** permet de specifier la **ligne de grid** où l'élément doit se limiter(horizontalement) en commençant à compter à partir de 1.

## La propriété: grid-column-start
La propriété **grid-row-start** permet de specifier la **ligne de grid** où l'élément doit commencer(verticalement) en commençant à compter à partir de 1.

## La propriété: grid-column-end
La propriété **grid-row-end** permet de specifier la **ligne de grid** où l'élément doit se limiter(verticalement) en commençant à compter à partir de 1.
## La veleur: span nombre:
La valeur **span nombre** nous évite de compter le nombre de **ligne de grid**, mais plutôt de compter le nombre de colonne ou de ligne qu'on veut que l'élément occupe.

## Les propriétés: grid-row et grid-column
les propriétés **grid-column** et **grid-row** sont les raccourchies respectives de **grid-column-start, grid-column-end** et **grid-row-start, grid-row-end** 