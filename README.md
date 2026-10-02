# Le Brief — l’essentiel politique

Une page web en français qui rassemble les actualités politiques françaises et européennes publiées au cours des dernières 24 heures.

## Fonctionnalités

- Sélection du jour avec une une et une grille de sujets.
- Filtres France, Parlement et Europe.
- Horodatage, éditeur et lien vers chaque article original.
- Mise à jour à la demande et mise en page adaptée au mobile.

## Source des actualités

La page lit les flux RSS de recherche de Google Actualités en français et en France, puis déduplique les titres. Les requêtes couvrent la politique française, le Parlement et l’Union européenne. Les résultats sont fournis par Google Actualités ; les articles restent hébergés chez leurs éditeurs d’origine.

Le navigateur récupère les flux via le proxy public cors.dev pour contourner les restrictions CORS. Les requêtes utilisent son accès public anonyme (GET), sans clé ni compte, et ne transmettent aucun identifiant. Le service limite les requêtes gratuites à 120 par minute par adresse IP et à 1 MiB par réponse. Si le service ou le flux amont ne répond pas, le bouton **Actualiser** permet de réessayer.

## Lancer la page

Ouvrir `index.html` dans un navigateur moderne. Pour une URL publique, activer GitHub Pages dans les paramètres du dépôt et choisir la branche `main` à la racine. Une fois publié, le site est accessible à `https://selfahssi.github.io/ma-premiere-appli-ia/`.

## Limites

Le classement reflète les résultats des flux et l’heure de publication. Il ne s’agit pas d’une sélection éditoriale exhaustive, d’un résumé généré par IA ni d’une mesure de l’importance démocratique des sujets.

