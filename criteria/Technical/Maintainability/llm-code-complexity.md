# Critère *Complexité du code*

## Objectif

Est-ce que le code est complexe à comprendre et à modifier pour un LLM ?

## Actions

- Évaluer la capacité d'un LLM à analyser, corriger ou faire évoluer le code à partir du contexte fourni. 
- Vérifier la présence de la documentation et des données nécessaires au contexte. 

## Notation
Note entre 0 et 20 selon la facilité de manipulation du code par un LLM :
- 0 : code trop complexe ou trop pauvre en contexte pour être traité par un LLM. 
- +5 : code structuré et décomposé en unités de taille raisonnable. 
- +5 : dépendances et imbrications restant limitées et explicites. 
- +5 : usage de noms explicites et de conventions connues. 
- +5 : documentation et contexte suffisants pour analyser et modifier le code. 