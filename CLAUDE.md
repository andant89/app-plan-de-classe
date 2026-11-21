# Plan de classe — consignes pour Claude

Ce projet suit la **méthode projet** (skill « methode-projet ») en **version allégée** : je suis le Product Owner, Claude conçoit, code, pousse et corrige. Tout se fait en français, en mots simples.

**Décision du PO (2026-11-21)** : c'est un petit outil. Pas de cadrage complet, pas de cahier des charges, pas d'issues ni de user stories. Les retours de la maîtresse sont corrigés directement dans le code ; chaque livraison est décrite au PO en quelques lignes (ce qui change, quoi tester). Les documents de `docs/` restent comme modèles, à utiliser seulement si le PO le demande.

## Le projet

- **Ce que c'est** : une app web gratuite pour aider la maîtresse de 1P-2P de notre fils à répartir ses élèves aux tables (4 places par table), en tenant compte du degré, du besoin d'attention, des paires à séparer et des voisins des plans précédents.
- **Techno** : une seule page HTML autonome (HTML, CSS et JavaScript sans framework ni serveur), dans `index.html`. Données dans le `localStorage` du navigateur, avec sauvegarde par copier-coller.
- **Version en cours** : prototype envoyé à la maîtresse le 2026-11-21, en attente de ses retours.
- **App en ligne (GitHub Pages, branche `main`)** : https://andant89.github.io/app-plan-de-classe/ — mise à jour automatique 1 à 2 minutes après chaque push sur `main`.
- **Prototype Claude** : artifact Claude « Plan de classe » (privé, partageable depuis sa page) — https://claude.ai/artifact/Ht5kJhA6XTzuFjU2dxXxQC

## Où sont les choses

- Cadrage de l'idée : `docs/cadrage.md`. À lire avant de rédiger ou modifier le cahier des charges ; le tableau « Vers le cahier des charges », à la fin, dit quelle partie alimente quelle section.
- Cahier des charges : `docs/cahier-des-charges.md` (copie ; référence : à créer).
- User stories : `docs/user-stories.md` et les issues `type: user story` ; les cases se cochent dans les issues.
- Étiquettes et jalons : `docs/etiquettes.md`.
- Parcours de non-régression : `docs/non-regression.md`.
- Design : pas encore de design system ni de maquettes.

## Séance de brainstorming

Quand je dis « lance une séance de brainstorming » (ou « aide-moi à cadrer mon idée »), ou quand `docs/cadrage.md` est encore vide au démarrage, suivre les consignes de `.claude/skills/brainstorming/SKILL.md` : une question à la fois, toutes les étapes même pour un petit projet, et `docs/cadrage.md` mis à jour après chaque étape.

## Compiler et tester

- Rien à compiler : ouvrir `index.html` dans un navigateur (ordinateur, tablette ou téléphone).
- Tests automatiques : aucun pour l'instant (0 test).
- Le PO teste sur https://andant89.github.io/app-plan-de-classe/ après chaque push sur `main` (recharger la page après 1 à 2 minutes).

## Règles propres à ce projet

- Les prénoms des élèves sont des données d'enfants : elles restent dans le navigateur de l'appareil, jamais envoyées sur un serveur. Pas de vrais prénoms dans le dépôt ni dans les exemples (prénoms inventés uniquement).
- L'utilisatrice finale n'est pas technicienne : textes simples, aucun terme technique à l'écran.
- Tenir à jour ce fichier, le README et le cahier des charges quand une décision du PO les change.
