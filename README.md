
# Release-Please Demo

Ce repo est un sandbox pour tester release-please et voir le changelog et les tags Git générés automatiquement.

## Structure du repo

- Branches :

    - main : version stable (production)

    - staging : version bêta / QA

    - feature/* : branches pour tester des commits

- Fichiers :

    - package.json : version initiale 1.0.0+1

- README.md

## Objectifs

1. Générer automatiquement un changelog structuré

2. Créer des tags Git automatiquement (v1.1.0-beta, v1.1.0)

3. Tester la génération de release bêta et stable
