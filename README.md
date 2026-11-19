# Modern Tank 🎮

Petit jeu de tanks en vue de dessus pour iPhone (et navigateur) : balles qui rebondissent, mines, et tanks ennemis aux comportements différents.

## Jouer sur iPhone

1. Activer GitHub Pages : **Settings → Pages → Source : « Deploy from a branch »**, choisir la branche, dossier `/ (root)`.
2. Ouvrir l'adresse `https://<ton-compte>.github.io/Modern-tank/` dans **Safari**.
3. Bouton **Partager → « Sur l'écran d'accueil »** : le jeu s'ouvre en plein écran comme une app, et marche hors-ligne.
4. Tenir l'iPhone en **paysage**. (Pour le son, désactiver le mode silencieux.)

## Commandes

| Tactile (iPhone) | Clavier / souris |
|---|---|
| Glisser à **gauche** : rouler | ZQSD / WASD / flèches |
| Glisser à **droite** : viser, **relâcher** pour tirer | Souris : viser, clic : tirer |
| Bouton jaune : poser une mine | Espace (ou clic droit) |
| ⏸ en haut à droite : pause | P / Échap |

## Règles

- Tes balles rebondissent **une fois** sur les murs foncés. Attention à ne pas te toucher toi-même !
- Max 5 balles à l'écran et 2 mines à la fois.
- Les **murs clairs** se fissurent au 1er tir et se cassent au 2e. Les murs foncés sont indestructibles (les balles rebondissent dessus).
- Les mines explosent au bout de 10 s ou quand un tank passe dessus, et cassent tous les murs clairs autour.
- Une vie bonus toutes les 5 missions. Les ennemis détruits restent détruits si tu perds une vie.
- 10 missions dessinées à la main, puis des missions générées à l'infini.

## Ennemis

| Tank | Comportement |
|---|---|
| Brun | Immobile, tire lentement |
| Gris | Se déplace lentement |
| Vert | Immobile, balles rapides qui rebondissent 2 fois, vise par ricochet |
| Rouge | Tire en rafale |
| Violet | Rapide, esquive, pose des mines, vise par ricochet |
| Noir | Très rapide, balles rapides, pose des mines |

## Fichiers

- `index.html` : tout le jeu (HTML + JavaScript, canvas, sons synthétisés)
- `manifest.webmanifest`, `sw.js`, `icon-*.png` : installation sur l'écran d'accueil et mode hors-ligne
