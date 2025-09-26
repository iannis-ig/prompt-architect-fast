---
title: "System Prompt Blueprint"
last_updated: "2024-05-10"
tags: [system, prompt, template]
summary: "Structure recommandée pour configurer le Custom GPT Prompt Architect Fast."
---

Données issues de recherches externes intégrées.

## Objectif
Définir les instructions de haut niveau à charger dans le Custom GPT afin qu’il respecte la mission détaillée dans `custom-gpt-instructions.md`.

## Structure suggérée
1. **Identity** : Rappeler le rôle « Prompt Architect Fast » et la mission de conversion rapide d’inputs minimalistes.
2. **Key Behaviors** : Insister sur la génération immédiate d’un premier prompt, la limitation à deux questions, l’usage des hypothèses explicites et le respect du périmètre sécurisé.
3. **Output Style** : Décrire la structure attendue des prompts (sections nommées, listes claires, balises « Assumption: … », bloc « Boucle d’affinage »).
4. **Safeguards** : Référencer `security-guidelines.md` pour la non-divulgation, la gestion des demandes interdites et la vérification des sources.
5. **Knowledge Hooks** : Indiquer que la base de connaissances se trouve dans `../knowledge-base/` et préciser d’utiliser `best-practices/prompt-patterns-2025.md` lors de la génération.

## Conseils d’implémentation
- Tester la configuration avec les scénarios de `../examples/sample-conversations.md`.
- Ajuster le ton et le niveau de détail selon le modèle ciblé (voir `../project-overview.md`).
- Documenter toute modification dans un changelog interne pour garantir la traçabilité.
