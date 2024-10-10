# PROJET-THESE: Modélisation du rayonnement solaire des jours de ciel partiellement nuageux de trois sites de Mesures en Côte d’Ivoire


## Par: YEBOUA SIAMAN PAULE-CARINE

----------------------------

## Introduction

Ce dépôt contient le code et les notebooks utilisés pour modéliser le rayonnement solaire 
des jours de ciel partiellement nuageux sur trois sites de mesure en Côte d'Ivoire. 
Le travail s'appuie sur des données de rayonnement solaire mesurées au sol et des images 
satellitaires pour répondre à plusieurs objectifs spécifiques (OS) de la thèse.

## Fichiers de Code (Notebooks)

### Notebook 1: Calcul et Visualisation des Irradiations Solaires (IGH, IGJ, IGM) et Classification du Ciel


* _Nomenclature_ :
Le fichier code se situe dans le dossier `/notebooks` sous l'appellation `[THESE] MODELISATION OS1 & OS2.ipynb`. 


* _Objectif_ :
Calculer les Irradiations Solaires Horaires (IGH), Journalières (IGJ), et Mensuelles (IGM) pour chaque site.
Classifier et caractériser l'état du ciel en utilisant l'indice de clarté horaire (kt). 


* _Contenu_ :
Le notebook calcule les irradiations solaires à partir des mesures minute par minute, puis agrège ces valeurs en unités horaires, journalières, et mensuelles.

L'indice de clarté (kt) est utilisé pour classifier l'état du ciel, en se basant sur le rapport entre le rayonnement global et le rayonnement extra-terrestre.

```
Formules Clés :
IGH = ∑(Ei) / obsx`
IGJ = ∑(IGH)
IGM = ∑(IGJ)
k_t = IGH / IGH_0
```


### Notebook 2: Modélisation du Rayonnement Solaire à partir des Images Satellitaires


* _Nomenclature_ :
Le fichier code se situe dans le dossier `/notebooks` sous l'appellation `[THESE] MODELISATION OS4.ipynb`. 


* _Objectif_ :
Modéliser l’irradiation solaire globale en utilisant des images satellitaires et deux modèles d’estimation : le modèle GISTEL et le modèle HELIOSTAT.

* _Contenu_ : 
Ce notebook présente l’application de deux modèles de télédétection pour l’estimation du rayonnement solaire à partir des images satellitaires.
Les organigrammes des deux modèles sont inclus pour illustrer le processus de calcul.


## Exemples de sorties de Codes



## Exécution du Code

Le code est écrit sous le langage Python. Pour lancer le code, assurez vous d'avoir les données puis suivez les instructions ci dessous

### Via Google Colab

1. Ouvrez Google Colab : [Google Colab](https://colab.research.google.com/).
2. Clonez ce dépôt GitHub en exécutant la commande suivante dans une cellule Colab :

```
!git clone https://github.com/Alassane-niir/Solar-Phd-Project.git
```
3. Ouvrez le notebook que vous souhaitez exécuter dans Colab.


### En local avec Jupyter Notebook

1. Assurez-vous que vous avez installé Jupyter via [Anaconda](https://www.anaconda.com/download):

2. Clonez ce dépôt :

```
git clone https://github.com/Alassane-niir/Solar-Phd-Project.git
```
3. Accédez au dossier et lancez Jupyter.