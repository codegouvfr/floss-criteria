# Critère *Absence de données sensibles*

## Objectif

Le projet est-il exempt de données sensibles dans les dépôts de code versionnés ?

## Actions

- Rechercher la présence de mots de passe, clés d'API ou secrets en dur dans le code source.
- Vérifier l'absence de certificats privés ou de clés privées dans le dépôt.
- Vérifier l'utilisation d'outils de détection de secrets (ex. git-secrets, truffleHog, gitleaks).
- Vérifier la présence d'un fichier .gitignore excluant les fichiers sensibles.
- Vérifier que les variables d'environnement sont utilisées pour les données sensibles.

## Notation
Note entre 0 et 20 :
- 0 : données sensibles détectées dans le code versionné.
- +5 : aucun secret ou donnée sensible trouvé dans le code source.
- +5 : outil de détection de secrets configuré.
- +5 : fichier .gitignore excluant les fichiers sensibles.
- +5 : utilisation des variables d'environnement pour les données sensibles.