# Projet 5 — DATAImmo : modélisation et analyse SQL du marché immobilier


**Contexte :** Pour une agence immobilière, centraliser 3 sources hétérogènes (DVF, INSEE démographie, référentiel géographique) dans une base relationnelle normalisée, pour analyser le marché immobilier français.

**Problématique :** Comment structurer et interroger des données transactionnelles + démographiques + géographiques hétérogènes pour produire des indicateurs de marché (volumes, prix au m², typologie) fiables et gouvernés (RGPD, sauvegarde) ?

**Mots-clés :** modélisation relationnelle · schéma normalisé · dictionnaire de données · SQLite · jointures multi-tables · CTE (WITH ... AS (...) )· fonctions fenêtrées (ROW_NUMBER) · agrégation SQL · RGPD · stratégie de sauvegarde · Open Data / Etalab

**Compétences mobilisées :**

| Domaine                 | Compétence                                                                                                   |
|-------------------------|--------------------------------------------------------------------------------------------------------------|
| Modélisation de données | Conception d'un schéma relationnel normalisé (clés primaires/étrangères) à partir de sources hétérogènes     |
| Documentation           | Rédaction d'un dictionnaire de données                                                                       |
| SQL                     | Jointures multi-tables, sous-requêtes corrélées, CTE (WITH), fonctions fenêtrées (ROW_NUMBER OVER PARTITION) |
| SQL                     | Agrégations (COUNT, AVG, ratios, taux d'évolution trimestriel), calculs dérivés (prix au m²)                 |
| Gouvernance des données | Analyse de conformité RGPD (licéité, minimisation, anonymisation par agrégation)                             |
| Gouvernance des données | Définition d'une stratégie de sauvegarde/restauration (versioning, sauvegardes différentielles)              |
| Gestion de projet       | Formalisation d'un cadrage de mission (mail de mission, POC avant généralisation)                            |

**Outils :** SQLite, SQL, Excel, Power Query

**Livrable :** Schéma relationnel + dictionnaire de données + base SQLite + requêtes SQL documentées

## Illustrations

<table width="100%" style="width:100%;table-layout:fixed;border-collapse:collapse;">
<tr>
<td width="25%" style="width:25%;"></td>
<td width="25%" style="width:25%;"></td>
<td width="25%" style="width:25%;"></td>
<td width="25%" style="width:25%;"></td>
</tr>
</table>

## Document complet

[Portfolio (PDF)](../pdf/portfolio_keyword_v2.pdf)
