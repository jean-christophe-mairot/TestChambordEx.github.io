### Tuto : mise en ligne sur GitHub Pages via glisser‑déposer (drag & drop)

Durée estimée : 10–20 min. Pré‑requis : compte GitHub.

1. Préparer les fichiers

   - Assurez‑vous d’avoir un fichier index.html à la racine du site, et que tous les chemins relatifs (css/, js/, images/) sont corrects.
   - Optionnel : mettre tous les fichiers dans un dossier `docs/` si vous préférez publier depuis cette racine.

2. Créer le dépôt GitHub

   - Connectez‑vous sur github.com.
   - Cliquez sur "New repository".
   - Donnez un nom (ex. hotel-chambord), description facultative.
   - Choisissez Public (GitHub Pages gratuit pour les dépôts publics).
   - Ne cochez pas "Initialize this repository with a README" si vous voulez téléverser tout le site intact.

3. Téléverser les fichiers (drag & drop)

   - Ouvrez le dépôt nouvellement créé.
   - Cliquez sur "Add file" → "Upload files".
   - Glissez‑déposez l’ensemble des fichiers et dossiers du site dans la zone prévue.
   - Vérifiez que `index.html` se trouve bien à la racine (ou dans `docs/` si vous avez choisi cette option).
   - Ajoutez un message de commit (par ex. "Initial upload site") et cliquez sur "Commit changes".

4. Activer GitHub Pages

   - Allez dans "Settings" du dépôt → section "Pages" (ou "Code and automation" → "Pages" selon l’interface).
   - Sous "Build and deployment", choisissez la source :
     - Branch: `main` (ou `master`) et Folder: `/ (root)` si index.html est à la racine.
     - OU Branch: `main` and Folder: `/docs` si vous avez utilisé `docs/`.
   - Cliquez sur "Save" (ou "Save and deploy"). GitHub lancera le déploiement.

5. Obtenir l’URL du site

   - Après déploiement (quelques minutes), l’URL apparaîtra : https://<votre‑pseudo>.github.io/<nom‑du‑repo> (ou https://<votre‑pseudo>.github.io si dépôt nommé `<votre‑pseudo>.github.io`).
   - Ouvrez l’URL pour vérifier le rendu.

6. Mettre à jour le site

   - Pour modifier le site via l’interface web : retournez dans "Add file" → "Upload files" et glissez les nouveaux fichiers (remplacez les précédents), puis commit.
   - Vous pouvez aussi utiliser Git en local pour push si vous préférez le contrôle de version.

7. Problèmes fréquents

   - Page 404 : vérifier la présence d’un `index.html` dans la racine ou `docs/` selon la source choisie.
   - Changements non visibles : attendre quelques minutes puis vider le cache du navigateur.
   - Ressources manquantes : vérifier chemins relatifs et majuscules/minuscules (GitHub Pages est sensible à la casse).

Notes finales

- Le drag & drop via l’interface web est simple pour des sites statiques. Pour évolutions fréquentes ou équipes, privilégiez Git (commit/push) et workflows (branches, PR).
- Conserver une copie locale du projet pour développement et sauvegarde.
