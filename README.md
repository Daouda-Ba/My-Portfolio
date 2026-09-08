# Daouda Ba | Portfolio Data Science, IA & MLOps

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daouda-ba-b9b21b2b4)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Daouda-Ba)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daoudaba4500@gmail.com)

---

## Profil

Je développe des projets appliqués en **machine learning**, **computer vision**, **NLP/RAG**, **MLOps**, **API data** et **applications web data-driven**.
Ce portfolio présente des réalisations concrètes autour de la détection d'objets, de l'OCR, de la fraude bancaire, de l'analyse audio médicale, du monitoring de modèles IA, de l'IoT et de l'exploration de données littéraires.

L'objectif de ce README est de documenter les projets de manière claire, professionnelle et authentique, sans ajouter de résultats ou de métriques non vérifiés.

---

## Domaines De Compétence

- **Machine Learning** : classification, régression, comparaison de modèles, validation croisée, optimisation d'hyperparamètres.
- **Deep Learning** : architectures CNN-LSTM, analyse audio, classification multi-classes.
- **Computer Vision** : YOLOv8, détection d'objets, suivi vidéo, OCR.
- **MLOps** : MLflow, FastAPI, Docker, monitoring, retraining, tests unitaires.
- **Data Apps** : Streamlit, Gradio, dashboards interactifs, visualisation Plotly.
- **APIs & Backend** : FastAPI, Django, SQLite/PostgreSQL, endpoints REST.
- **Data Engineering** : preprocessing, pipelines CSV/Parquet, indexation vectorielle, export de résultats.

---

## Stack Technique

### Langages & Données

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

### Machine Learning & Deep Learning

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-003366?style=flat-square)

### Vision, Audio & NLP

