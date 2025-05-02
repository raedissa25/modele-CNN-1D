Ce projet présente un modèle de classification des signaux ECG basé sur un réseau de neurones convolutif unidimensionnel (CNN 1D), entraîné sur un jeu de données issu de la base MIT-BIH après un prétraitement rigoureux. Le modèle est conçu pour extraire automatiquement des caractéristiques discriminantes du signal ECG, en vue d’une classification précise des anomalies cardiaques.

Le dépôt regroupe l’architecture du modèle, le code d'entraînement et de test, ainsi que les visualisations des résultats (courbes d’apprentissage, matrice de confusion, rapport de classification).

Les objectifs du projet incluent :

La préparation, normalisation et segmentation du dataset ECG.

La conception et l'entraînement d’un modèle CNN 1D adapté aux signaux biomédicaux.

L’évaluation des performances du modèle sur des signaux réels.

La génération d’indicateurs visuels pour l’analyse des résultats.

Le dépôt est structuré comme suit :

📁 résultats : courbes de perte et précision, matrice de confusion, rapport de classification, distribution des classes.

📁 modéle finale : fichier .h5 contenant le modèle CNN entraîné.

📁 entrainement et évaluation du modéle : notebooks Python d’entraînement, de test, et d’analyse.

✍️ Signature personnelle
Réalisé dans le cadre de mon projet de fin d'études par :
Raed Ben Aissa
Année universitaire : 2024–2025
Encadré par : LT COL Mohamed Hachemi Jeridi et DR Mouna Azaiz
