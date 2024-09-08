# Prédiction de la rétention de clientèle avec Machine Learning

J'ai réalisé ce projet académique à **ESPRIT** (2020-2021), se concentrant sur l'application de techniques de **Machine Learning** à la problématique de la **rétention de clientèle (Customer Churn)**. L'objectif principal était de **reproduire, comparer et évaluer** plusieurs modèles de prédiction à partir d'articles scientifiques et d'un jeu de données fourni par **IBM**.

## Objectifs
- Identifier les causes de la **résiliation des contrats clients** (churn) dans le secteur des télécommunications.
- **Implémenter et comparer plusieurs modèles** d’apprentissage supervisé et non supervisé.
- Proposer la **meilleure stratégie** pour prédire et réduire le churn des clients.

## Méthodologie
La méthodologie utilisée suit les étapes **CRISP-DM** :
1. **Compréhension du problème métier** : Analyser l'impact du churn dans l'industrie et définir les objectifs.
2. **Compréhension des données** : Utilisation du dataset "**Telco Customer Churn**" d'IBM.
3. **Préparation des données** : Nettoyage, réduction de dimensions et encodage des variables.
4. **Modélisation** : Implémentation de plusieurs algorithmes, notamment **k-NN**, **Random Forest**, **SVM**, et **Réseaux de Neurones Artificiels**.
5. **Évaluation** : Comparaison des modèles à travers différentes métriques comme **l'AUC** et la **précision**.
6. **Déploiement** : Non réalisé dans ce projet.

## Modèles utilisés
- **k-NN** (K-Nearest Neighbors)
- **Random Forest**
- **SVM** (Support Vector Machine)
- **Naïve Bayes**
- **Réseaux de Neurones Artificiels (ANN)**
- **AdaBoost**
- **K-Means** et **CAH** (Clustering Ascendant Hiérarchique) pour l’apprentissage non supervisé

## Résultats
Les modèles **Random Forest** et **SVM** ont obtenu les meilleurs résultats en termes de précision et de prédiction du churn. Le modèle **Naïve Bayes**, associé à une **sélection de caractéristiques séquentielles**, a montré une amélioration significative de la précision. L'approche de clustering **K-Means** a été la plus performante pour l’apprentissage non supervisé.

## Références
Les implémentations sont basées sur trois articles scientifiques :
- **Article A** : Utilisation de la **corrélation de Pearson** et de l’algorithme **K-NN**.
- **Article B** : **Sélection séquentielle de caractéristiques** dans la prédiction du churn avec **Naïve Bayes**.
- **Article C** : **Segmentation** et **détection des fraudes** dans l'industrie des télécommunications.
"""

# Sauvegarder le contenu dans un fichier README.md
file_path = "/mnt/data/README.md"
with open(file_path, "w") as file:
    file.write(readme_content)

file_path
