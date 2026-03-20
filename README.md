# FastLearn

**Apprends vite, ce que tu veux !**

FastLearn est une application web d'apprentissage des langues (espagnol et anglais) qui génère des exercices personnalisés grâce à l'IA Claude. L'app fonctionne entièrement dans le navigateur, sans backend — toute la progression est sauvegardée localement.

## Fonctionnalités

- **Exercices personnalisés** — Décris un thème (commander au restaurant, à l'aéroport…) et l'IA génère un deck de 10 exercices adaptés à ton niveau
- **5 types d'exercices** — Vocabulaire (flashcards), ordre des mots, traduction, conjugaison, texte à trous
- **Progression par niveaux** — A1 → C1 (espagnol), A1 → C2+ (anglais), avec examens blancs et finaux pour débloquer le niveau suivant
- **Conversation avec l'IA** — Dialogue en situation réelle avec correction automatique des erreurs
- **Répétition espacée (SRS)** — Algorithme SM-2 pour réviser les mots au bon moment
- **Glossaire** — Sauvegarde et consulte les mots appris, avec conjugaisons et exemples
- **Suivi quotidien** — Objectif journalier de 20 XP, streak de jours consécutifs, badges

## Stack technique

| | |
|---|---|
| **Frontend** | HTML, CSS, JavaScript vanilla (fichier unique, aucun framework) |
| **IA** | API Anthropic — Claude Haiku 4.5 |
| **Stockage** | localStorage (progression par langue + streak global) |
| **Hébergement** | GitHub Pages |

## Utilisation

1. Ouvre [neyler0.github.io/FastLearn](https://neyler0.github.io/FastLearn)
2. Entre ta clé API Anthropic dans le champ prévu
3. Choisis ta langue (ES / EN)
4. Décris une situation ou un thème, puis clique sur **Générer**

> La clé API est stockée uniquement dans ton navigateur et n'est jamais envoyée ailleurs qu'à l'API Anthropic.

## Structure du projet

```
FastLearn/
└── index.html    ← Application complète (HTML + CSS + JS)
```

## Développement

Aucun build nécessaire. Ouvre `index.html` dans un navigateur ou lance un serveur local :

```bash
npx serve .
```

## Auteur

Aurélien Boré — 2025

## Licence

Projet personnel. Tous droits réservés.
