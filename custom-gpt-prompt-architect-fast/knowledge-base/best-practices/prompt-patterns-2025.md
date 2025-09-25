---
title: "Prompt Patterns 2025"
last_updated: "2024-05-10"
tags: [best-practices, templates, patterns]
summary: "Gabarits et pratiques 2025 pour accélérer la construction de prompts."
---

Données issues de recherches externes intégrées.

## Principes clés 2025
- **Structuration modulaire** : D’après les guides OpenAI 2024 et Anthropic 2025, diviser le prompt en modules Objectif, Contexte, Contraintes, Livrable.
- **Instructions explicites** : Cohere et Google recommandent d’indiquer le style attendu et la granularité des étapes.
- **Gardiens de sécurité** : Inclure une clause rappelant les limites éthiques lorsque le sujet est sensible.

## Templates rapides
### Analyse de texte
```
Objectif: Analyser [type de contenu] pour identifier [insight principal].
Contexte: [résumé ou source].
Données disponibles: [liste].
Contraintes: Ton [professionnel/critique], longueur [nb mots].
Tâches IA:
1. Résumer les points clés.
2. Extraire [indicateur].
3. Proposer [recommandation].
Format de sortie: Tableau avec colonnes [Titre, Insight, Action].
Boucle d’affinage: Préciser si d’autres axes doivent être étudiés.
```

### Résumé exécutif
```
Objectif: Produire un résumé exécutif de [contenu].
Contexte: [public cible, enjeu].
Contraintes: Maximum [nb] mots, ton [stratégique].
Sections attendues: Situation actuelle, Analyse, Actions recommandées.
Boucle d’affinage: Indiquer si un zoom sur une section est nécessaire.
```

### Génération créative
```
Objectif: Créer un contenu créatif pour [canal].
Audience: [profil].
Contrainte de style: [ex. storytelling énergique].
Inspiration: [références].
Livrable: [nombre] propositions avec structure [accroche, développement, call-to-action].
Boucle d’affinage: Demander des précisions sur le ton ou la longueur.
```

## Bonnes pratiques génériques
- Toujours indiquer la finalité métier du prompt.
- Ajouter des exemples quand c’est pertinent (few-shot) en suivant la guidance de `../resources/external-resources.md`.
- Mentionner comment l’IA doit gérer les informations manquantes (assumptions ou questions).

Pour l’implémentation pas à pas, combiner avec `../procedures/rapid-draft-workflow.md`.
