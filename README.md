# Random Features Experiments

Ce dépôt contient un notebook explorant les méthodes proposées dans l'article *Random Features for Large-Scale Kernel Machines*.

## Description

Les machines à noyau comme les SVM sont puissantes mais coûteuses en calcul. Cet article propose une approche basée sur des projections aléatoires pour approximer les noyaux tout en accélérant l'apprentissage.

Ce projet met en œuvre et teste ces méthodes :
- **Fourier Features** : Utilisation des sinus et cosinus pour approximer les noyaux RBF.
- **Random Binning Features** : Discrétisation aléatoire de l'espace pour approximer des noyaux dépendant de la distance L1.

## Contenu

- `notebook.ipynb` : Expérimentations sur les méthodes de features aléatoires.
- `data/` : Éventuels fichiers de données.
- `results/` : Résultats des tests et visualisations.

## Installation

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/leaam06/Random-Features-Experiments
   cd Random-Features-Experiments
