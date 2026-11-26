# satis — galerie de jeux

- `index.html` : galerie
- `jeux/` : un fichier autonome par jeu — billes, tranche, bulles, sable, mandala, dominos, limaille, engrenages, gouttes

Ouvrir `index.html` dans un navigateur suffit, aucun build.

## Ajouter un jeu
1. Déposer `jeux/mon-jeu.html`.
2. Copier une carte `<a class="card">` dans `index.html`.

## Héberger en le gardant privé
GitHub Pages sur un dépôt public est visible par tout le monde.
Pour un accès réservé à soi : Cloudflare Pages + Cloudflare Access (connexion par e-mail), ou Netlify/Vercel avec protection par mot de passe.
