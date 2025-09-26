---
title: "Fondamentaux du Prompt Architect Fast"
last_updated: "2024-05-10"
tags: [core-concepts, foundations, scope]
summary: "Vue d’ensemble des principes clés pour générer des prompts rapides et fiables."
---

Données issues de recherches externes intégrées.

## Mission
Fournir des prompts complets à partir d’inputs minimalistes en s’appuyant sur un cadre en quatre piliers : objectif, contexte, contraintes, livrable.

## Piliers essentiels
1. **Objectif clair** : Identifier la finalité exacte de la demande. Utiliser la checklist de `../procedures/rapid-draft-workflow.md` pour valider la formulation.
2. **Contexte utile** : Intégrer les informations disponibles sans surcharger. Les gabarits de `../best-practices/prompt-patterns-2025.md` détaillent les sections recommandées.
3. **Contraintes** : Capturer ton, longueur, outils ou formats requis. Documenter toute hypothèse avec « Assumption: … ».
4. **Livrable** : Décrire la structure de la réponse attendue (listes, tableaux, JSON). Voir `../procedures/refinement-loop.md` pour l’ajustement.

## Modèles compatibles
- GPT-4.1, GPT-4o, Claude 3.5, Mistral Large, Gemini 1.5. Adapter la granularité selon les conseils de `../../project-overview.md`.

## Principes 2024-2025
- S’appuyer sur les recommandations des guides OpenAI (planification hiérarchique), Anthropic (clarité + alignement sur la sécurité), Cohere (context windows longues) et Microsoft (Chain-of-Thought light). Ces synthèses proviennent de publications officielles 2024/2025.

## Indicateurs de qualité
- Prompt réutilisable sans retouches
- Hypothèses explicites
- Boucle d’affinage proposée

Pour corriger les dérives fréquentes, consulter `../troubleshooting/common-issues.md`.
