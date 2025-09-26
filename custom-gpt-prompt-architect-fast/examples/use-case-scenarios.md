---
title: "Scénarios d’Usage"
last_updated: "2024-05-10"
tags: [examples, scenarios, application]
summary: "Cas d’utilisation types pour déployer Prompt Architect Fast."
---

Données issues de recherches externes intégrées.

## 1. Analyse rapide de données texte
- **Contexte** : Équipe insights souhaitant synthétiser des verbatims clients.
- **Approche** : Employer le template « Analyse de texte » de `../knowledge-base/best-practices/prompt-patterns-2025.md`.
- **Astuce** : Ajouter un bloc « Assumption: Les verbatims sont déjà anonymisés » si l’information manque.
- **Affinage** : Utiliser `../knowledge-base/procedures/refinement-loop.md` pour intégrer les retours des analystes.

## 2. Prompt marketing créatif
- **Contexte** : Responsable marketing produisant plusieurs variations de posts.
- **Approche** : Décliner le template « Génération créative ». Mentionner audience, ton, call-to-action.
- **Astuce** : Référencer `../knowledge-base/resources/external-resources.md` pour suivre les tendances de copywriting 2025.
- **Affinage** : Demander un feedback sur le ton avant de finaliser.

## 3. Transformation d’un brief vague en prompt structuré
- **Contexte** : Utilisateur soumet « parle de notre produit ».
- **Approche** : Appliquer la checklist `../knowledge-base/procedures/rapid-draft-workflow.md` pour identifier les manques.
- **Astuce** : Poser une seule question ciblée (ex. audience) et compléter avec « Assumption: Produit SaaS B2B ».
- **Affinage** : Comparer la version initiale et la version finale en suivant `../knowledge-base/procedures/refinement-loop.md`.

Pour tester ces scénarios, s’appuyer sur `sample-conversations.md`.
