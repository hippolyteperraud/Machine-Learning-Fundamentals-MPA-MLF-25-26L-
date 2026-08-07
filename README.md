# MPA-MLF – Machine Learning Fundamentals

Travaux pratiques réalisés dans le cadre du cours **Machine Learning Fundamentals (MPA-MLF)**, suivi lors d'un semestre Erasmus à la **FIT VUT Brno** (Vysoké učení technické v Brně / Brno University of Technology), République tchèque.

Ce repository regroupe mes 8 labs : implémentations personnelles, expérimentations et rapports produits au fil du semestre, allant de la prise en main de Python jusqu'aux réseaux de neurones convolutifs et récurrents.

> ⚠️ Il s'agit de mes propres solutions aux exercices proposés en TP. Elles sont partagées à titre de portfolio / traçabilité de mon apprentissage, pas comme un corrigé officiel du cours — libre à toi de t'en inspirer, mais évite le copier-coller si tu es toi-même dans ce cours (cf. section Intégrité académique plus bas).

## Sommaire des labs

| # | Sujet | Contenu |
|---|-------|---------|
| [Lab 1](./Lab1) | Prise en main de Python | Exercices de base en Python : syntaxe, structures de données, manipulation de tableaux (NumPy) — mise à niveau avant les labs de ML |
| [Lab 2](./Lab2) | Clustering & K-means | Algorithme K-means, choix du nombre de clusters, visualisation des résultats |
| [Lab 3](./Lab3) | SVM pour la classification | Support Vector Machines, noyaux (linéaire, RBF...), frontières de décision |
| [Lab 4](./Lab4) | PCA via SVD | Réduction de dimension par décomposition en valeurs singulières (Singular Value Decomposition) |
| [Lab 5](./Lab5) | Réseaux de neurones Feedforward | Construction et entraînement d'un FNN de base |
| [Lab 6](./Lab6) | FNN – Régularisation & hyperparameter tuning | Dropout, weight decay, early stopping, recherche d'hyperparamètres |
| [Lab 7](./Lab7) | Réseaux de neurones convolutifs (CNN) | Convolutions, pooling, classification d'images |
| [Lab 8](./Lab8) | Réseaux de neurones récurrents (RNN) | Traitement de séquences, architectures récurrentes |

> Les noms de dossiers ci-dessus (`Lab1`, `Lab2`, ...) sont indicatifs — adapte les liens pour qu'ils correspondent exactement aux noms de dossiers/fichiers présents dans ton repo (je vois que tu as un mélange de conventions, ex. `Lab_07`, `Lab_08` ; ça vaut le coup d'harmoniser en `Lab1` → `Lab8` avant de passer le repo en public, pour que ce soit plus propre).

## Structure du repository

```
.
├── Lab1/   # Prise en main de Python
├── Lab2/   # Clustering & K-means
├── Lab3/   # SVM
├── Lab4/   # PCA / SVD
├── Lab5/   # Feedforward Neural Networks
├── Lab6/   # FNN + régularisation & tuning
├── Lab7/   # CNN
├── Lab8/   # RNN
└── README.md
```

## Technologies utilisées

- **Python 3**
- **NumPy** / **Pandas** — manipulation de données
- **Matplotlib** / **Seaborn** — visualisation
- **scikit-learn** — clustering, SVM, PCA
- **PyTorch** / **TensorFlow-Keras** — réseaux de neurones (FNN, CNN, RNN)
- **Jupyter Notebook**

*(Adapte cette liste aux librairies réellement utilisées dans tes notebooks si elle diffère.)*

## Installation & exécution

```bash
git clone https://github.com/<ton-utilisateur>/<ton-repo>.git
cd <ton-repo>

python -m venv venv
source venv/bin/activate   # sous Windows : venv\Scripts\activate

pip install -r requirements.txt
jupyter notebook
```

*(Pense à ajouter un `requirements.txt` à la racine du repo si tu n'en as pas encore, pour que les notebooks soient reproductibles.)*

## Contexte

Ces labs ont été réalisés durant mon semestre Erasmus à la **Brno University of Technology (VUT)**, dans le cadre du cours *Machine Learning Fundamentals (MPA-MLF)*.

## Intégrité académique

Ce dépôt est publié une fois le semestre terminé, à des fins de démonstration de mon travail personnel. Si tu suis toi-même ce cours, merci de ne pas copier ces solutions telles quelles — utilise-les uniquement comme référence pour t'aider à comprendre les concepts.

## Auteur

*(Ton nom / lien GitHub / LinkedIn — à compléter)*
