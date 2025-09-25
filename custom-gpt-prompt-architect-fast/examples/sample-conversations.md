---
title: "Conversations Exemple"
last_updated: "2024-05-10"
tags: [examples, conversations, onboarding]
summary: "Deux dialogues illustrant la génération rapide de prompts et la boucle d’affinage."
---

Données issues de recherches externes intégrées.

## Exemple 1 – Analyse d’articles de blog
**Utilisateur** : « J’ai besoin d’un prompt pour analyser des articles de blog. »

**Assistant** :
```
Objectif: Analyser des articles de blog pour extraire les tendances clés.
Contexte: Articles fournis par l’utilisateur, langue française.
Assumption: Les articles traitent de marketing digital.
Tâches IA:
1. Résumer les 3 idées majeures par article.
2. Identifier les KPI mentionnés.
3. Recommander des actions marketing basées sur les tendances récurrentes.
Format de sortie: Tableau Markdown avec colonnes Article, Insights, KPI, Action.
Boucle d’affinage: Indiquez si vous souhaitez approfondir un canal spécifique ou ajuster le ton.
```

**Assistant (affinage proposé)** : « Souhaitez-vous un focus particulier (ex. SEO) pour affiner la recommandation ? »

## Exemple 2 – Prompt créatif LinkedIn
**Utilisateur** : « Fais-moi un prompt de style créatif pour LinkedIn. »

**Assistant** : « Pour garantir le bon ton créatif, quel est l’objectif principal de la publication (conversion, notoriété) ? »

**Utilisateur** : « Notoriété. »

**Assistant** :
```
Objectif: Générer un post LinkedIn créatif visant la notoriété de la marque.
Audience: Professionnels marketing B2B.
Assumption: Le produit est une solution SaaS.
Contrainte de style: Ton inspirant, storytelling, 120-150 mots.
Tâches IA:
1. Proposer une accroche percutante liée à un défi du secteur.
2. Développer un récit court montrant la solution.
3. Terminer par un call-to-action orienté engagement.
Format de sortie: Post en 3 paragraphes avec emojis modérés.
Boucle d’affinage: Dites si vous souhaitez un ton plus technique ou ajouter une statistique.
```

Pour d’autres contextes, voir `use-case-scenarios.md` et les templates dans `../knowledge-base/best-practices/prompt-patterns-2025.md`.
