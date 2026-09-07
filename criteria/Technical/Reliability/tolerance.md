# Critère *Robustesse du logiciel*

## Objectif

Le logiciel est-il robuste face aux erreurs, à la montée en charge et aux conditions extrêmes ?

## Actions

- Rechercher des tests de tolérance aux fautes dans la suite de tests du projet.
- Vérifier le comportement du logiciel face à des entrées invalides ou inattendues.
- Tester le comportement du logiciel sous montée en charge progressive.
- Vérifier le comportement du logiciel en situation de stress (ressources limitées, charge maximale).
- Analyser la gestion des erreurs et des exceptions dans le code source.
- Vérifier l'absence de crash ou de blocage en conditions dégradées.

## Notation
Note entre 0 et 20 :
- 0 : aucun test de tolérance aux fautes ni vérification de robustesse.
- +5 : gestion des erreurs et des exceptions présente dans le code.
- +5 : tests de tolérance aux fautes ou tests de robustesse disponibles.
- +5 : bon comportement du logiciel sous montée en charge.
- +5 : stabilité maintenue en conditions de stress ou dégradées.