R Notebook
================

Nous sommes entrain de faire un tutoriel pour avoir une belle page sur
github. Pour ce faire nous avons crée un nouveau repository (sandbox).
Sur ce nouveau repository, sur R, nous avons crée ce nouveau notebook.
Nous avons enlevé le texte inutile et nous avons juste laissé le chunk
code pour créer le graphique de cars qui servira d’exemple sur la
lecutre du markdown. De plus ce que l’on veut obtenir en output est un
github\_document et non pas un html (page web).

Chargement des libraries:

``` r
library(rmarkdown)
library(knitr)
```

Après avoir fait ce chargement nous faisons un preview. Cette preview
(knit) ouvre une fenêtre nouvelle sur laquelle on a un apperçu de ce que
l’on a fait.(Sorte d’apperçu avant impression)

``` r
plot(cars)
```

![](test_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->
