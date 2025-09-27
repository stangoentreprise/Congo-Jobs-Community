# Congo Jobs Community — Mini site statique

Ce dossier contient une version statique adaptée du site "Congo Jobs Community" pour un contexte local (Congo Brazzaville). Le site est volontairement simplifié : pas d'authentification intégrée — on privilégie le contact direct et la publication simple d'annonces.

Fichiers principaux:
- `index.html` : page d'accueil moderne avec recherche et aperçu de services
- `services.html` : liste / résultats de recherche
- `post.html` : formulaire de publication
- `about.html`, `contact.html` : pages d'information
- `profile.html`, `dashboard.html` : vues de prestataire (statique)
- `styles.css` : petites personnalisations CSS

How to use:
- Ouvrez `index.html` dans votre navigateur (double-clic sous Windows). Le site est entièrement statique.
- Pour un déploiement local ou sur un hébergement statique, utilisez un serveur simple (voir instructions dans le fichier).

Note concernant l'architecture locale :
- L'approche ici favorise la simplicité : publier une annonce et laisser un numéro de contact visible aide les utilisateurs qui n'ont pas d'authentification ou d'email fiable.
- Si vous souhaitez plus tard ajouter une authentification, privilégiez des méthodes légères (vérification SMS, OAuth via Facebook/Google si disponible localement) ou l'utilisation d'un compte téléphone unique.

Remarques:
- Les images (logo.png, image_fond.png, etc.) sont utilisées depuis le dossier. Remplacez-les par vos images si nécessaire.
- J'ai utilisé Tailwind CDN pour accélérer le style; pour production, envisagez de builder un CSS local.
