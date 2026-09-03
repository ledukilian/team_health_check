# 🌦️ Team Health Check - Météo d'équipe

Outil léger pour suivre le **bien-être d'une équipe** sprint après sprint. Ce n'est pas un KPI de delivery : c'est un thermomètre humain, sous forme de météo.

Chaque personne note deux critères de **0 à 5** :

1. **Travail & Charge** : point de vue équipe / le travail qu'on a réalisé (charge, pression, urgences, organisation)
2. **Moral & énergie** : point de vue individuel, ressenti (moral global, fatigue)

La somme des notes donne une **météo d'équipe** (grand soleil → orage), affichable en review. Le barème est relatif : **10 points max par réponse reçue**, les paliers se recalent tout seuls. En parallèle, une somme des deux critères **inférieure ou égale à 3/10** déclenche une **alerte individuelle** : signal pour proposer un 1:1 et du soutien, sans exposer les réponses nominatives sur la slide KPI.

Les relevés sont rattachés à une **période** (libellé libre : sprint, mois, itération…). Un sélecteur en haut de page affiche la météo correspondante. L'interface a trois onglets : **Fonctionnement** (barème, paliers météo, seuil d'alerte), **Saisies** (météo d'équipe et réponses de la période sélectionnée) et **Suivi** (progression d'une période à l'autre, graphique équipe ou personnes, statistiques individuelles). Sans période, seul Fonctionnement est accessible ; Saisies et Suivi se déverrouillent après l'ajout d'une période.

## Comment l'utiliser

Deux façons de lancer l'outil. Dans les deux cas, **les données restent dans le navigateur, côté client** 🔐 : rien n'est envoyé à un serveur. Le suivi vit dans le `localStorage` de la machine et du navigateur utilisés. Pour conserver ou partager un relevé, exporter le JSON.

1. **GitHub Pages** : ouvrir [https://ledukilian.github.io/team_health_check/](https://ledukilian.github.io/team_health_check/). Prêt à l'emploi, sans installation.
2. **En local** : cloner ou télécharger ce dépôt, puis ouvrir `index.html` dans un navigateur. Même application, hors ligne, entièrement sur la machine.

Le fichier d'échange est un JSON unique :

- `config.periods` : liste des périodes (`id` UUID + `label`)
- `responses` : notes par personne, liées à une période via `periodId`

## Contenu du dépôt

- [`index.html`](index.html) : prototype (périodes, saisie, tableau de bord, page de suivi, import/export JSON)
- [`PRINCIPE.md`](PRINCIPE.md) : barème, paliers météo, seuil d'alerte et cadre d'usage

Le détail du barème, des paliers et des limites (anonymat de la restitution, escalade si le lead fait partie du problème) est dans [`PRINCIPE.md`](PRINCIPE.md).
