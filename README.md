# HomeCreditScore

#### <i>Création d'un modèle de scoring</i>

## Présentation
La mission principale de ce projet est de prédire le risque de faillite d'un client pour une société de crédit. Pour cela, nous devons configurer un modèle de classification binaire et d'en analyser les différentes métriques.

Ce projet consiste à créer une API web avec un Dashboard interactif. Celui-ci devra a minima contenir les fonctionnalités suivantes :

 - Permettre de visualiser le score et l’interprétation de ce score pour chaque client de façon intelligible pour une personne non experte en data science.
 - Permettre de visualiser des informations descriptives relatives à un client (via un système de filtre).
 - Permettre de comparer les informations descriptives relatives à un client à l’ensemble des clients ou à un groupe de clients similaires.

La partie features engineering n'étant pas la partie la plus importante de ce projet, il nous est proposé d'utiliser un Notebook disponible sur le site de Kaggle, dont le lien est disponible au bas de cette présentation.

## Construction

<u>Dans ce dépôt, vous trouverez :</u>

 - Un dossier avec les Notebook Jupyter pour l'exploration des données, l'entraînement et la configuration du modèle de classification.
 - Un dossier avec la note technique qui explique en détails la construction et les résultats du modèle.
 - Un dossier avec la Le tableau HTML d’analyse de data drift réalisé à partir d’evidently
 - Un dossier avec le dashbord Streamlit et la configuration de l'API.


## Modèle de classification
Le modèle retenu pour cet exercice est le modèle LightGBM.
## Dashboard / API
J'ai utilisé:
 - MLflow pour la création de l'API et Azure Machine Learning Studio pour le déploiment 
 - Streamlit

## Données d'entrées
 - Lien de téléchargement des données d'entrées : https://www.kaggle.com/c/home-credit-default-risk/data 
 - Notebook de départ pour la partie Features Engineering : https://www.kaggle.com/willkoehrsen/start-here-a-gentle-introduction
