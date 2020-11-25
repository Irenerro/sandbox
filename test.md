R Notebook
================

  - [Titre 1](#titre-1)
      - [sous titre A](#sous-titre-a)
      - [sous titre B](#sous-titre-b)

# Titre 1

## sous titre A

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

## sous titre B

``` r
plot(cars)
```

![](test_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->

On veut garder une trace du script ainsi on va push les fichiers .Rmd et
.md. Le .md est celui qui va être interpretable par github pour faire
une page. Ce fichier va être associé à un dossier contenant les figures
à part, qui seront utilisées par github pour faire la présentation.

Nous avons mis github\_document: toc (table of content) pour créer un
sommaire. Ensuite nous avons rajouté titre 1 et sous titre A et sous
titre B. Les ajouts postérieurs au commit et push, faut les sauvegarder
ET faire un deuxième preview (créer un document .md actualisé\!). Faire
gaffe à laisser un espace entre \# et le titre pour qu’il ne soit pas lu
comme un commentaire. Notre depth est marqué à 2: ainsi le markdown
reconnaît que jusqu’à 2 dièses de profondeur en titre.
