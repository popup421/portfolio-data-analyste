# Migration et qualité des flux de données

**Mapping · SQL · Data Quality · flux**

## Contexte

Une migration de données nécessite de vérifier que les données sources correspondent correctement au modèle cible.

## Problématique

Comment sécuriser une migration en identifiant les écarts de mapping, les données manquantes et les incohérences avant la mise en production ?

## Démarche

```text
Source
  ↓
Analyse du modèle
  ↓
Mapping source → cible
  ↓
Transformation
  ↓
Contrôles
  ↓
Pré-production
  ↓
Cible
```

Les contrôles portent notamment sur les clés, cardinalités, valeurs obligatoires, correspondances et règles métier.

## Résultats

Le projet met l'accent sur la traçabilité du passage source → cible et sur la détection des anomalies avant validation.

## Compétences mobilisées

| Domaine | Compétences |
|---|---|
| Flux | Analyse source → cible |
| SQL | Contrôles et rapprochements |
| Data Quality | Règles de validation |
| Projet | Tests et documentation |
| Métier | Traduction des besoins |


[← Retour au portfolio](../index.md)
