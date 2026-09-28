# Prototype RAG pour interrogation documentaire

**n8n · Ollama · Qdrant · embeddings**

## Contexte

Les systèmes RAG permettent de rechercher des informations dans un corpus documentaire avant de solliciter un modèle de langage.

## Problématique

Comment construire une chaîne simple permettant d'indexer des documents puis de récupérer les passages pertinents pour répondre à une question ?

## Architecture

```text
Documents
   ↓
Chunking
   ↓
Embeddings
   ↓
Qdrant
   ↓
Recherche vectorielle
   ↓
LLM
   ↓
Réponse
```

## Démarche

- préparation des documents ;
- génération des embeddings ;
- stockage vectoriel ;
- recherche des passages pertinents ;
- génération de la réponse ;
- traçabilité des étapes.

## Résultats

Le prototype permet d'expérimenter une architecture RAG locale et d'observer les différentes étapes du traitement.

## Technologies

`n8n` `Ollama` `Qdrant` `Embeddings` `LLM`


[← Retour au portfolio](../index.md)
