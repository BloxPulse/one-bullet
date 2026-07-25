# ONE BULLET

> **Une seule balle. Tu la tires. Tu la ramasses. Tu recommences.**

[![JOUER EN LIGNE](https://img.shields.io/badge/JOUER-GitHub_Pages-ffc233?style=for-the-badge)](https://TONPSEUDO.github.io/one-bullet/)
![HTML5 Canvas](https://img.shields.io/badge/HTML5-Canvas-3fe3ff?style=for-the-badge)
![1 fichier](https://img.shields.io/badge/1_FICHIER-0_DEPENDANCE-ff3ec8?style=for-the-badge)
![Licence MIT](https://img.shields.io/badge/LICENCE-MIT-8f97bd?style=for-the-badge)

<!-- TODO: ajouter un GIF de gameplay de 5-10 s ici — boucle parfaite, ça vend le jeu instantanément -->

## Le concept

Un shooter d'arène en vue du dessus avec une contrainte radicale : **tu n'as qu'une seule balle**.

- 🔫 **Tire** — la balle transperce les ennemis et ricoche sur les murs
- 🧲 **Ramasse** — une fois à terre, c'est à toi d'aller la chercher… au milieu de la horde
- ⚡ **Dash** — esquive avec un bref instant d'invincibilité
- 🔥 **Combo** — chaque élimination rapprochée multiplie ton score

Plus la balle traverse d'ennemis, plus tu marques. Mais chaque tir te laisse vulnérable.

## Jouer

👉 **[Version en ligne](https://TONPSEUDO.github.io/one-bullet/)**

Ou en local : clone le repo et ouvre `index.html` dans ton navigateur. C'est tout — aucune dépendance, aucun build.

## Contrôles

| Touche | Action |
|---|---|
| `Z Q S D` / `W A S D` / flèches | Se déplacer |
| Souris | Viser |
| Clic gauche | Tirer |
| `Espace` | Dash |
| `P` / `Échap` | Pause |

## Les ennemis

| Ennemi | Comportement |
|---|---|
| 🔺 Traqueur | Te poursuit sans relâche |
| 🟪 Brute | Lente, encaisse 3 coups |
| 🔸 Fonceur | Charge après une courte télégraphie |

## Technique

- **1 fichier HTML**, aucune dépendance (Google Fonts uniquement)
- Canvas 2D + sons synthétisés en WebAudio — zéro asset externe
- Résolution logique 960 × 600, mise à l'échelle auto, compatible HiDPI
- Record sauvegardé en `localStorage`

## Licence

MIT — libre d'étude, de modification et de redistribution.

---

**ONE BULLET** · prototype Nº1 · 25.07.2026