![YOLOv8](https://img.shields.io/badge/YOLOv8-111111?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![PaddleOCR](https://img.shields.io/badge/PaddleOCR-0062B1?style=flat-square)
![Librosa](https://img.shields.io/badge/Librosa-1f77b4?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square)

### Web, API & Déploiement

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square)

---

## Projets

### 1. Mauritanian Licence Plate Detection

Pipeline Streamlit pour la **détection de plaques d'immatriculation mauritaniennes** avec YOLOv8 et l'extraction de texte par PaddleOCR.

**Objectif**
Combiner la détection d'objets et l'OCR afin d'identifier automatiquement les plaques mauritaniennes sur des images, vidéos ou flux caméra.

**Fonctionnalités principales**

- Interface Streamlit multi-pages : accueil, visualisation, détection image, détection vidéo/webcam.
- Détection de plaques avec **YOLOv8**.
- Extraction du texte des plaques avec **PaddleOCR**.
- Tracking des plaques sur vidéo avec rafraîchissement OCR.
- Prétraitement et normalisation du texte détecté.
- Validation par expressions régulières des séries et régions mauritaniennes.
- Export des résultats en CSV pour images et vidéos.
- Mode rapide et mode complet pour adapter les performances au traitement vidéo.

**Stack** : Python, YOLOv8, PaddleOCR, Streamlit, OpenCV.

---

### 2. Application De Détection De Fraude Par Carte De Crédit

Application interactive Streamlit pour détecter les transactions frauduleuses à partir de techniques de machine learning.

**Objectif**
Identifier et analyser les transactions frauduleuses dans des données de cartes de crédit avec plusieurs modèles supervisés et une interface configurable.

**Fonctionnalités principales**

- Page d'accueil avec vue d'ensemble et métriques clés.
- Exploration du dataset et statistiques descriptives.
- Comparaison entre transactions authentiques et frauduleuses.
- Analyse de corrélation interactive.
- Trois modèles disponibles : **Random Forest**, **Régression Logistique**, **SVM**.
- Prétraitement avec **StandardScaler**.
- Gestion du déséquilibre des classes avec **SMOTE**.
- Optimisation des hyperparamètres avec **GridSearchCV**.
- Évaluation avec précision, rappel, F1-score, matrice de confusion et courbe ROC.
- Paramètres interactifs configurables depuis l'interface.

**Stack** : Streamlit, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn, Imbalanced-learn.

---

### 3. Projet MLOps End-To-End Avec Données Réelles

Pipeline MLOps complet pour prédire le prix des maisons à partir du dataset **Ames Housing**.

**Objectif**
Construire une solution couvrant le cycle de vie machine learning : ingestion, preprocessing, entraînement, tracking, déploiement, monitoring et retraining automatique.

**Fonctionnalités principales**

- Ingestion de données réelles depuis CSV.
- Préprocessing des variables numériques et catégorielles avec Scikit-learn.
- Entraînement et sauvegarde du modèle.
- Validation croisée et comparaison de modèles.
- Optimisation des hyperparamètres avec GridSearchCV.
- Tracking local des expériences avec MLflow.
- API de prédiction avec FastAPI.
- Monitoring de performance et détection de data drift.
- Dashboard Streamlit.
- Tests unitaires.
- Conteneurisation Docker.

**Workflow**

1. Validation croisée.
2. Comparaison de modèles.
3. Optimisation avec GridSearchCV.
4. Entraînement et sauvegarde du modèle.
5. Logging des métriques avec MLflow.
6. Évaluation avec MAE, RMSE et R².
7. Monitoring et détection de drift.
8. Visualisation dans un dashboard.

**Stack** : Scikit-learn, Pandas, NumPy, FastAPI, Uvicorn, MLflow, Streamlit, Pytest, Docker.

---

### 4. Détection De Maladies Respiratoires À Partir Des Sons Respiratoires

Système de deep learning pour classifier automatiquement des conditions respiratoires à partir d'enregistrements audio.

**Objectif**
Développer un modèle capable de détecter et classifier différentes pathologies respiratoires à partir de sons respiratoires, avec un accent sur l'asthme.

**Classes détectées**

- Bronchite.
- Pneumonie.
- Asthme.
- Respiration saine.
- BPCO.

**Fonctionnalités principales**

- Analyse exploratoire des données audio.
- Visualisation des formes d'onde, spectrogrammes et MFCC.
- Extraction avancée de caractéristiques audio.
- Augmentation de données pour équilibrer les classes.
- Classification multi-classes.
- Évaluation avec matrices de confusion, courbes ROC et rapports de classification.
- Analyse SHAP pour interpréter les prédictions.
- Application web Gradio déployée sur Hugging Face Spaces.

**Architecture du modèle**

- Convolutions 1D pour l'extraction de caractéristiques fréquentielles.
- Couches LSTM pour capturer les relations temporelles.
- Couches denses pour la classification finale.

**Stack** : TensorFlow/Keras, Librosa, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn, SHAP, Gradio, Hugging Face Spaces.

**Démo** : [Hugging Face Spaces](https://huggingface.co/spaces/daouda-ba/detection_des_maladies_pulmonaire_par_sons)

---

### 5. Surveillance De Modèle D'IA Sur Docker

Système de monitoring pour un modèle XGBoost déployé en conteneur Docker avec Prometheus et Grafana.

**Objectif**
Déployer un modèle IA en production avec une surveillance des performances du modèle et des ressources système en temps réel.

**Architecture multi-services**

1. Application Streamlit pour les prédictions.
2. Exportateur de métriques avec Flask.
3. Prometheus pour la collecte et le stockage des métriques.
4. Grafana pour la visualisation.
5. Node Exporter pour les métriques système au niveau hôte.

**Fonctionnalités principales**

- Déploiement conteneurisé avec Docker Compose.
- Interface Streamlit pour exécuter des prédictions.
- Collecte automatique des métriques via un exportateur Flask.
- Visualisation temps réel sur Grafana.
- Monitoring des performances et des ressources.

**Métriques surveillées**

- Utilisation CPU et mémoire.
- Nombre de prédictions.
- Temps de réponse.
- Répartition des résultats : approuvé ou refusé.
- Performance du modèle XGBoost.

**Stack** : XGBoost, Docker, Docker Compose, Streamlit, Prometheus, Grafana, Flask, Python.

---

### 6. Système IoT De Supervision Environnementale

Système IoT complet pour mesurer, transmettre et visualiser la température et l'humidité en temps réel avec ESP8266, DHT11 et dashboard Django.

**Objectif**
Superviser des données environnementales en temps réel avec alertes email, indicateurs visuels et historique des mesures.

**Architecture**

```text
[DHT11] -> [ESP8266] -> [Wi-Fi] -> [Django API] -> [SQLite DB] -> [Dashboard Web]
                                           |
                                      [Email Alerts]
```

**Couches du système**

1. Capteurs : DHT11 pour température et humidité.
2. Communication : ESP8266 avec Wi-Fi intégré.
3. Application : API Django pour recevoir et traiter les données.
4. Présentation : dashboard web interactif.
5. Notifications : alertes email.

**Fonctionnalités principales**

- Mesure en temps réel toutes les 15 secondes.
- Dashboard responsive et interactif.
- Graphiques dynamiques avec Chart.js.
- Alertes email via Brevo API.
- Indicateurs visuels avec LEDs sur ESP8266.
- Historique complet des mesures.
- API REST pour récupérer les données.

**Composants matériels**

| Composant | Rôle |
| --- | --- |
| ESP8266 NodeMCU | Microcontrôleur Wi-Fi |
| DHT11 | Capteur température et humidité |
| LEDs verte et rouge | Indicateurs d'état |
| Résistances 220Ω | Protection des LEDs |
| Breadboard et fils | Câblage du circuit |

**API**

- `POST /api/recevoir/` : réception des données capteurs.
- `GET /api/data/` : récupération des données historiques.

**Stack** : ESP8266, DHT11, Arduino IDE, Python, Django, SQLite, HTML/CSS/JavaScript, Chart.js, Brevo API.

---

### 7. Books_Project_Streamlit

Application Streamlit interactive pour analyser un catalogue de livres, explorer des données Goodreads et interroger un assistant RAG connecté à Hugging Face.

**Objectif**
Développer une plateforme complète de gestion et d'analyse de livres combinant visualisation de données, exploration interactive et assistant IA générative.

**Pages et fonctionnalités**

- Accueil avec présentation du projet MauriBooks et vue d'ensemble des phases API, data analysis et RAG.
- Dashboard analytique Plotly avec métriques globales du catalogue.
- Analyse des auteurs, des livres populaires, des notes, des évaluations, des années de publication et des langues.
- Explorateur de bibliothèque avec recherche rapide et filtres avancés.
- Affichage des couvertures et liens directs vers Goodreads.
- Assistant RAG basé sur le catalogue.

**Assistant RAG**

- Embeddings avec Sentence Transformers.
- Index vectoriel FAISS.
- Recherche rapide dans le catalogue.
- Génération de réponses via Hugging Face Inference API.
- Réponses contextualisées à partir des données disponibles.

**Stack** : Streamlit, Plotly, Sentence Transformers, FAISS, Hugging Face Inference API, Parquet, CSV, Python logging.

---

### 8. Books Project API

API RESTful construite avec FastAPI pour explorer et gérer une base de données de livres et de données de lecture inspirée de Goodbooks-10k.

**Objectif**
Fournir une API robuste pour gérer des livres, métadonnées, évaluations, tags, listes de lecture et statistiques.

**Fonctionnalités principales**

- Recherche de livres par titre, auteur ou ID.
- Filtrage par année, langue et notation.
- Pagination pour les grandes collections.
- Accès aux métadonnées complètes des livres.
- Accès aux notes utilisateurs par livre.
- Statistiques de notation : moyenne et distribution.
- Historique d'évaluations par utilisateur.
- Gestion et filtrage par tags.
- Exploration de tendances littéraires.
- Récupération de listes "à lire" par utilisateur.
- Exports en JSON, CSV et DataFrame Pandas.
- Documentation automatique avec Swagger UI et ReDoc.

**Performance & sécurité**

- Pagination optimisée avec LIMIT/OFFSET.
- Cache Redis configurable.
- Compression GZIP.
- CORS configuré.
- Logging structuré.
- Gestion centralisée des erreurs.
- Tests unitaires avec Pytest.

**Stack** : FastAPI, Python 3.10+, SQLite, PostgreSQL, SQLAlchemy, Pydantic, Render, Docker, Gunicorn, Pytest.

**Production** : [books-project-api.onrender.com](https://books-project-api.onrender.com/)

**Documentation** : `/docs` et `/redoc`.

---

## Synthèse Des Projets

| Projet | Domaine | Interface / Déploiement | Technologies clés |
| --- | --- | --- | --- |
| Mauritanian Licence Plate Detection | Computer vision, OCR | Streamlit | YOLOv8, PaddleOCR |
| Détection de fraude carte de crédit | Machine learning | Streamlit | Scikit-learn, SMOTE |
| Projet MLOps Ames Housing | MLOps, régression | FastAPI, Streamlit, Docker | MLflow, Pytest |
| Maladies respiratoires par sons | Deep learning audio | Gradio, Hugging Face Spaces | TensorFlow/Keras, Librosa |
| Surveillance modèle IA sur Docker | Monitoring IA | Docker Compose, Grafana | XGBoost, Prometheus |
| Supervision environnementale IoT | IoT, web dashboard | Django | ESP8266, DHT11, Chart.js |
| Books_Project_Streamlit | Data analysis, RAG | Streamlit | Plotly, FAISS, Hugging Face |
| Books Project API | API data | Render | FastAPI, SQLAlchemy |

---

## Contact

Je suis ouvert aux collaborations, projets data/IA, stages, opportunités professionnelles et échanges techniques.

| Canal | Lien |
| --- | --- |
| LinkedIn | [linkedin.com/in/daouda-ba-b9b21b2b4](https://linkedin.com/in/daouda-ba-b9b21b2b4) |
| GitHub | [github.com/Daouda-Ba](https://github.com/Daouda-Ba) |
| Email | [daoudaba4500@gmail.com](mailto:daoudaba4500@gmail.com) |

---

<div align="center">

**Merci de visiter mon portfolio.**

*Dernière mise à jour : septembre 2026*

</div>
