# Critère *Tests d'intégration en continue*

## Objectif

Les tests sont-ils exécutés automatiquement lors de chaque contribution ?

## Actions

- Rechercher un fichier de configuration d'intégration continue (ex. .github/workflows, .gitlab-ci.yml, Jenkinsfile).
- Vérifier que les tests font partie du pipeline d'intégration continue.
- Vérifier que le pipeline est déclenché à chaque Pull Request ou Push.
- Analyser les résultats des exécutions récentes du pipeline pour constater leur succès.
- Vérifier que les retours d'erreur sont visibles et exploitables par les contributeurs.

## Notation
Note entre 0 et 20 :
- 0 : aucune intégration continue configurée.
- +5 : pipeline d'intégration continue présent.
- +5 : les tests sont inclus dans le pipeline.
- +5 : le pipeline est déclenché à chaque contribution.
- +5 : les résultats sont visibles et les erreurs exploitables.