# Critère *Distributions sécurisées*

## Objectif

La livraison du code est-elle sécurisée contre les attaques de type man-in-the-middle ?

## Actions

- Vérifier que les livraisons sont signées numériquement.
- Vérifier que les transferts utilisent des protocoles sécurisés (HTTPS, SSH).
- Vérifier la présence de checksums ou de signatures pour les artefacts de build.
- Vérifier que les packages publiés sont signés (ex. GPG, sigstore).

## Notation
Note entre 0 et 15 :
- 0 : aucune mesure de sécurité des distributions.
- +5 : transferts effectués via des protocoles sécurisés.
- +5 : artefacts de build fournis avec des checksums.
- +5 : livraisons signées numériquement.
