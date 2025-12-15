# Classification de compositeurs – Projet Machine Learning

## Objectif
Ce projet a pour objectif de **classifier le compositeur d’un morceau à partir de fichiers MIDI**
en utilisant des techniques de **Machine Learning classique**.

Le projet est volontairement structuré autour d’un **unique notebook**

---

## Contenu du projet
- Un **notebook Python** contenant :
  - le chargement des données
  - l’extraction des caractéristiques MIDI
  - la préparation des données
  - l’entraînement du modèle
  - l’évaluation des performances
- Modèle de classification basé sur **RandomForest (scikit-learn)**

---

## Exécution du projet
Le projet se lance via le notebook.

## Prérequis

- Python **3.10** 
- Environnement virtuel Python (`venv`)

- Le projet a été développé et testé avec Python 3.10.  
- L’utilisation de versions plus récentes (ex. 3.12 / 3.13) peut entraîner des incompatibilités avec certaines dépendances.

### Étapes :
Il est recommandé d’utiliser un environnement virtuel Python (`venv`) pour installer les dépendances.

```bash
py -3.10 -m venv venv
venv\Scripts\activate      # powershell
python -m pip install --upgrade pip
```

```bash
pip install -r requirements.txt
```