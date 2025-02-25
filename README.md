# Machine learning avec tidymodels 

## À Propos  

Ce projet utilise le framework tidymodels pour réaliser une analyse de données et construire des modèles 
de machine learning en R. Il utilise les différentes approches offertent par tidymodels, le prétraitement des données, 
l'ajustement des modèles et l'évaluation des performances. Nous comparons aussi les performances de tidymodels 
avec un modèle des k plus proches voisins (KNN).   



## Installation et chargement des packages

Il faut installer tidymodels et charger les différents packages ci-dessous:  

library(tidyverse)  
library(tidymodels)  
library(ggcorrplot)  
library(caret)  
library(brulee)

## Données

Les informations pour la démonstration proviennent du dépôt de machine learning de l'Université de Californie
à Irvine (UCI).
Il s'agit de la base de données sur le cancer du sein au Wisconsin 
<https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic>   
