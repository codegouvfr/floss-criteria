# Critère *Performances*

## Objectif

Est-ce que le logiciel offre de bonnes performances au chargement et à l'exécution, dans un contexte donné et reproductible ?

## Actions

- Définir un contexte de référence (matériel, volume de données, charge) pour rendre les mesures comparables. 
- Mesurer les performances au chargement :
  - Temps de démarrage. 
  - Temps de chargement des ressources et des données. 
- Mesurer les performances à l'exécution :
  - Temps de réponse aux sollicitations. 
  - Débit de traitement (requêtes, opérations par unité de temps). 
  - Latence dans le traitement des données. 
- Vérifier le comportement sous charge croissante (montée en charge, pics de sollicitation). 
- Comparer les performances observées aux besoins attendus dans le contexte de référence. 

## Notation
Note entre 0 et 20 selon la qualité des performances :
- 0 : performances insuffisantes ou non mesurables dans un contexte de référence. 
- +5 : temps de chargement rapide par rapport aux attentes. 
- +5 : temps de réponse et latence faibles à l'exécution par rapport aux attentes. 
- +5 : débit de traitement suffisant pour le volume attendu. 
- +2 : bon comportement sous charge croissante. 
- +3 : bon comportement sous pics. 