# Critère *Reprise sur erreur*

## Objectif

Le logiciel permet-il une reprise fiable après une erreur ou un arrêt inattendu ?

## Actions

- Identifier les mécanismes de reprise sur erreur mis en œuvre dans le logiciel.
- Vérifier la présence de sauvegardes automatiques de l'état du logiciel en cours d'exécution.
- Analyser la perte potentielle de données en cas d'arrêt brutal.
- Tester le comportement du logiciel après un plantage forcé.
- Vérifier la présence de journaux d'erreurs exploitables pour diagnostiquer les causes de crash.
- Évaluer la rapidité et la facilité de rétablissement après une erreur.

## Notation
Note entre 0 et 20 :
- 0 : aucun mécanisme de reprise sur erreur.
- +5 : mécanismes de reprise sur erreur présents.
- +5 : sauvegarde automatique de l'état en cours d'exécution.
- +5 : perte minimale de données en cas d'arrêt brutal.
- +2 : journalisation des erreurs.
- +3 : rétablissement rapide.