# Projet d'Analyse Big Data pour le Transport Public en Finlande
 
## Description
 
Ce projet d'analyse Big Data pour le transport public en Finlande a démontré l'impact considérable que peuvent avoir des outils et technologies modernes sur l'amélioration de la gestion et de l'optimisation du transport en temps réel. L'objectif principal de ce projet était d'analyser les données de transport public, de prédire les retards et les accidents, et d'identifier les problèmes de planification tels que des horaires de train et de bus désynchronisés.
 
### Objectifs du projet :
 
- **Collecte des données** : Utilisation de sources telles que Digitransit et des API météorologiques pour collecter les données en temps réel.
- **Analyse descriptive** : Étudier la performance des flottes de transport et identifier les schémas d'utilisation.
- **Analyse prédictive** : Prédire les retards et les accidents grâce à des modèles de machine learning.
- **Analyse graphique** : Détecter des problèmes de planification en analysant les horaires de train et de bus.
 
Le pipeline de stockage des données a été conçu pour garantir une collecte fluide et un stockage optimisé des informations dans **MongoDB**, tandis que le pipeline de prédiction en streaming a permis d'effectuer des analyses en temps réel grâce à **Apache Spark** et **Kafka**. Les résultats des analyses descriptives et prédictives ont montré qu'il est possible d'améliorer la gestion des ressources et de rendre les trajets plus fiables et moins perturbés.
 
## Prérequis
 
- **Apache Kafka** pour la gestion du streaming de données en temps réel.
- **Apache Spark** pour l'analyse des flux de données.
- **MongoDB** pour le stockage des données.
- **Python 3.x** pour exécuter les scripts de traitement.
- **TensorFlow** pour la prédiction via des modèles de machine learning.
- **PySpark** pour l'intégration avec Spark.
 
## Installation
 
### 1. Cloner le projet
 
```bash
git clone https://github.com/sondes98/BigDataProject
cd BigDataProject
