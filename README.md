<h1 align="center">Cheikh Ahmed Tidiane Ciss</h1>
<h3 align="center">Ingénieur IA & Machine Learning junior — Deep Learning · IA générative · MLOps</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TensorFlow-Keras-FF6F00?logo=tensorflow&logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/LLM-Prompt%20engineering-412991?logo=openai&logoColor=white" alt="LLM">
  <img src="https://img.shields.io/badge/scikit--learn-LightGBM-F7931E?logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/FastAPI-Docker-009688?logo=fastapi&logoColor=white" alt="FastAPI">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/cheikh-ciss-ia">LinkedIn</a> ·
  <a href="mailto:cisscheikhahmedtidiane31@gmail.com">Email</a>
</p>

---

## À propos

Je conçois des solutions d'**intelligence artificielle de bout en bout** : de la compréhension mathématique des modèles jusqu'à leur **mise en production**. Je suis la formation **Intelligence Artificielle d'Orange Digital Center**, et j'applique dans chaque projet les standards d'un environnement professionnel : code modulaire et testé, protocoles d'évaluation rigoureux, résultats reproductibles et documentés.

Ce qui me définit : **je ne m'arrête pas à un bon score**. Je cherche à comprendre d'où il vient, et à prouver qu'il tiendra en conditions réelles.

---

## Compétences

