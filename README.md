# Théâtre d'encre

Des expériences de récit interactif faites de **rien que des caractères** — HTML et `<canvas>` purs, aucune dépendance, aucun asset graphique. Tout (décors, personnages, perspective, animation, musique) est généré par le code, à partir de densités de caractères (`· : ░ ▒ ▓ █`) traitées comme des valeurs tonales.

Nées d'une conversation, un soir.

## Voir

Page d'accueil : **[index.html](index.html)** — la galerie de toutes les expériences.

Chaque fichier est autonome : on l'ouvre directement dans un navigateur, ou via GitHub Pages.

### Scènes jouées
- **`wang-fo.html`** — *Comment Wang-Fô fut sauvé*, d'après Marguerite Yourcenar. Portraits à l'encre, musique pentatonique synthétisée, et un peintre qui échappe à la mort en entrant dans sa propre peinture.
- **`shakespeare.html`** — *Roméo & Juliette*, II.2, la scène du balcon. Avec musique.
- **`trailer.html`** — *Les Mille Souvenirs*, un mini-trailer JRPG inventé.

### Spikes
Décors (`clairiere`, `donjon`, `ruelle`, `place`, `village`), échelles et caméras (`carte`, `scene`, `recul`, `scroll-*`), présences (`marque`, `fantome`, `perso`), matière du texte (`fremir`, `matiere`), le corps (`separe`).

## Commandes

- **Souris** : avive / mouille l'encre.
- **Flèches / WASD** : déplacement, selon la scène.
- **Molette / Page Down** : pour les expériences à défilement.
- **Clic / Espace** : avancer dans les scènes jouées. *Le son démarre au premier clic.*
- **M** : couper le son. **R** : recommencer.

## Technique

- HTML5 `<canvas>` 2D, JavaScript vanilla.
- Police *EB Garamond* via Google Fonts (repli serif si hors-ligne).
- Musique synthétisée à la volée via Web Audio API.
- Aucune build, aucun `npm`, aucun framework.

---

*Le modèle est remplaçable ; la mémoire ne l'est pas.*
