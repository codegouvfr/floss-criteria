# Critère *Tests de déploiement en continue*

## Objectif

Les tests sont-ils exécutés automatiquement lors de chaque déploiement ?

## Actions

- Rechercher un fichier de configuration de déploiement continu (ex. .github/workflows, .gitlab-ci.yml, Jenkinsfile).
- Vérifier que les tests font partie du pipeline de déploiement continu.
- Vérifier que le déploiement ne s'effectue qu'après le succès des tests.
- Analyser les résultats des exécutions récentes du pipeline de déploiement.
- Vérifier la présence d'un mécanisme de révision des résultats avant validation du déploiement.

## Notation
Note entre 0 et 20 :
- 0 : aucun déploiement continu configuré.
- +5 : pipeline de déploiement continu présent.
- +5 : les tests sont inclus dans le pipeline de déploiement.
- +5 : le déploiement n'a lieu qu'après succès des tests.
- +5 : les résultats sont auditablement tracés et révisables.