# zaydmoto.com — version « un seul dossier »

Tous les fichiers sont **au même niveau** (aucun sous-dossier). Impossible de casser la structure : rien à aplatir, aucun doublon de nom.

## Mettre en ligne sur GitHub Pages (gratuit)

1. Créez un compte sur https://github.com
2. **New repository** → nom `zayd-moto` → visibilité **Public** → *Create*.
3. **Add file → Upload files** → sélectionnez **TOUS les fichiers de ce dossier** (Ctrl+A / tout sélectionner) et déposez-les. Comme il n'y a pas de sous-dossiers, tout arrive correctement du premier coup.
4. **Commit changes**.
5. **Settings → Pages → Build and deployment → Source : _Deploy from a branch_ → Branch : `main` / `/ (root)` → Save.**
6. Après 1–2 minutes, le site est en ligne (lien affiché en haut de la page Pages).

> ✅ Pas besoin de workflow, pas de fichier caché `.github`. Le site se publie tout seul depuis la branche.

## Pages du site

- `index.html` — accueil (français)
- `en.html` — accueil anglais · `ar.html` — accueil arabe
- Modèles FR : `touring-pro-gris.html`, `touring-pro-noir.html`, `touring-pro-rouge.html`, `neo-camouflage.html`, `neo-turquoise.html`, `veracrus-smart-noir.html`, `veracrus-smart-gris.html`
- Modèles EN : `en-touring-pro-gris.html` … `en-veracrus-smart-noir.html`, `en-veracrus-smart-gris.html`
- Modèles AR : `ar-touring-pro-gris.html` … `ar-veracrus-smart-noir.html`, `ar-veracrus-smart-gris.html`
- `moto-electrique-tanger.html`, `blog-quel-scooter-electrique-choisir-a-tanger.html`
- `styles.css`, `nav.js`, toutes les photos `.jpg`, `sitemap.xml`, `robots.txt`

## Domaine personnalisé (zaydmoto.com)

Le fichier `CNAME` (contient `zaydmoto.com`) est déjà inclus. Dans **Settings → Pages → Custom domain**, entrez `zaydmoto.com`, puis chez votre registrar :
- `CNAME` : `www` → `VOTRE-NOM.github.io`
- 4 enregistrements `A` (apex) : `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`

Pas de domaine ? Supprimez le fichier `CNAME` — le site restera sur `https://VOTRE-NOM.github.io/zayd-moto/`.
