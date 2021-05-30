README
================

## Constituciones Políticas de Nicaragua

Este repositorio continue cuatro constituciones políticas de Nicaragua
de los años:

1.  1974
2.  1987
3.  2010
4.  2014

## Uso

Los datos se encuentran en la carpeta `/data` en formato `.rds`, y
contienen las siguientes variables:

1.  `year`: Año de publicación.
2.  `line`: Línea en el texto extraído de la Asamblea Nacional.
3.  `text`: Texto de la constitución de acuerdo a la línea.
4.  `titulo`: Título de la constitución.
5.  `cap`: Capítulo de la constitución (por Título).
6.  `art`: Artículo de la constitución.
7.  `tema`: Tema de la constitución (por Título).

``` r
cons_2014
```

    ## # A tibble: 715 x 7
    ##    year   line text                                  titulo   cap   art   tema  
    ##    <chr> <int> <chr>                                 <chr>    <chr> <chr> <chr> 
    ##  1 2014      1 TEXTO DE LA CONSTITUCIÓN POLÍTICA DE~ PREÁMBU~ <NA>  <NA>  PREÁM~
    ##  2 2014      2 CONSTITUCIÓN POLÍTICA DE NICARAGUA, ~ PREÁMBU~ <NA>  <NA>  PREÁM~
    ##  3 2014      3 Publicada en La Gaceta, Diario Ofici~ PREÁMBU~ <NA>  <NA>  PREÁM~
    ##  4 2014      4 “El Presidente de la República        PREÁMBU~ <NA>  <NA>  PREÁM~
    ##  5 2014      5 Hace saber al pueblo de Nicaragua qu~ PREÁMBU~ <NA>  <NA>  PREÁM~
    ##  6 2014      6 CONSTITUCIÓN POLÍTICA:                PREÁMBU~ <NA>  <NA>  PREÁM~
    ##  7 2014      7 Preámbulo                             PREÁMBU~ <NA>  <NA>  PREÁM~
    ##  8 2014      8 NOSOTROS,                             PREÁMBU~ <NA>  <NA>  PREÁM~
    ##  9 2014      9 Representantes del Pueblo de Nicarag~ PREÁMBU~ <NA>  <NA>  PREÁM~
    ## 10 2014     10 Evocando                              PREÁMBU~ <NA>  <NA>  PREÁM~
    ## # ... with 705 more rows

## Comentarios y sugerencias

Para realizar comentarios o sugerencias sobre la base de datos puedes
abrir un issue en este repositorio:
<https://github.com/RRMaximiliano/constituciones/issues>
