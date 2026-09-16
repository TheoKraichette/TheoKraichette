<div align="center">

# Théo Kraichette

**Data &amp; IA Engineer**

*Ingestion → lakehouse → modèle → application.*

</div>

---

## Ce que je construis

Des chaînes de données qui vont jusqu'au bout : collecter des sources ouvertes
hétérogènes, les fiabiliser dans un lakehouse, entraîner le modèle qui répond à la
question métier, et livrer le résultat dans une application qu'on ouvre vraiment.
Conteneurisé, orchestré, et reproductible sur un `docker compose up`.

## Projets

| Projet | Le problème résolu | Stack |
|---|---|---|
| **[ImmoLake](https://github.com/TheoKraichette/ImmoLake)** | Croise les prix de l'immobilier (DVF) et les diagnostics énergétiques (ADEME) pour repérer les biens sous-cotés avant l'interdiction des passoires thermiques. Architecture médaillon, orchestration event-driven. | Airflow 3 · MinIO · DuckDB · Parquet · Streamlit |
| **[ExoLifeAnalyzer](https://github.com/TheoKraichette/ExoLifeAnalyzer)** | Détecte des indicateurs de vie dans un flux de signaux planétaires à 50–100 msg/s. Architecture Lambda HDFS-first, couche batch et couche temps réel réconciliées. | Kafka · Hadoop · Spark · MongoDB |
| **[dog-classifier](https://github.com/Calamia92/dog-classifier)** | Classification de races de chiens : un CNN écrit à la main, puis du transfer learning, comparés sur le même jeu. *(projet d'équipe)* | TensorFlow · Keras · Jupyter |
| **[tp-datalake](https://github.com/TheoKraichette/tp-datalake)** | Stockage objet pour les fichiers, relationnel pour les métadonnées, ingestion orchestrée sans écrire de glue code. | PostgreSQL · MinIO · n8n |

## Stack

**Données** — Airflow · Spark · Kafka · n8n · DuckDB · PostgreSQL · MongoDB · MinIO/S3 · HDFS · Parquet

**Modèles** — PyTorch · TensorFlow/Keras · scikit-learn · CNN · RNN/LSTM · Transformers · YOLO

**Plateforme** — Docker &amp; Compose · Linux · Traefik · GitHub Actions · supervision Zabbix/Grafana

**Applicatif** — Python · TypeScript · PHP · Streamlit · React · React Native

## Avant la data

Du développement applicatif, et ça sert tous les jours : **[WeSkateGo](https://github.com/TheoKraichette/WeSkateGo)**
(React Native, géolocalisation et carte) et **[CheckTricks](https://github.com/TheoKraichette/checktricks)**
(MERN, authentification JWT).

Actuellement en M2 Développement / Data / IA — mémoire sur l'aide à la conception
d'îlots urbains par apprentissage par renforcement sous contrainte réglementaire.
