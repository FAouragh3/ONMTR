# ONMTR
Exercices et Tutoriels sur R 
Cette extension (package) contient une série 
d'exercices et tutoriels sur le le language R.


## Installation

Pour installer `ONMTR` à partir de [GitHub](https://github.com/),
il suffit d'exécuter dans R le code suivant:

```{r}
##############################################
### Si le package devtools n'est pas installé, 
### activer la ligne de code suivante (supprimer le #)
##############################################

#install.packages("devtools")

### Ensuite exécuter la ligne ci-dessous

devtools::install_github("beabd/ONMTR")
```


## Exécution

Le package `ONMTR` devrait être listé parmi les tutoriels
installés sur votre machine, cliquer sur le menu `Tutorial` 
(l'onglet devrait se trouver sur un des panneaux à droite)  

Vous trouverez ci-dessous les commandes à exécuter pour chaque exercice ou tutoriel

## Installation de R et Rstudio

```{r Installation de R et Rstudio}
learnr::run_tutorial("InstallationR","ONMTR")
```


## Concepts de base

```{r Bases de R}
learnr::run_tutorial("BasesR","ONMTR")
```

