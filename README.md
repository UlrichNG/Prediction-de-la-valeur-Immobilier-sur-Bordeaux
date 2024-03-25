# Modélisation et Prédiction des Valeurs Foncières

Ce code Python effectue le scraping des données de valeurs foncières à partir du site data.gouv.fr, puis il prépare les données, construit un modèle de prédiction des valeurs foncières à l'aide de TensorFlow/Keras, et évalue les performances du modèle.


## Explication du Code

Le code est divisé en plusieurs sections :

- **Scraping des données** : Cette partie du code utilise BeautifulSoup pour extraire les données de valeurs foncières à partir de la page data.gouv.fr.

- **Traitement et Nettoyage des Données** : Le code effectue diverses étapes de nettoyage et de transformation des données, telles que la suppression des colonnes inutiles, le traitement des valeurs manquantes et la conversion des types de données.

- **Modélisation et Prédiction** : Il construit un modèle de prédiction des valeurs foncières à l'aide de TensorFlow/Keras, en divisant les données en ensembles d'entraînement, de validation et de test, et en prétraitant les données avant de les utiliser pour l'entraînement du modèle.

- **Analyse des Résultats** : Le code évalue les performances du modèle sur l'ensemble de test et affiche les résultats, tels que la perte (loss) et l'erreur absolue moyenne (MAE), ainsi qu'un graphique comparant les valeurs réelles et les prédictions.

## Exécution

Pour exécuter le code, assurez-vous d'avoir les dépendances requises installées, puis exécutez le script Python.

## Résultats

Le code génère un modèle de prédiction des valeurs foncières et évalue ses performances sur l'ensemble de test. Les résultats peuvent être consultés dans les sorties produites par le code ou dans les graphiques générés.

## Conclusion

Ce code constitue un pipeline complet pour la modélisation et la prédiction des valeurs foncières à partir de données de biens immobiliers. Il peut être utilisé comme référence pour créer des modèles de prédiction similaires dans d'autres contextes.
