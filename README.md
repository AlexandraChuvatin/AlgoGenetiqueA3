# Approximation de fonction par Algorithme génétiques
Projet réalisé dans le cadre de ma première année de cycle ingénieur visant à approximer les parmètres d'une fonction à l'aide d'un algorithme génétique.

![image](https://user-images.githubusercontent.com/60775531/213716484-fd4b0aa3-d45b-400e-8ab5-d1b48ced8347.png)


## Introduction

Des astronomes ont observé une nouvelle étoile inconnue. On souhaite trouver une fonction qui approche au mieux la température de celle-ci. Les astronomes supposent que l'étoile suit une fonction dite de Weierstrass avec plusieurs périodicités imbriquées au sens fractale que l'on définit comme suit:
t(i)=∑_(n=0)^c▒〖a^n*cos⁡(b^n πi)〗

Avec t(i) la température de l'étoile à un instant i donné, avec pour ensemble de paramètres:
* A={ a∈R | a∈├]0,1┤[  }
* B={ b∈N | b∈[1,20]  }
* C={ c∈N | c∈[1,20]  }

On souhaite réaliser un algorithme génétique capable de trouver une bonne combinaison de paramètres expliquant au mieux la température de l’étoile. Pour répondre à ce problème, on définit donc un individu comme un combinaison des 3 paramètres recherchés : le triplet (a, b, c), répondant aux contraintes ci-dessus. 
La taille de l’espace de recherche dépend des paramètres a, b et c. De plus, le nombre de chiffre après la virgule pour le paramètre a joue également sur la taille de l’espace de recherche. Dans la version finale de mon programme, le nombre est arrondi à 4 chiffres après la virgule, ce qui donne un espace de recherche de 10^4*20*20 soit 4*10^6 possibilités.


## Projet

### Code
[Fichier code](https://github.com/AlexandraChuvatin/AlgoGenetiqueA3/blob/main/chuvatin_alexandra.py)


### Data

[Data](https://github.com/AlexandraChuvatin/AlgoGenetiqueA3/blob/main/temperature_sample.csv)

### Rapport

Vous trouverez également le [rapport](https://github.com/AlexandraChuvatin/AlgoGenetiqueA3/blob/main/Rapport_DIA_chuvatin_alexandra.docx) rédigé dans le cadre du projet afin de comprendre les étapes de réflexion.
