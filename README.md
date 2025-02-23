# Analyse de Données : Vidéos YouTube les Plus Populaires

Ce projet vise à analyser un dataset contenant des informations sur les vidéos YouTube les plus populaires. L'objectif est d'explorer, nettoyer, analyser et visualiser les données pour en tirer des insights pertinents.

## 📊 Objectifs

1. **Chargement et Exploration des Données** :
   - Charger le dataset avec Pandas.
   - Explorer les premières et dernières lignes.
   - Analyser la structure et les informations générales du dataset.
   - Identifier et gérer les valeurs manquantes et les doublons.

2. **Nettoyage et Préparation des Données** :
   - Convertir certaines colonnes en types numériques.
   - Remplacer les valeurs manquantes et standardiser les colonnes.
   - Créer des indicateurs supplémentaires comme le ratio de likes.

3. **Analyse Statistique et Manipulation** :
   - Calculer les statistiques descriptives (moyenne, médiane, écart-type).
   - Identifier les vidéos les plus vues et les plus aimées.
   - Classer les catégories par nombre total de vues.
   - Analyser la corrélation entre les différentes variables.

4. **Visualisation des Données** :
   - Créer des graphiques pour explorer les tendances :
     - Histogramme des vues
     - Graphique en barres des vidéos les plus populaires
     - Boxplot des vues par catégorie
     - Scatterplot entre vues et likes
     - Regression Linéaire pour montrer la corrélation

## 📁 Structure du Projet

```
├── data/                   # Dossier contenant le dataset
├── notebooks/              # Notebooks Jupyter pour l'analyse
├── src/                    # Scripts Python pour le traitement des données
├── resultats/              # Page Web contenant les conclusions et interprétations de l'analyse
├── README.md               # Documentation du projet
└── requirements.txt        # Dépendances du projet
```

## 🛠️ Prérequis

Assurez-vous d'avoir Python installé sur votre machine. Créez un environnement virtuel et installez les dépendances :

```bash
python -m venv venv
source venv/bin/activate  # Sur Windows : .\venv\Scripts\activate
pip install -r requirements.txt
```

## 📊 Exécution du Projet

1. Lancez un notebook Jupyter pour explorer le dataset :

```bash
jupyter notebook
```

2. Exécutez les différentes étapes d'analyse dans l'ordre :
   - Chargement et exploration
   - Nettoyage des données
   - Analyse statistique
   - Visualisation

## 📈 Résultats Attendus

- Compréhension des tendances sur les vidéos YouTube populaires.
- Identification des catégories et types de vidéos les plus performants.
- Visualisations claires pour communiquer les insights extraits.

## 📌 Améliorations Possibles

- Intégrer des données supplémentaires (durée des vidéos, localisation).
- Automatiser l'analyse avec des fonctions modulaires.
- Créer un tableau de bord interactif pour l'exploration des données.

## 🧑‍💻 Contributions

Les contributions sont les bienvenues ! N'hésitez pas à proposer des améliorations ou des corrections via des pull requests.

## 📄 Licence

Ce projet est sous licence MIT. Vous êtes libre de l'utiliser et de le modifier.

---

