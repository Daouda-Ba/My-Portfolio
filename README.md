<div align="center">
  <img src="img/photo.jpg" alt="Daouda Ba" width="140" style="border-radius: 50%;" />

  <h1>Daouda Ba</h1>

  <p>
    <strong>Portfolio Data Science, Intelligence Artificielle & MLOps</strong>
  </p>

  <p>
    Machine Learning · Computer Vision · OCR · Audio Deep Learning · APIs · Monitoring IA · IoT · RAG
  </p>

  <p>
    <a href="https://www.linkedin.com/in/daouda-ba-b9b21b2b4">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://github.com/Daouda-Ba">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <a href="mailto:daoudaba4500@gmail.com">
      <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>
</div>

---

## Aperçu

Ce portfolio regroupe des projets appliqués en **machine learning**, **computer vision**, **traitement audio**, **MLOps**, **API data**, **IoT** et **applications interactives**.
Chaque projet répond à un cas d'usage concret : détecter des plaques, reconnaître des fraudes, surveiller un modèle IA, analyser des sons respiratoires, explorer des livres ou superviser des données environnementales.

Le contenu ci-dessous est volontairement factuel : il décrit les objectifs, fonctionnalités et technologies réellement fournis pour chaque projet.

---

## Sommaire

- [Expertises](#expertises)
- [Stack Technique](#stack-technique)
- [Projets En Bref](#projets-en-bref)
- [Fiches Projets](#fiches-projets)
- [Contact](#contact)

---

## Expertises

| Domaine | Ce que je construis |
| --- | --- |
| **Computer Vision & OCR** | Détection d'objets, reconnaissance de plaques, extraction et validation de texte |
| **Machine Learning** | Classification, régression, comparaison de modèles, optimisation et évaluation |
| **Deep Learning Audio** | Extraction de caractéristiques, MFCC, classification de sons respiratoires |
| **MLOps & Monitoring** | Pipelines end-to-end, tracking MLflow, FastAPI, Docker, Prometheus, Grafana |
| **Applications Data** | Interfaces Streamlit et Gradio, dashboards, visualisations interactives |
| **API & Backend** | APIs REST avec FastAPI et Django, documentation Swagger/ReDoc, stockage SQL |
| **RAG & NLP** | Embeddings, indexation vectorielle FAISS, assistant connecté à Hugging Face |
| **IoT** | ESP8266, DHT11, transmission Wi-Fi, dashboard web, alertes email |

---

## Stack Technique

**Langages & données**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Machine learning & deep learning**

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-003366?style=flat-square)

**Vision, audio & NLP**

![YOLOv8](https://img.shields.io/badge/YOLOv8-111111?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![PaddleOCR](https://img.shields.io/badge/PaddleOCR-0062B1?style=flat-square)
![Librosa](https://img.shields.io/badge/Librosa-1f77b4?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square)

**Web, API & déploiement**

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square)

---

## Projets En Bref

| Projet | Domaine | Résultat principal | Technologies clés |
| --- | --- | --- | --- |
| **Mauritanian Licence Plate Detection** | Computer vision, OCR | Pipeline de détection et lecture de plaques mauritaniennes | YOLOv8, PaddleOCR, Streamlit |
| **Détection de fraude carte de crédit** | Machine learning | Application Streamlit de classification de transactions | Scikit-learn, SMOTE, Plotly |
| **MLOps Ames Housing** | MLOps, régression | Pipeline complet de prédiction du prix de maisons | MLflow, FastAPI, Docker |
| **Maladies respiratoires par sons** | Deep learning audio | Classification de sons respiratoires | TensorFlow/Keras, Librosa, Gradio |
| **Surveillance modèle IA sur Docker** | Monitoring IA | Stack de monitoring conteneurisée | XGBoost, Prometheus, Grafana |
| **Supervision environnementale IoT** | IoT, dashboard web | Mesure et visualisation température/humidité | ESP8266, DHT11, Django |
| **Books_Project_Streamlit** | Data analysis, RAG | Dashboard livres avec assistant RAG | Plotly, FAISS, Hugging Face |
| **Books Project API** | API data | API REST pour données de livres | FastAPI, SQLAlchemy, Render |

---

## Fiches Projets

### Mauritanian Licence Plate Detection

Pipeline Streamlit pour la **détection de plaques d'immatriculation mauritaniennes** avec YOLOv8 et l'extraction de texte par PaddleOCR.

| Élément | Description |
| --- | --- |
| **Objectif** | Identifier automatiquement les plaques mauritaniennes sur images, vidéos ou flux caméra. |
| **Interface** | Application Streamlit multi-pages : accueil, visualisation, détection image, détection vidéo/webcam. |
| **Vision** | Détection des plaques avec YOLOv8. |
| **OCR** | Extraction du texte avec PaddleOCR, prétraitement et normalisation. |
| **Validation** | Expressions régulières pour les séries et régions mauritaniennes. |
| **Vidéo** | Tracking intelligent avec rafraîchissement OCR. |
| **Export** | Résultats exportables en CSV pour images et vidéos. |

**Stack** : Python, YOLOv8, PaddleOCR, Streamlit, OpenCV.

---

### Application De Détection De Fraude Par Carte De Crédit

Application interactive Streamlit pour détecter les transactions frauduleuses avec différents algorithmes de machine learning.

| Élément | Description |
| --- | --- |
| **Objectif** | Identifier et analyser les transactions frauduleuses dans des données de cartes de crédit. |
| **Exploration** | Vue d'ensemble du dataset, statistiques descriptives, comparaison authentiques vs frauduleuses. |
| **Visualisation** | Analyse de corrélation interactive et graphiques d'évaluation. |
| **Modèles** | Random Forest, Régression Logistique, SVM. |
| **Prétraitement** | StandardScaler et SMOTE pour gérer le déséquilibre des classes. |
| **Optimisation** | GridSearchCV pour les hyperparamètres. |
| **Évaluation** | Précision, rappel, F1-score, matrice de confusion, courbe ROC. |

**Stack** : Streamlit, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn, Imbalanced-learn.

---

### Projet MLOps End-To-End Avec Données Réelles

Pipeline MLOps complet pour prédire le prix de maisons avec le dataset **Ames Housing**.

| Élément | Description |
| --- | --- |
| **Objectif** | Couvrir le cycle de vie ML : ingestion, preprocessing, entraînement, tracking, déploiement, monitoring et retraining. |
| **Données** | Ingestion de données réelles depuis CSV. |
| **Préparation** | Preprocessing numérique et catégoriel avec Scikit-learn. |
| **Modélisation** | Validation croisée, comparaison de modèles et optimisation GridSearchCV. |
| **Tracking** | Logging des métriques avec MLflow local. |
| **Déploiement** | API FastAPI pour les prédictions. |
| **Monitoring** | Suivi de performance, détection de drift et dashboard Streamlit. |
| **Qualité** | Tests unitaires et conteneurisation Docker. |

**Métriques suivies** : MAE, RMSE, R².

**Stack** : Scikit-learn, Pandas, NumPy, FastAPI, Uvicorn, MLflow, Streamlit, Pytest, Docker.

---

### Détection De Maladies Respiratoires À Partir Des Sons Respiratoires

Système de deep learning pour classifier automatiquement des conditions respiratoires à partir d'enregistrements audio.

| Élément | Description |
| --- | --- |
| **Objectif** | Détecter et classifier différentes pathologies respiratoires à partir de sons, avec un accent sur l'asthme. |
| **Classes** | Bronchite, pneumonie, asthme, respiration saine, BPCO. |
| **Analyse audio** | Formes d'onde, spectrogrammes, MFCC et autres caractéristiques audio. |
| **Préparation** | Extraction de caractéristiques et augmentation de données. |
| **Modèle** | Architecture hybride CNN-LSTM. |
| **Évaluation** | Matrices de confusion, courbes ROC, rapports de classification. |
| **Interprétabilité** | Analyse SHAP des prédictions. |
| **Déploiement** | Interface Gradio sur Hugging Face Spaces. |

**Stack** : TensorFlow/Keras, Librosa, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn, SHAP, Gradio, Hugging Face Spaces.

**Démo** : [Hugging Face Spaces](https://huggingface.co/spaces/daouda-ba/detection_des_maladies_pulmonaire_par_sons)

---

### Surveillance De Modèle D'IA Sur Docker

Système de monitoring pour un modèle XGBoost déployé en conteneur Docker avec Prometheus et Grafana.

| Élément | Description |
| --- | --- |
| **Objectif** | Déployer un modèle IA avec surveillance des performances et des ressources système. |
| **Application** | Interface Streamlit pour effectuer des prédictions. |
| **Métriques** | Exportateur Flask pour collecter les mesures. |
| **Monitoring** | Prometheus pour la collecte, Grafana pour la visualisation. |
| **Infrastructure** | Docker Compose et Node Exporter. |
| **Suivi** | CPU, mémoire, nombre de prédictions, temps de réponse, répartition approuvé/refusé. |

**Stack** : XGBoost, Docker, Docker Compose, Streamlit, Prometheus, Grafana, Flask, Python.

---

### Système IoT De Supervision Environnementale

Système IoT pour surveiller en temps réel la température et l'humidité avec ESP8266, DHT11 et dashboard Django.

```text
[DHT11] -> [ESP8266] -> [Wi-Fi] -> [Django API] -> [SQLite DB] -> [Dashboard Web]
                                           |
                                      [Email Alerts]
```

| Élément | Description |
| --- | --- |
| **Objectif** | Mesurer, transmettre et visualiser les données environnementales avec alertes email. |
| **Capteurs** | DHT11 pour température et humidité. |
| **Communication** | ESP8266 avec Wi-Fi intégré. |
| **Backend** | API Django et base SQLite. |
| **Dashboard** | Interface web responsive avec graphiques Chart.js. |
| **Alertes** | Notifications email via Brevo API et LEDs d'état sur ESP8266. |
| **Fréquence** | Mesure toutes les 15 secondes. |

**Composants matériels** : ESP8266 NodeMCU, DHT11, LEDs verte/rouge, résistances 220Ω, breadboard et fils.

**API** : `POST /api/recevoir/`, `GET /api/data/`.

**Stack** : ESP8266, DHT11, Arduino IDE, Python, Django, SQLite, HTML/CSS/JavaScript, Chart.js, Brevo API.

---

### Books_Project_Streamlit

Application Streamlit pour analyser un catalogue de livres, explorer des données Goodreads et interroger un assistant RAG connecté à Hugging Face.

| Élément | Description |
| --- | --- |
| **Objectif** | Créer une plateforme de gestion et d'analyse de livres avec visualisation, exploration et IA générative. |
| **Accueil** | Présentation du projet MauriBooks et des phases API, Data Analysis, RAG. |
| **Dashboard** | Métriques globales, auteurs, livres populaires, notes, évaluations, années, langues. |
| **Explorateur** | Recherche rapide, filtres avancés, couvertures et liens Goodreads. |
| **RAG** | Réponses contextualisées à partir du catalogue. |
| **Recherche vectorielle** | Embeddings Sentence Transformers et index FAISS. |
| **Génération** | Hugging Face Inference API. |

**Stack** : Streamlit, Plotly, Sentence Transformers, FAISS, Hugging Face Inference API, Parquet, CSV, Python logging.

---

### Books Project API

API RESTful FastAPI pour explorer et gérer une base de données de livres et de données de lecture inspirée de Goodbooks-10k.

| Élément | Description |
| --- | --- |
| **Objectif** | Fournir une API robuste pour livres, métadonnées, évaluations, tags, listes de lecture et statistiques. |
| **Livres** | Recherche par titre, auteur ou ID ; filtrage par année, langue et notation. |
| **Pagination** | Pagination optimisée pour grandes collections. |
| **Évaluations** | Notes par livre, statistiques de notation, historique par utilisateur. |
| **Tags** | Recherche, filtrage et exploration de tendances littéraires. |
| **Exports** | JSON, CSV et DataFrame Pandas. |
| **Documentation** | Swagger UI et ReDoc générés depuis les modèles Pydantic. |
| **Sécurité & performance** | Cache Redis, compression GZIP, CORS, logging structuré, gestion centralisée des erreurs, tests Pytest. |

**Stack** : FastAPI, Python 3.10+, SQLite, PostgreSQL, SQLAlchemy, Pydantic, Render, Docker, Gunicorn, Pytest.

**Production** : [books-project-api.onrender.com](https://books-project-api.onrender.com/)

**Documentation** : `/docs` et `/redoc`.

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
  <strong>Merci de visiter mon portfolio.</strong>
  <br />
  <sub>Dernière mise à jour : septembre 2026</sub>
</div>
