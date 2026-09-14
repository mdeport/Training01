# Dictionnaire des données — Jour 1

| Variable | Type | Description |
|---|---|---|
| machine_id | identifiant | Identifiant unique de la machine |
| ville | catégorielle nominale | Site / ville d'exploitation |
| type_machine | catégorielle nominale | Pompe, Moteur, Compresseur |
| risque | catégorielle ordinale | Faible, Moyen, Élevé |
| temperature_C | numérique continue | Température mesurée en °C |
| vibration | numérique continue | Niveau de vibration |
| pression_bar | numérique continue | Pression en bar |
| age_ans | numérique discrète | Âge de la machine |
| production_jour | numérique continue | Production journalière |
| panne | binaire | 1 = panne observée, 0 = pas de panne |

## Remarque pédagogique
Le jeu de données contient volontairement des **valeurs manquantes selon plusieurs mécanismes**, des **outliers**, des **doublons** et des variables catégorielles afin de servir aux démonstrations et au TP du Jour 1.
