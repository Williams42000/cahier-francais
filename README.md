# 📓 Mon cahier de français

Application web interactive pour apprendre le **français langue seconde** (interface bilingue FR / ES), construite à partir d'un cahier de cours.

➡️ **Démo en ligne :** une fois GitHub Pages activé → `https://williams42000.github.io/cahier-francais/`

## ✨ Fonctionnalités

**Grammaire & conjugaison** (6 modules, 430+ questions avec explications)
- Le présent (1er / 2e groupe, verbes irréguliers)
- L'impératif
- La négation
- Les pronoms (sujet, COD, COI, réfléchi, disjoint)
- Le passé composé (être / avoir + accords)
- Activités : *jouer à / de · faire du*

Chaque module : un onglet **Étudier** (explication du temps + tableaux à code couleur) et un onglet **S'exercer** (quiz de 10, 20 ou toutes les questions, avec une explication après chaque réponse).

**Examen final** 🎓 — un test d'entraînement qui pioche **aléatoirement** dans toute la grammaire et la conjugaison : questions à choix multiple, conjugaisons à taper, et **phrases complètes à former**. Les questions sont différentes à chaque passage, avec une explication après chaque réponse. Trois formats : rapide (10), moyen (20), long (40).

**Tuteur IA** 🤖 — un bouton flottant ouvre un chat avec une IA qui répond **uniquement** sur la grammaire et la conjugaison du français (elle refuse poliment tout le reste). Elle s'adapte à la **section où se trouve l'élève** et explique les règles en français. Propulsé par un agent n8n (OpenAI) ; aucune clé n'est exposée côté navigateur.

**Vocabulaire par thèmes** — 1500 mots les plus courants (100 par thème), classés en 15 contextes
✨ Essentiels · 🍴 Cuisine · ⚽ Sport · 👪 Famille · 🧍 Corps · 👕 Vêtements · 🏠 Maison · 🎨 Couleurs · 🔢 Nombres · 📅 Calendrier · ☀️ Météo · 🐶 Animaux · 🏙️ Ville & transports · ⚡ Verbes courants · 🙂 Adjectifs & émotions

Chaque thème : **Cartes** (flashcards FR → ES), **Liste** (tableau complet) et **Quiz** généré automatiquement dans les deux sens.

## 🛠️ Technique
- Une seule page, **100 % autonome** (HTML + CSS + JavaScript, aucune dépendance, aucun build).
- Progression sauvegardée localement.
- Responsive, accessible (focus clavier, `prefers-reduced-motion`).

## 🚀 Lancer en local
Ouvre simplement `index.html` dans un navigateur.

---
Fait avec ❤️ pour apprendre le français.
