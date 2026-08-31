# Critère *Architecture du code*

## Objectif

Est-ce que l'architecture logicielle du projet est favorable à son évolution ?

## Actions

- Identifier l'architecture logicielle retenue (monolithique, modulaire, microservices, plugin, etc.).
- Analyser la documentation développeur décrivant l'architecture. 
- Vérifier la cohérence entre l'architecture décrite en documentation et l'architecture réellement implémentée. 
- Évaluer le niveau de modularité du code :
  - Découpage en modules ou composants aux responsabilités claires.
  - Couplage faible et cohésion forte entre modules.
  - Séparation des préoccupations (par exemple données / logique métier / présentation).
- Identifier les parties complexes de l'architecture :
  - Volumes de code important par module ou composant.
  - Nombre élevé de dépendances internes entre modules.
  - Présence de couplages circulaires ou de dépendances inattendues.
  - Absence de frontières nettes entre les modules.
- Étudier la possibilité d'ajouter, de supprimer ou de remplacer un module sans impact sur le reste du projet.

## Notation
Note entre 0 et 20 :
- 0 : architecture non identifiable ou non documentée. 
- +5 : architecture identifiée et documentée. 
- +5 : architecture modulaire, aux responsabilités claires. 
- +5 : faible couplage et forte cohésion entre les modules. 
- +5 : insertion de nouvelles fonctionnalités sans impact sur le reste du projet. 