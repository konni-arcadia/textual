# Théâtre d'encre — conventions

Sandbox d'exploration de rendu : récit interactif en caractères, HTML/Canvas purs.

## Règles dures
- Zéro dépendance, zéro asset, zéro build : chaque fichier HTML est autonome (canvas 2D, JS vanilla, Web Audio pour le son).
- Tout est généré par le code. Esthétique de référence : l'encre — densités `· : ░ ▒ ▓ █`, fond `#0d0c10`, EB Garamond via Google Fonts (repli serif).
- Tout en français : noms de fichiers, commentaires, textes à l'écran.

## Ajouter un spike (checklist)
1. Créer `spike-<nom>.html`, autonome, avec un bloc `// ---- a toucher ----` pour les réglages.
2. Ajouter sa carte dans la bonne section de `index.html`.
3. Ajouter son nom dans la ligne « Spikes » du `README.md`.

## Tester
Ouvrir le fichier directement dans un navigateur (`file://` suffit), ou `python -m http.server`.
Conventions de commandes : souris = aviver/orbiter, molette = approcher, T = mode de rendu, R = régénérer, M = son.
