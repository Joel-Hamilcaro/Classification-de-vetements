# Deep Learning : Classification de vêtements

<img src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=flat-square&logo=python&logoColor=white"/><img src="https://img.shields.io/badge/Jupyter%20-%23F37626.svg?&style=flat-square&logo=Jupyter&logoColor=white" /><img src="https://img.shields.io/badge/Keras%20-%23D00000.svg?&style=flat-square&logo=Keras&logoColor=white"/><img src="https://img.shields.io/badge/TensorFlow%20-%23FF6F00.svg?&style=flat-square&logo=TensorFlow&logoColor=white" />
    
*Projet réalisé en binôme dans le cadre du cours "Machine Learning"*   
**Auteurs : [Joël Hamilcaro](https://github.com/Joel-Hamilcaro/) et [Jie Tu](https://github.com/jie-tu)**

### Affichage Web 

- [Jupyter Notebook Viewer](https://nbviewer.org/github/Joel-Hamilcaro/Classification-de-vetements/blob/main/Joel-HAMILCARO_Jie-TU_fashion_mnist.ipynb)   

## Résumé du projet 

L'objectif était de programmer un réseau de neurones artificiel qui, à partir d'une image de vêtement, est capable de prédire à quelle classe appartient ce vêtement (t-shirt, pantalon, robe, ...).

## Plan du notebook 

- Introduction  
- Paramétrage de l'environnement  
- Importation des librairies nécessaires
- Chargement des données
- Exploration des données  
    - Aperçu rapide des données
    - Distribution des données
-  Préparation des données
    - Valeurs manquantes
    - Encodage One-Hot des labels
    - Normalisation des images
    - "Reshaping"

- Notre modèle de départ : "CNN par défaut"
    - Création de l'architecture
    - Création du jeu de validation
    - Entraînement
    - Évaluation du modèle
    - Ajustement manuel des hyperparamètres
    - Recherche automatique d'hyperparamètres
    - Augmentation des données

- Autres architectures
    - Réseau de neurones à propagation avant
    - CNN avec AveragePooling
    - CNN plus profond

- Conclusion  

- Extension : prédictions à partir d'images quelconques
