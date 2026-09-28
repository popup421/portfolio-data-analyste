# Pipeline analytique avec dbt et Snowflake

**dbt · Snowflake · SQL · staging · marts**

## Contexte

Un environnement analytique devient difficile à maintenir lorsque les transformations SQL sont dispersées et peu documentées.

## Problématique

Comment organiser les transformations pour obtenir des données analytiques structurées, testables et maintenables ?

## Architecture

```text
Sources
   ↓
Staging
   ↓
Intermediate
   ↓
Marts
   ↓
BI / Analyse
```

## Démarche

- définition des sources ;
- création des modèles staging ;
- transformations SQL ;
- organisation des marts ;
- tests de données ;
- documentation.

## Résultats

Le projet met en place une structure reproductible séparant les données proches de la source des données destinées à l'analyse.

## Compétences mobilisées

`dbt` `Snowflake` `SQL` `Data modelling` `Tests`


[← Retour au portfolio](../index.md)
