# Critère *Bonnes pratiques cryptographiques*

## Objectif

Le code suit-il les bonnes pratiques de base en cryptographie ?

## Actions

- Rechercher l'utilisation de bibliothèques cryptographiques dans le code source.
- Vérifier que les algorithmes utilisés sont reconnus et à jour (pas d'algorithmes obsolètes).
- Vérifier que les clés cryptographiques ne sont pas codées en dur dans le code source.
- Vérifier que les protocoles cryptographiques utilisés sont conformes aux standards (ex. TLS 1.2+).
- Vérifier la conformité avec les critères openSSF relatifs aux bonnes pratiques cryptographiques.
- Vérifier que la gestion des clés suit les bonnes pratiques (rotation, stockage sécurisé).

## Notation
Note entre 0 et 20 :
- 0 : aucune pratique cryptographique identifiée ou pratiques obsolètes.
- +5 : bibliothèques cryptographiques reconnues et à jour utilisées.
- +5 : algorithmes cryptographiques conformes aux standards actuels.
- +5 : clés cryptographiques gérées de manière sécurisée.
- +5 : conformité avec les critères openSSF de bonnes pratiques cryptographiques.