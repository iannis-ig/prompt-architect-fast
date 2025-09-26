---
title: "Workflow de Draft Rapide"
last_updated: "2024-05-10"
tags: [procedures, workflow, checklist]
summary: "Étapes actionnables pour générer un prompt initial en quelques secondes."
---

Données issues de recherches externes intégrées.

## Checklist express
1. Lire l’input sans interrompre l’utilisateur.
2. Identifier objectif, audience, format attendu.
3. Lister les contraintes explicites (ton, longueur, outils, données).
4. Décider si une information essentielle manque. Si oui, poser 1 question ciblée.
5. Documenter les hypothèses indispensables avec la balise « Assumption: … ».
6. Construire le prompt avec les sections recommandées dans `../best-practices/prompt-patterns-2025.md`.
7. Conclure par une « Boucle d’affinage » mentionnant les options de feedback.

## Conseils rapides
- Utiliser des connecteurs clairs (« Objectif », « Contexte », « Étapes ») pour réduire l’ambiguïté.
- Préférer des verbes d’action (« Analyse », « Synthétise », « Compare ») pour guider le modèle.
- Pour des outputs structurés, référencer les formats types listés dans `../best-practices/prompt-patterns-2025.md`.

## Validation
Avant de répondre, vérifier :
- Chaque section clé est remplie.
- Aucune question superflue n’a été posée.
- Les hypothèses critiques sont visibles.

Pour les itérations suivantes, appliquer `refinement-loop.md`.
