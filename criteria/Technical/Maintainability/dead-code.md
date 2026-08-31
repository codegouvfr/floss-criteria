# Critère *Code mort*

## Objectif

Est-ce que le code contient des parties mortes ?

## Actions

- Mesurer automatiquement la présence de code mort (fonctions, classes, variables ou branches inutilisées). 
- Identifier les dépendances ou modules déclarés mais jamais utilisés. 
- Repérer la présence d'algorithmes ou de traitements jamais sollicités à l'exécution. 
- Évaluer la part de code mort dans le volume total du code. 

## Notation
Note entre 0 et 20 selon l'absence de code mort :
- 0 : forte présence de code mort non détectée ni gérée. 
- +1 : faible part de code mort dans le projet. 