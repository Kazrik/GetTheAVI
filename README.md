# Get The A : VI

Mini-jeu HTML/JS/CSS autonome (canvas, aucune dépendance) pour réviser les verbes irréguliers
anglais. Généré et lié depuis l'application Evaluator — chaque lien `?v=...` encode les verbes
du jour pour une classe donnée ; sans paramètre, la page tourne en mode démo.

Hébergé via GitHub Pages depuis ce dépôt.

## Structure

- `index.html` — le jeu complet (carte d'exploration, 4 mini-jeux : La Foule, Le Poste, Le
  Coffre, La Poursuite).
- `assets/` — sprites originaux (héros/héroïne, policiers, "méchants" génériques, objets
  ramassables) fournis par l'auteur, aucun emprunt à une œuvre existante.

## Lien avec verbes personnalisés

```
index.html?v=<JSON des verbes encodé en base64url>&t=<titre affiché>
```
