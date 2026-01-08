# Projet : Nettoyage et Analyse des Ventes d'un Café

## Objectif du projet
Ce projet consiste à nettoyer un dataset brut et "sale" contenant des transactions de ventes dans un café, afin de le transformer en un dataset propre, cohérent et prêt pour des analyses et visualisations.

## Étapes principales réalisées
1. **Exploration des données**  
   Identification des problèmes tels que valeurs manquantes, incohérences et types de données incorrects.  

2. **Nettoyage approfondi**  
   - Conversion des types de données  
   - Correction des erreurs de texte  
   - Gestion des valeurs manquantes  
   - Recalcul des montants  
   - Suppression des doublons et des outliers  

3. **Transformation et analyse**  
   - Extraction de features à partir des dates  
   - Analyse des ventes : top produits, tendances temporelles  

4. **Visualisations**  
   Création de graphiques simples pour mettre en évidence les insights métier.

Le résultat final est un dataset fiable qui permet de répondre à des questions telles que :  
- Quels sont les produits les plus vendus ?  
- Quelles sont les périodes les plus rentables ?  

## Source des données
Le dataset original, intentionnellement "dirty" pour s'entraîner au nettoyage, provient de Kaggle.  

**Lien :** [Cafe Sales Dirty Data for Cleaning Training](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training)  

### Détails du dataset
- **Nom :** Cafe Sales Dirty Data for Cleaning Training  
- **Fichier principal :** CSV avec environ 10 000 transactions  
- **Colonnes :**  
  - Transaction ID  
  - Item  
  - Quantity  
  - Price Per Unit  
  - Total Spent  
  - Payment Method  
  - Location  
  - Transaction Date  

## Structure du projet
- `01_EXPLORATION.ipynb` → Exploration initiale des données  
- `02_CLEANING.ipynb` → Étapes de nettoyage  
- `03_TRANSFORMATION.ipynb` → Transformations, analyses et visualisations  
- **Dataset nettoyé** → Disponible après exécution des notebooks
