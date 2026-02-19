# 🏙️ Analyse des données Airbnb à :contentReference[oaicite:1]{index=1}

## 📌 Description du projet
Ce projet consiste en une **analyse exploratoire et statistique** du dataset Airbnb de New York.  
L’objectif est de comprendre les **facteurs influençant les prix**, la **disponibilité des logements**, ainsi que les **différences entre les quartiers et les types de logements**, à l’aide de Python et de bibliothèques de data science.

Ce projet s’inscrit dans une démarche d’**analyse de données appliquée au secteur du tourisme et de l’immobilier locatif**.

---

## 🎯 Objectifs
- Explorer et nettoyer le dataset Airbnb
- Identifier les valeurs manquantes et les doublons
- Analyser la distribution des prix et de la disponibilité
- Comparer les prix par quartiers et types de logements
- Étudier les relations entre les variables (analyse bivariée)
- Créer de nouvelles variables pertinentes (feature engineering)
- Visualiser les corrélations entre les variables clés

---

## 🧰 Technologies & bibliothèques utilisées
- **Python**
- **NumPy** – calcul numérique
- **Pandas** – manipulation et analyse des données
- **Matplotlib** – visualisation
- **Seaborn** – visualisation statistique avancée

---

## 📂 Structure du projet
```py
📁 Python-Project-New-York-AirBnb
│
├── 📄 datasets.csv # Dataset Airbnb
├── 📄 analysis.ipynb # Notebook d’analyse (ou script .py)
├── 📄 README.md # Documentation du projet
```

---

## 🔍 Étapes de l’analyse

### 1️⃣ Chargement des données
- Importation du dataset Airbnb
- Vérification de la structure et des types de variables

### 2️⃣ Exploration des données
- Aperçu des premières et dernières lignes
- Dimensions du dataset
- Statistiques descriptives
- Identification des valeurs manquantes et doublons

### 3️⃣ Nettoyage des données
- Suppression des valeurs manquantes
- Suppression des doublons
- Correction des types de variables (ex : `id` converti en objet)

### 4️⃣ Analyse univariée
- Distribution des prix
- Détection et traitement des valeurs aberrantes (outliers)
- Analyse de la disponibilité annuelle (`availability_365`)

### 5️⃣ Feature Engineering
- Création de la variable **prix par lit** (`price per bed`)
- Comparaison par groupe de quartiers

### 6️⃣ Analyse bivariée
- Prix selon les quartiers et le type de logement
- Relation entre nombre d’avis et prix
- Analyse géographique (latitude / longitude)
- Matrice de corrélation entre variables numériques

---

## 📊 Visualisations réalisées
- Histogrammes
- Boxplots
- Barplots
- Scatter plots
- Pair plots
- Heatmap de corrélation

---

## 💡 Principales observations
- Les prix varient fortement selon le **quartier** et le **type de logement**
- Les **outliers** influencent fortement la distribution des prix
- La disponibilité annuelle diffère significativement d’un logement à l’autre
- Certaines variables présentent des corrélations intéressantes avec le prix

---

## 🚀 Améliorations possibles
- Ajout d’un modèle de **Machine Learning** pour prédire les prix
- Analyse temporelle des avis
- Cartographie interactive (Folium / Plotly)
- Normalisation et standardisation des données

---

## 👤 Auteur
**Kodjo Georges AKAKPO**  
📊 Data Analyst | Python | Data Visualization  

---

⭐ *N’hésitez pas à laisser une étoile si ce projet vous a été utile !*
