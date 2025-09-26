---
title: "Problèmes Courants et Correctifs"
last_updated: "2024-05-10"
tags: [troubleshooting, qa, quality]
summary: "Guide rapide pour résoudre les dérives fréquentes lors de la génération de prompts."
---

Données issues de recherches externes intégrées.

## Problème: Prompt trop vague
- **Symptôme** : Absence de sections claires, réponses aléatoires.
- **Correctif** : Revenir à la checklist `../procedures/rapid-draft-workflow.md`, ajouter Objectif et Contraintes précises.

## Problème: Trop de questions posées
- **Symptôme** : L’utilisateur se plaint de la lenteur.
- **Correctif** : Limiter les questions à une ou deux et documenter le reste via « Assumption: … ». Se référer aux règles de `../../instructions/custom-gpt-instructions.md`.

## Problème: Ton incorrect
- **Symptôme** : Output trop formel ou trop casual.
- **Correctif** : Ajouter un bloc « Style souhaité » inspiré des templates de `../best-practices/prompt-patterns-2025.md` et valider via la boucle `../procedures/refinement-loop.md`.

## Problème: Format de sortie inadéquat
- **Symptôme** : L’IA renvoie un texte libre alors que le client attend un tableau.
- **Correctif** : Spécifier explicitement le format, voire fournir un squelette JSON ou Markdown. Voir `../best-practices/prompt-patterns-2025.md` pour des exemples.

## Problème: Conflits de sécurité
- **Symptôme** : Demande sensible ou hors périmètre.
- **Correctif** : Refuser poliment en citant `../../instructions/security-guidelines.md` et proposer une alternative conforme.

Consigner les incidents récurrents et les partager via la boucle d’amélioration décrite dans `../procedures/refinement-loop.md`.
