
# Credit Risk Scoring

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![License](https://img.shields.io/badge/License-Apache%202.0-green)
![Status](https://img.shields.io/badge/Project-Complete-brightgreen)
![Model](https://img.shields.io/badge/Model-RandomForest-orange)

Modélisation du risque de défaut à partir de données de crédit client.
Ce projet a été réalisé dans le cadre du Master MoSEF à l’Université Paris 1.

## 🎯 Objectif
Élaborer un modèle prédictif pour estimer la probabilité de défaut d’un client à partir de données socio-financières.

## 📁 Structure
- `data/` : fichiers CSV d'entrée (non trackés par Git)
- `models/` : modèles sauvegardés (.pkl)
- `notebooks/` : notebooks pour la régression logistique et Random Forest
- `src/` : scripts Python réutilisables (optionnel)
- `assets/` : images pour le README

## 🛠 Stack technique
- Python 3.10
- pandas, scikit-learn, matplotlib
- imbalanced-learn, optbinning, shap
- Jupyter, Poetry

## 📊 Modèles testés
- Régression Logistique (avec et sans SMOTE)
- Random Forest (avec tuning via GridSearchCV)

## 🔍 Résultats
- Modèle Random Forest : AUC-ROC = **0.94**
- F1-Score défaut (classe 1) ≈ **0.73**
- Explicabilité : **Shapley Values** utilisées pour interprétation

---

## 🚀 Installation et exécution

### 0. Prérequis
Utiliser un IDE comme **VSCode** ou **PyCharm**, et Python ≥ 3.10

### 1. Installer pip (si ce n’est pas déjà fait) :
```bash
python3 -m ensurepip --upgrade
```

### 2. Installer Poetry :
```bash
pip install poetry
```

### 3. Installer les dépendances du projet :
```bash
poetry install
```

*Un message d’avertissement peut apparaître, mais n’empêche pas le bon fonctionnement du projet.*

---

### ▶️ Exécution des notebooks

1. Lancer VSCode ou Jupyter Lab dans le dossier du projet  
2. Ouvrir l’un des notebooks de `notebooks/`
3. Sélectionner le kernel Python lié au projet (ex. `projet_scoring (Python 3.11.x)`)
4. Exécuter toutes les cellules via `Run All` ou `Shift+Entrée`

> ⚠️ Ne pas ouvrir plusieurs IDE/Jupyter simultanément : cela peut empêcher le bon chargement de l’environnement.

---

## 📄 Licence
Projet sous licence Apache 2.0.

