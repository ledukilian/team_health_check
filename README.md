# Team Health Check

Outil léger pour suivre le **bien-être d'une équipe** sprint après sprint. Ce n'est pas un KPI de delivery : c'est un thermomètre humain, sous forme de météo.

Chaque personne note deux critères de **0 à 5** :

1. **Charge & climat de travail** — charge, pression, urgences, organisation
2. **Moral & énergie** — moral global, fatigue

La somme des notes donne une **météo d'équipe** (grand soleil → orage), affichable en review. Le barème est relatif : **10 points max par réponse reçue**, les paliers se recalent tout seuls. En parallèle, toute note **strictement inférieure à 3/5** déclenche une **alerte individuelle** : signal pour proposer un 1:1 et du soutien, sans exposer les réponses nominatives sur la slide KPI.

## Contenu du dépôt

- [`index.html`](index.html) — prototype local (saisie, tableau de bord, import/export CSV)
- [`PRINCIPE.md`](PRINCIPE.md) — barème, paliers météo, seuil d'alerte et cadre d'usage

Ouvrir `index.html` dans un navigateur suffit pour essayer le dispositif. Les réponses restent dans le navigateur.

Le détail du barème, des paliers et des limites (anonymat de la restitution, escalade si le lead fait partie du problème) est dans [`PRINCIPE.md`](PRINCIPE.md).
