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