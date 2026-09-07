# Critère *Dépendances sécurisées*

## Objectif

Les dépendances du projet sont-elles vérifiées et sécurisées avant incorporation ?

## Actions

- Rechercher un fichier de gestion des dépendances (package.json, requirements.txt, pom.xml, Cargo.toml, etc.).
- Vérifier la présence d'outils de vérification des dépendances (ex. Dependabot, Snyk, OWASP Dependency-Check).
- Vérifier que les dépendances sont verrouillées (fichiers de lock) pour garantir la reproductibilité.
- Vérifier que les versions des dépendances sont régulièrement mises à jour.
- Vérifier l'absence de dépendances contenant des vulnérabilités connues.

## Notation
Note entre 0 et 25 :
- 0 : aucune gestion ou vérification des dépendances.
- +5 : fichiers de dépendances présents et gérés.
- +5 : outil de vérification des dépendances configuré.
- +5 : dépendances verrouillées pour la reproductibilité.
- +10 : dépendances régulièrement mises à jour et sans vulnérabilités connues.