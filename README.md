
# Site académique bilingue — modèle statique (FR/EN)

Dossier prêt à l’emploi avec deux arborescences (`/fr` et `/en`) partageant les mêmes assets.

## Remplacer les contenus
- Éditez les fichiers HTML dans `/fr` et `/en`.
- Remplacez `assets/photo.jpg` par votre portrait (600×600 px conseillé).
- Déposez vos CV en `assets/cv-fr.pdf` et `assets/cv-en.pdf`.

## Déploiement
- GitHub Pages / Netlify / hébergement FTP : déposez tout le dossier.
- La page racine `index.html` redirige automatiquement selon la langue du navigateur (FR→/fr, sinon →/en) et propose des liens FR/EN.

## Personnalisation
- Couleur d’accent : modifiez `--accent` dans `assets/style.css`.
- Ajoutez des logos, tracking, ou pages supplémentaires à votre convenance.
