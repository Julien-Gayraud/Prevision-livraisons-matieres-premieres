## 1. Contexte

Projet réalisé à **NTNU** dans le cadre d’un travail de groupe avec **Yannick Rudolf** et **Théo Choné** en Machine Learning.  

Le projet s’inscrit dans une mission proposée autour d’un cas réel industriel impliquant **Append Consulting** et **Hydro ASA**, entreprise norvégienne spécialisée dans l’énergie, l’aluminium et le recyclage. L’objectif était de développer un modèle de prévision des livraisons de matières premières destiné à être intégré dans un outil d’optimisation logistique. 

---

## 2. Présentation du projet

L’objectif principal est de prédire, pour chaque matière première (`rm_id`), le **poids cumulé des livraisons entrantes** entre le 1er janvier 2025 et une date cible donnée.

Le défi consistait à produire des prévisions **précises mais conservatrices**, car une surestimation des ressources disponibles peut perturber la planification industrielle.

Plusieurs approches de prévision ont été testées et comparées, notamment :

- modèles de séries temporelles,
- modèles de Machine Learning,
- méthodes de boosting,
- approches statistiques classiques.

Les notebooks du projet présentent différents modèles tels que **Holt-Winters**, **SARIMA**, **Random Forest**, **XGBoost**, ainsi que d’autres expérimentations.

---

## 3. Présentation des fichiers

- **Task-Description.pdf**  
  Description officielle du problème, des objectifs métier et de la métrique d’évaluation.

- **Dataset_definitions_and_explanation.pdf**  
  Documentation détaillée des tables de données utilisées (`receivals`, `purchase_orders`, etc.).

- **Prediction-TS_Holt_Winters.ipynb**  
  Prévisions basées sur la méthode Holt-Winters.

- **Prediction-SARIMA.ipynb**  
  Prévisions avec modèle SARIMA.

- **Prediction-RandomForest.ipynb**  
  Modélisation par Random Forest.

- **Prediction_XGBoost.ipynb**  
  Modélisation par XGBoost.

- **Exemple-Fichier-Prediction.csv**  
  Exemple du format attendu pour les prédictions finales.
