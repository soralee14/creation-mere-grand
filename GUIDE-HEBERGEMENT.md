# Mettre le site en ligne gratuitement (GitHub Pages)

GitHub Pages héberge gratuitement les sites comme celui-ci. L'adresse sera du type :
`https://votre-pseudo.github.io/creation-mere-grand/`

## 1. Créer un compte GitHub
- Allez sur https://github.com et cliquez sur **Sign up** (c'est gratuit).

## 2. Créer un dépôt (le « dossier » du site)
1. Une fois connecté, cliquez sur **+** en haut à droite, puis **New repository**.
2. Nom : `creation-mere-grand`
3. Cochez **Public**.
4. Cliquez sur **Create repository**.

## 3. Envoyer les fichiers
1. Sur la page du dépôt, cliquez sur **uploading an existing file**.
2. Glissez-déposez : `index.html`, `style.css` et le dossier `images` (avec vos photos).
3. En bas, cliquez sur **Commit changes**.

## 4. Activer le site
1. Dans le dépôt : **Settings** → **Pages** (menu de gauche).
2. Sous **Branch**, choisissez `main` et `/ (root)`, puis **Save**.
3. Attendez 1 à 2 minutes, rafraîchissez : l'adresse du site s'affiche en haut.

## Modifier le site plus tard
- Cliquez sur un fichier dans GitHub → icône crayon ✏️ → modifiez → **Commit changes**.
- Le site se met à jour tout seul en 1 à 2 minutes.

## Ajouter les vraies photos
1. Mettez les photos dans le dossier `images` (noms simples, sans accents ni espaces : `echarpe-rouge.jpg`).
2. Dans `index.html`, remplacez par exemple :
   ```html
   <div class="placeholder">🧣</div>
   ```
   par :
   ```html
   <img src="images/echarpe-rouge.jpg" alt="Écharpe torsadée rouge">
   ```
3. Astuce : réduisez les photos à ~1200 px de large pour que le site charge vite.

## Photos à prévoir (dossier `images`)
- `accueil.jpg` : la pile de vêtements (grande photo du haut)
- `brigitte.jpg` : portrait de Brigitte (affiché en rond)
- `atelier-1.jpg`, `atelier-2.jpg`, `atelier-3.jpg` : l'atelier, les tissus, les vêtements sur cintres
- Une photo par création du Portfolio (enfants qui portent les vêtements)

Chaque emplacement est marqué par un commentaire `<!-- PHOTO : ... -->` dans `index.html`.

## À personnaliser dans `index.html`
- Les textes (accueil, « La créatrice »).
- Les créations du Portfolio (chaque bloc `<figure>` = une création ; copiez-collez pour en ajouter).
- Le téléphone et l'email sont déjà ceux de la pancarte : vérifiez-les.

## Bonus : un vrai nom de domaine (optionnel, payant)
Un nom comme `creation-mere-grand.fr` coûte environ 5 à 10 €/an (OVH, Gandi…).
On le relie ensuite dans **Settings → Pages → Custom domain**. L'hébergement reste gratuit.
