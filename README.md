### 📄 `README.md`
# 🏍️ My Data App - Motocycles Data Viewer

Bienvenue dans **My Data App**, une application interactive construite avec **Streamlit** qui permet d'explorer des données sur les motocyclettes extraites du site [Expat-Dakar](https://www.expat-dakar.com).


## 🔧 Fonctionnalités

- 📂 Affichage interactif des fichiers CSV contenant des annonces de motos.
- 📏 Visualisation des dimensions du jeu de données (nombre de lignes et colonnes).
- 🔍 Barre de recherche pour filtrer les résultats par mot-clé.
- 💅 Interface web stylisée, accessible localement.


## 📁 Structure du projet


mon\_projet/
│
├── app.py                  # Application Streamlit
├── data/
│   ├── motos\_scooters1.csv
│   ├── motos\_scooters2.csv
│   ├── motos\_scooters3.csv
│   ├── motos\_scooters4.csv
│   └── motos\_scooters5.csv
└── README.md


## 🚀 Lancement de l'application

### Prérequis

- Python 3.7+
- Les bibliothèques suivantes : `streamlit`, `pandas`

### Installation

pip install streamlit pandas

### Exécution

Dans le terminal :

streamlit run app.py

L'application s'ouvrira automatiquement dans votre navigateur par défaut à l'adresse :
[http://localhost:8501](http://localhost:8501)


## 🧠 Technologies utilisées

* [Streamlit](https://streamlit.io) – pour créer l'application web
* [Pandas](https://pandas.pydata.org) – pour la manipulation des données
* HTML/CSS – pour le style dans l'interface Streamlit


## 📌 Auteur

**Niako Kebe** 
 [Email](mailto:drivenindata@gmail.com)


## 💡 Idées futures

* Ajout d’un bouton de téléchargement CSV
* Visualisation des prix avec des graphiques interactifs
* Analyse de tendance par marque ou modèle