###  Deep Learning et IA générative
- **Frameworks** : TensorFlow, Keras (conception, entraînement, évaluation et sauvegarde de réseaux de neurones).
- **IA générative** : LLM (GPT-4, Mistral, Llama), **prompt engineering** pour l'exploitation de documents, l'analyse de données et la génération de résultats structurés.
- **Données pour le Deep Learning** : pipelines de préparation de jeux de données **images** et **textes**, propres et homogènes, prêts pour l'entraînement.
- **Explicabilité** : SHAP (explications globales et locales, détection d'artefacts dans les données).

###  Fondamentaux mathématiques et optimisation
- **Algèbre linéaire et calcul différentiel** appliqués au Machine Learning (gradients, hessiennes, fonctions de perte).
- **Optimisation** : descente de gradient, méthode de Newton du boosting, régularisation, réglage d'hyperparamètres (recherche aléatoire, validation croisée temporelle).
- **Probabilités et statistiques** : tests non paramétriques (χ², Mann-Whitney), tailles d'effet, correction de Bonferroni, intervalles de confiance par **bootstrap**.
- **Décision sous coût** : choix de seuils par minimisation d'un coût métier, apprentissage sous déséquilibre extrême.

###  Python et génie logiciel
- **Python avancé** : programmation orientée objet, typage, modules réutilisables, interfaces scikit-learn personnalisées.
- **Qualité** : tests automatisés avec **pytest** (plus de 460 tests écrits sur mes projets), code modulaire, documentation.
- **Back-end** : API REST avec **FastAPI**, Pydantic, SQLAlchemy, PostgreSQL, authentification JWT.
- **Collaboration** : Git, historique propre en Conventional Commits, un commit par fonctionnalité.

###  MLOps et mise en production
- **Conteneurisation** : Docker, Docker Compose (application et base de données orchestrées).
- **Reproductibilité** : pipelines d'entraînement en une commande, modèles versionnés avec métadonnées (réglages, seuil, métriques, versions).
- **Base de données en production** : migrations Alembic, données d'initialisation, configuration par variables d'environnement.
- **Démonstration** : applications **Streamlit** pour exposer un modèle à des utilisateurs métier.
- **Robustesse** : évaluation sur un jeu de test isolé, suivi de la dérive des données (PSI), tests de résistance au changement de régime.

###  Autres compétences
- **Data science** : pandas, NumPy, scikit-learn, XGBoost, LightGBM, imbalanced-learn.
- **Visualisation** : Matplotlib, Seaborn, palettes accessibles aux daltoniens.
- **Web** : HTML, CSS, JavaScript.

---

## Projets phares

###  [Détection de fraude Mobile Money](https://github.com/cheikhahmedtidiane/projet_detection_fraude)
Projet de Machine Learning de bout en bout sur 6,3 millions de transactions (0,13 % de fraudes).
- Protocole **temporel** face à des données non stationnaires, tests statistiques des hypothèses.
- LightGBM : **88 % du montant fraudé intercepté** sur des jours jamais vus, coût divisé par 7.
- Seuil choisi par minimisation du **coût métier** ; explicabilité **SHAP**, qui a mis en évidence les artefacts du simulateur.
- Pipeline d'entraînement reproductible, **88 tests**, démo Streamlit et rapport académique.

`Python` `LightGBM` `SHAP` `scikit-learn` `Streamlit` `pytest`

###  [API de gestion d'un atelier de couture](https://github.com/cheikhahmedtidiane/atelier_couture_api)
API REST complète pour un métier réel : clients, mesures, commandes, paiements, livraisons et statistiques.
- **44 routes** documentées (Swagger), authentification **JWT**, mots de passe hachés avec Argon2.
- PostgreSQL 16, SQLAlchemy 2, migrations Alembic.
- **378 tests automatisés** ; lancement complet en une commande avec **Docker Compose**.

`FastAPI` `PostgreSQL` `SQLAlchemy` `Docker` `JWT` `pytest`

###  [AI Workspace](https://github.com/cheikhahmedtidiane/AI-Workspace)
Plateforme web donnant accès à différents services d'intelligence artificielle, avec un tableau de bord de suivi de l'usage des modèles de langage (GPT-4, Mistral, Llama).

`JavaScript` `HTML/CSS` `LLM`

###  [AI Business Assistant](https://github.com/cheikhahmedtidiane/ai-business_assistant)
Prompt engineering appliqué à l'entreprise : exploiter des documents, analyser des données, faire du Machine Learning et produire des résultats structurés à l'aide de LLM.

`LLM` `Prompt engineering` `Jupyter`

---

## Ateliers techniques

| Domaine | Dépôts |
|---|---|
| Deep Learning | [TensorFlow](https://github.com/cheikhahmedtidiane/atelier_tensorflow_iot) |
| Préparation de données | [images](https://github.com/cheikhahmedtidiane/atelier_prepa_donnees_images) · [textes](https://github.com/cheikhahmedtidiane/atelier_prepa_donnees_textuelles) · [données tabulaires](https://github.com/cheikhahmedtidiane/atelier_prepa_donnees_tab) |
| Machine Learning | [scikit-learn](https://github.com/cheikhahmedtidiane/atelier_scikit-learn_iot) |
| Analyse et visualisation | [NumPy](https://github.com/cheikhahmedtidiane/Atelier_Numpy_P1IAODC) · [pandas](https://github.com/cheikhahmedtidiane/atelier_pandas_iot) · [Matplotlib](https://github.com/cheikhahmedtidiane/atelier_matplotlib_iot) · [Seaborn](https://github.com/cheikhahmedtidiane/atelier_seaborn_iot) |

---

## Ma façon de travailler

- **Rigueur** : hypothèses formulées avant l'analyse, jeu de test utilisé une seule fois, résultats vérifiés.
- **Esprit critique** : un score parfait est une question à creuser, pas une victoire.
- **Orientation métier** : je traduis les performances d'un modèle en impact concret (coût, fausses alertes, montant protégé).
- **Qualité** : chaque projet est testé, documenté et reproductible par n'importe qui.

---

## Me contacter

Je suis ouvert aux opportunités en **IA, Machine Learning et Data Science**. N'hésitez pas à me contacter :

<p>
  <a href="https://www.linkedin.com/in/cheikh-ciss-ia"><img src="https://img.shields.io/badge/LinkedIn-Cheikh%20Ahmed%20Tidiane-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:cisscheikhahmedtidiane31@gmail.com"><img src="https://img.shields.io/badge/Email-cisscheikhahmedtidiane31%40gmail.com-EA4335?logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/cheikhahmedtidiane"><img src="https://img.shields.io/badge/GitHub-cheikhahmedtidiane-181717?logo=github" alt="GitHub"></a>
</p>
