---
title: "Project Overview - Prompt Architect Fast"
last_updated: "2024-05-10"
tags: [overview, governance, roadmap]
summary: "Vue d’ensemble du projet, périmètre et maintenance de l’assistant Prompt Architect Fast."
---

Données issues de recherches externes intégrées.

## Portée
Prompt Architect Fast génère des prompts structurés pour divers modèles de langage. Il ne produit pas de code, d’analyses expertes ni de conseils réglementaires. Toute demande hors périmètre doit être déclinée conformément à `instructions/security-guidelines.md`.

## Limites
- Conçu pour inputs textuels courts.
- Hypothèses autorisées uniquement si elles sont signalées (« Assumption: … »).
- Ne remplace pas une validation humaine métier.

## Adaptation aux modèles
| Modèle | Ajustement conseillé |
| --- | --- |
| GPT (4.1, 4o) | Utiliser des sections détaillées et encourager la réflexion pas à pas légère. |
| Claude 3.5 | Favoriser le langage clair, éviter les formulations ambiguës, ajouter une clause de sécurité. |
| Mistral Large | Privilégier les instructions concises, expliciter le format de sortie. |
| Gemini 1.5 | Segmenter les tâches et préciser les limites de données externes. |

Voir `knowledge-base/core-concepts/foundations.md` pour les piliers fondamentaux.

## Maintenance de la base de connaissances
- Planifier une revue bimensuelle des fichiers `knowledge-base/`.
- Alimenter `knowledge-base/resources/external-resources.md` avec les nouveautés après double vérification.
- Synchroniser les templates avec `knowledge-base/best-practices/prompt-patterns-2025.md`.

## Processus d’amélioration
1. Recueillir les retours des utilisateurs (canal support).
2. Documenter les incidents dans `knowledge-base/troubleshooting/common-issues.md`.
3. Mettre à jour les procédures correspondantes.
4. Notifier l’équipe via un changelog interne.

## Vitesse vs qualité
- Appliquer la checklist de `knowledge-base/procedures/rapid-draft-workflow.md` pour rester rapide.
- Utiliser la boucle `knowledge-base/procedures/refinement-loop.md` pour éviter les itérations inutiles.
- Automatiser la surveillance qualité via un échantillon hebdomadaire de conversations.

Pour onboarding rapide, commencer par `instructions/custom-gpt-instructions.md` puis `examples/sample-conversations.md`.
