<div align="center">

# Théo Kraichette

**Data &amp; IA Engineer**

*De la donnée brute au modèle qui tourne — ingestion, entraînement, mise en service.*

</div>

---

## IA &amp; modèles

| Projet | Ce qu'il fait | Stack |
|---|---|---|
| **[Noob Sama](https://github.com/Calamia92/Noob_Sama)** | Un agent apprend à jouer à un roguelite dans le navigateur : clonage de comportement à partir de démonstrations, puis DQN, évalués face à une heuristique de référence. Les deux algorithmes sont écrits en NumPy, sans framework de deep learning. Playwright pilote Chromium, chaque essai est consigné.<br><sub>Projet d'équipe — j'ai écrit l'agent, et <a href="https://kraich.itch.io/eclipse-of-souls">le jeu sur lequel il s'entraîne</a>.</sub> | NumPy · DQN · Behavior Cloning · Playwright |
| **[DocuScan AI](https://github.com/PhilLeGoff/hackaton-groupe-12)** | Traitement automatisé de documents administratifs : OCR, classification, extraction d'entités et détection d'anomalies structurelles (Luhn, SIREN, clé RIB, TVA), orchestrés en DAG Airflow au-dessus d'un lac HDFS à trois zones.<br><sub>Hackathon à 7 — modules IA, API, orchestration et frontend.</sub> | Tesseract · spaCy · TF-IDF/SVM · XLM-RoBERTa · Airflow · FastAPI · HDFS |
| **[CinePoster Insight](https://github.com/Calamia92/CinePoster-AI)** | Prédiction des genres d'un film à partir de sa seule affiche, en multi-label — avec Grad-CAM pour montrer *où* le modèle a regardé pour décider.<br><sub>Projet d'équipe.</sub> | MobileNetV2 · TensorFlow · Grad-CAM · Streamlit |
| **[dog-classifier](https://github.com/Calamia92/dog-classifier)** | Classification de races de chiens : un CNN écrit à la main, puis du transfer learning, comparés sur le même jeu de données.<br><sub>Projet d'équipe.</sub> | TensorFlow · Keras · Jupyter |

## Données &amp; plateforme

| Projet | Ce qu'il fait | Stack |
|---|---|---|
| **[ImmoLake](https://github.com/TheoKraichette/ImmoLake)** | Croise les prix de l'immobilier (DVF) et les diagnostics énergétiques (ADEME) pour repérer les biens sous-cotés avant l'interdiction des passoires thermiques. Architecture médaillon, orchestration event-driven. | Airflow 3 · MinIO · DuckDB · Parquet · Streamlit |
| **[ExoLifeAnalyzer](https://github.com/TheoKraichette/ExoLifeAnalyzer)** | Détecte des indicateurs de vie dans un flux de signaux planétaires à 50–100 msg/s. Architecture Lambda HDFS-first, couches batch et temps réel réconciliées. | Kafka · Hadoop · Spark · MongoDB |
| **[CrimeScope NYC](https://github.com/Calamia92/CrimeScope-NYC)** | Analyse et prévision des plaintes du NYPD : ingestion Socrata, entrepôt ClickHouse, indexation géospatiale H3, prévisions hebdomadaires par le modèle de fondation Chronos-2.<br><sub>Projet d'équipe.</sub> | ClickHouse · Chronos-2 · H3 · SvelteKit · Bun · FastAPI |
| **[tp-datalake](https://github.com/TheoKraichette/tp-datalake)** | Stockage objet pour les fichiers, relationnel pour les métadonnées, ingestion orchestrée sans écrire de glue code. | PostgreSQL · MinIO · n8n |

## Stack

**Modèles** — NumPy · PyTorch · TensorFlow/Keras · scikit-learn · XGBoost · CNN · RNN/LSTM · Transformers · apprentissage par renforcement · YOLO

**Données** — Airflow · Spark · Kafka · n8n · DuckDB · ClickHouse · PostgreSQL · MongoDB · MinIO/S3 · HDFS · Parquet

**Plateforme** — Docker &amp; Compose · Linux · Traefik · GitHub Actions · supervision Zabbix/Grafana

**Applicatif** — Python · TypeScript · PHP · FastAPI · Streamlit · React · React Native

## Avant la data

Du développement applicatif, et ça sert tous les jours pour livrer un modèle
autrement qu'en notebook : **[WeSkateGo](https://github.com/TheoKraichette/WeSkateGo)**
(React Native, géolocalisation et carte) et
**[CheckTricks](https://github.com/TheoKraichette/checktricks)** (MERN, authentification JWT).

Actuellement en M2 Développement / Data / IA — mémoire sur l'aide à la conception
d'îlots urbains par un agent d'apprentissage par renforcement contraint par la
réglementation d'urbanisme.
