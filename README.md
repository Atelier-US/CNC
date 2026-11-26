# CNC Atelier

Assistant HTML d’atelier pour les calculs d’usinage et de métrologie. L’application existante est déjà conçue avec une mise en page adaptative et une balise viewport pour les écrans mobiles.

## Accès depuis un téléphone

Après publication avec GitHub Pages, ouvrez l’URL du site sur le téléphone. La page d’accueil `index.html` redirige vers l’application; le bouton reste disponible si la redirection automatique est bloquée.

## Activer GitHub Pages

Dans le dépôt GitHub, ouvrez **Settings → Pages**, choisissez **Deploy from a branch**, sélectionnez `main` et le dossier `/ (root)`, puis enregistrez. GitHub affichera l’URL du site dans cette page lorsqu’il sera publié.

**À noter :** le dépôt est actuellement privé. La visibilité du site dépend de votre offre GitHub et des réglages Pages de l’organisation/du compte. Si l’URL doit être accessible sans connexion à tout le monde, vérifiez que les Pages privées sont autorisées ou rendez le dépôt public (uniquement si cela convient à votre atelier).

L’application charge Tailwind CSS et les polices depuis des services externes; une connexion Internet est donc nécessaire pour obtenir son apparence complète. Les calculs JavaScript restent dans le navigateur.
