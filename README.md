## Data Scientist • Machine Learning Engineer • IA Générative & MLOps
En tant qu’expert en data science, je vous accompagne dans la transformation de vos données en leviers stratégiques. Grâce à l’extraction d’insights pertinents et au développement de modèles intelligents, j’apporte une vision éclairée pour optimiser vos prises de décision. Mon agilité, ma curiosité analytique et mon approche proactive constituent des atouts majeurs pour toute entreprise souhaitant affiner sa stratégie et améliorer l’efficacité de ses processus décisionnels. 
Je privilégie des solutions analytiques performantes, durables et adaptées aux enjeux spécifiques de votre activité.
## Formations
- Machine Learning Enginner
- Master Data Science
- Certificat Data Science

## Compétences clés :
- Machine Learning & Deep Learning
- Scikit-Learn, XGBoost, Random Forest
- NLP (transformers, embeddings), clustering
- Feature engineering & optimisation des modèles
- Évaluation : AUC, F1-Score, confusion matrice

## Expériences
🔹Data Scientist | Covéa | [Dates]
📍 Paris, France.
- Optimisé la tarification MRH en développant un modèle dynamique (Python, SQL), réduisant l’écart-type des primes de 15 %.
- Analysé 10M+ sinistres auto (PySpark, SQL), identifiant des facteurs de risque et réduisant les coûts d’indemnisation de 10 %.
- Renforcé la lutte antifraude en implémentant un modèle IA (Random Forest, Gradient Boosting), améliorant la détection de 30 %.
- Industrialisé le scoring de fraude via AWS Sagemaker, réduisant le temps de détection de 40 %.
- Déployé des dashboards interactifs (Power BI, Tableau), optimisant l’interprétation des insights métiers.

🔹Data Scientist | Ufirst Advisory | [Dates]
📍 Paris, France.
- Optimisé le traitement des données (+50M lignes) avec SQL, Pandas, PySpark, réduisant le temps de préparation de 30 %.
- Exploré et visualisé les données (Matplotlib, Seaborn, Plotly), améliorant l’analyse exploratoire et la prise de décision.
- Amélioré les prévisions de vente de 15 % via des modèles prédictifs avancés (XGBoost, LightGBM, Random Forest).
- Automatisé le déploiement des modèles (Docker, AWS Lambda), réduisant le time-to-production de 40 %.
- Restitué des insights clairs en Power BI, Tableau, Dash, facilitant la prise de décision métier.

🔹 Chargé d'études statistiques | Altocis-P.S.| [Dates]
📍 Paris, France.
- Conçu des dashboards dynamiques (Excel, Power BI), clarifiant les insights pour la direction.
- Automatisé le suivi des KPI, réduisant le temps d’analyse de 30 %.
- Géré 500+ documents comptables (SQL, Excel VBA), assurant une saisie de données précise.
- Fournit des analyses stratégiques, influençant les décisions opérationnelles.
- Optimisé la planification des agents, réduisant les conflits d’horaires de 25 %.

## Projets: 
### Projet 1 : Assistant RH Intelligent basé sur l’IA Générative (RAG).
[Code source GitHub | Demo en ligne](https://github.com/DataEngineer87/Chatbot-Rh-Rag?tab=readme-ov-file)
#### Démo :
![Data Code](/images/photo/CHATBOOT.png)

### Objectif du projet
Les entreprises, disposent des informations RH (télétravail, congés, formation, primes...) sont souvent dispersé dans des fichiers PDF longs et difficiles à consulter.
Ce projet a pour objectif la mise en palce d'un assistant IA capable de :
Comprendre une question RH en langage naturel
Rechercher automatiquement la réponse dans les documents PDF internes
Générer une réponse claire et contextualisée.

### Architecture globale

#### 1 - Ingestion & Indexation :
- Extraction des textes PDF via LangChain
- Découpage intelligent en chunks
- Vectorisation via MiniLM (HuggingFace)
- Stockage dans une base vectorielle FAISS

#### 2 - Moteur RAG :
- Similarity search k=3 dans FAISS
- Construction dynamique du contexte
- Génération de réponse avec GPT ou LLM HuggingFace

#### 3 - Interface utilisateur (Streamlit) :
- Chat propre
- Affichage de la réponse
- Affichage des sources documentaires
- Gestion des erreurs et clé API

#### 4 - Déploiement :
- Version cloud via Streamlit Cloud pour démonstration
- GitHub Actions 
### Solution technique
**J’ai conçu une archiPrédiction du Statut de Compte – MLOps de bout en bouttecture complète basée sur le principe du RAG : Recherche vectorielle (FAISS + Sentence-Transformers)**
- 0% hallucinations grâce à un filtrage strict basé sur la similarité vectorielle
- Gestion multi-PDF pour un référentiel RH complet
- Architecture modulaire : API indépendante de l’UI
- Compatible 100% Open-Source (version HuggingFace)
- Compatible OpenAI pour une qualité premium

### Compétences démontrées
- IA Générative (RAG complet)
- NLP avancé
- Vector Search (FAISS)
- HuggingFace embeddings + LLM
- Streamlit front-end
- Gestion des secrets & configuration streamlit cloud
- Structuration professionnelle de projet IA


## Projet 2 : Prédiction du Statut de Compte Client
- Conception d’un pipeline MLOps complet permettant d’automatiser l’entraînement, le test, le déploiement et le suivi d’un modèle de Machine Learning.
- Le projet combine FastAPI, Docker, GitHub Actions, MLflow, Streamlit Cloud et SHAP pour un cycle de vie ML industrialisé, traçable et explicable.

### Réalisations clés :
- Déploiement **API FastAPI** conteneurisée avec **Docker** et testée automatiquement via **GitHub Actions (CI/CD).**
- Entraînement, suivi et versioning des modèles avec **MLflow.**
- Développement d’une interface utilisateur **Streamlit Cloud** pour des prédictions interactives en ligne.
- Analyse de l’explicabilité du modèle avec **SHAP** et mise en place d’un monitoring des performances.
- Tests unitaires automatisés avec **pytest**, assurant stabilité et qualité du code.

### Stack technique :
- Python, FastAPI, Docker, GitHub Actions, MLflow,
- Streamlit, SHAP, scikit-learn, pandas, pytest

[Code source GitHub | Demo en ligne](https://github.com/DataEngineer87/Statut-Compte-Clients)
#### Démo :
img = Image.open("images/photo/COMPTE_CLIENT_page-0001.jpg")
# Réduire la résolution (par exemple 50%)
new_width = img.width // 2
new_height = img.height // 2
img_resized = img.resize((new_width, new_height), Image.ANTIALIAS)

# Enregistrer l’image compressée
img_resized.save("images/photo/COMPTE_CLIENT_page-0001_small.jpg", optimize=True, quality=70)





### - Modélisation prédictive de la consommation énergétique et des émissions de CO₂ des bâtiments municipaux.
![Data Code](/images/photo/normal.jpg)

### - Segmentation client et analyse comportementale sur un site e-commerce à l’aide de techniques de clustering.
![Data Code](/images/photo/DaImg.jpg)

### - Classification de tags avec des modèles NLP et déploiement du modèle sur le cloud.

### - Reconnaissance d’images par Deep Learning en utilisant des réseaux de neurones convolutifs (CNN).


