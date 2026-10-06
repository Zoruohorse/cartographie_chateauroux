# Adaptation du réseau Châteauroux sur le modèle Fouju

## Changements
- réseau généré depuis `data/actors.json`, `data/relations.json`, `data/claims.json` et `config/taxonomy.json` ;
- aucune liste métier dupliquée dans le moteur ;
- catégories, libellés et couleurs pilotés par la taxonomie ;
- recherche, filtres, sélection relationnelle, zoom centré, déplacement, recentrage et ajustement global ;
- interface responsive à trois panneaux ;
- tailles des nœuds calculées selon le nombre de relations ;
- conservation des identifiants stables et du référentiel Châteauroux.

## Déploiement
Remplacer le contenu du dépôt par cette archive, puis publier la racine avec GitHub Pages.

## Extension
Un nouvel acteur ou une nouvelle relation ne nécessite qu’une modification des données. Une nouvelle catégorie nécessite seulement une entrée dans `config/taxonomy.json`.
