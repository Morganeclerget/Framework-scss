# Bienvenue sur mon Framework !

**Celui-ci propose 6 types de classes différentes :**

1. Système de colonnes pour le placement des éléments
2. Gestion des margins
3. Gestion des paddings
4. Gestion de la justification du contenu 
5. Gestion de l'alignement du contenu
6. Gestion du responsive


## 1. Système de colonnes pour le placement des éléments

La page est divisée en 12 colonnes : 

On a donc une variable i qui définit le nombre de colonnes de 1 à 12 que doit prendre un élément.
La classe associée s'écrit de cette manière : 

      .col-i
      
_____



## 2. Gérer les margins :

Le framework permet de gérer les margins jusqu'à 4 niveaux multiplicateurs différents en se basant sur une variable "$margin" :

      $margin : 20px;  // Variable modifiable directement dans le scss

Ce nombre muliplicateur maximal peut également être géré dans le scss via la variable suivante : 

      $nbSpacing : 4;



**Formation de la classe à utiliser : m(x)-i**

le "x-" peut être remplacé par  :

- m-   : margin 
- mt-  : margin-top
- mr-  : margin-right
- mb-  : margin-bottom
- ml-  : margin-left

*ex :* 

      class="mt-2"  // = margin-top 

mauto  : margin-auto (centrer le contenu dans un bloc)

_____

## 3. Gérer les paddings :

Les paddings se gèrent de la même manière que les margins (CF "2. Gérer les margins").

La variable $nbSpacing est utilisée pour les 4 niveaux de gestion différents.

**Formation de la classe à utiliser : p(x)-i**

x-  :

- p-   : padding 
- pt-  : padding-top
- pr-  : padding-right
- pb-  : padding-bottom
- pl-  : padding-left

ex : 

      class="pr-3"

_____

**Gérer la justification du contenu**

- content-center : Centrer le contenu

- content-start : Justifier le contenu au début du bloc

- content-end : Justifier le contenu à la fin du bloc

- content-between : Espacer le contenu proportionnellement entre le début et la fin du bloc
   
- content-around : Espacer le contenu de manière égale entre les bords du contenu et de manière proportionnelle pour le contenu lui-même

- content-evenly : Espacer le contenu de manière égale entre les bords du contenu et le contenu lui-même

_____


**Gérer l'alignement du contenu**

- al-end : aligner à la fin

- al-center : aligner au centre 

- al-stretch : étirer sur toute la largeur/hauteur

- al-content : aligner sur le contenu 

_____

**Gérer le responsive**

- col-lg-i : Utilisé pour la version "desktop"

- col-md-i : Utilisé pour la version "tablet"

- col-sm-i : Utilisé pour la version "mobile"





