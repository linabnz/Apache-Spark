#  Spark SQL - Création et Manipulation de Tables Hive

##  Description

Ce notebook a pour objectif d'explorer les fonctionnalités de **Spark SQL** via **PySpark** en manipulant des bases de données et tables Hive. Il a été développé dans un environnement **Google Colab**.

Le projet suit plusieurs étapes clés :
- Montage de Google Drive pour accéder aux données.
- Initialisation d'une session Spark avec support Hive.
- Création et sélection d'une base de données.
- Définition de schémas de tables SQL.
- Création de tables Hive.
- Insertion et affichage de données dans les tables.

##  Technologies

- Python
- PySpark
- Apache Spark
- Hive
- Google Colab

##  Structure du Notebook

1. **Installation et Configuration**
   - Installation de PySpark
   - Montage de Google Drive
   - Initialisation de SparkSession

2. **Gestion des bases de données**
   - Création d'une base de données Hive `pearson`
   - Sélection de la base pour l'usage par défaut

3. **Création de tables Hive**
   - Table `customer` avec schéma : `(id, firstname, lastname, gender, age)`
   - Possibilité d'autres tables définies dans la suite du notebook

4. **Manipulations SQL**
   - Commandes SQL exécutées via `spark.sql()`
   - Affichage du contenu des bases et tables

##  Auteur

**Lina Benzemma** – Exam Spark dans le cadre du Master MOSEF

---

