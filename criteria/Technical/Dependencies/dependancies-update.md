# Critère *Mise à jour des dépendances*

## Objectif
Est-ce que les dépendances sont à jour et régulièrement mises à jour ?

## Actions
- Pour chaque dépendance directe, comparer la version utilisée avec celle conseillée par les mainteneurs de la dépendance. 
- Déterminer les écarts de date entre les versions utilisées et la dernière disponible et conseillée en production. 
- Déterminer si un mécanisme automatique permet de répérer les mises à jour possibles
- Déterminer si un mécanisme automatique permet de répérer les mises à jour nécessaires
- Déterminer si un mécanisme automatique permet de réaliser automatiquement des mises à jour mineures. 

## Notation
0 : aucune dépendance n'est à jour
+1 : certaines dépendances sont à jour
+3 : toutes les dépendances sont à jour 
+1 : un mécanisme automatique informe des mises à jour possibles
+2 : un mécanisme automatique informe des mises à jour nécessaires
+1 : un mécanisme automatique réalise des mises à jour mineures possibles
