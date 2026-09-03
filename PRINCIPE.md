# Météo de l'équipe – Principe et barème

## Objectif

Dispositif léger de suivi du bien-être de l'équipe, orienté ressenti individuel (mal-être, charge, moral), pour :

- détecter les signaux faibles de souffrance ou de surcharge,
- ouvrir des 1:1 ciblés,
- visualiser une tendance d'équipe sprint après sprint.

Ce n'est pas un KPI de delivery, mais un **thermomètre humain**.

---

## Critères (2 maximum)

Chaque membre de l'équipe répond individuellement (identifié) sur **2 critères**, chacun noté de **0 à 5**.

### 1. Travail & Charge

Point de vue équipe : le travail qu'on a réalisé.

> « Sur ce sprint, comment évalues-tu :  
> – ta charge de travail,  
> – et le climat autour du travail (pression, urgences, organisation) ? »

**Échelle (0–5) :**

- **0** – Insoutenable : charge écrasante et/ou climat très tendu  
- **1** – Très lourd : difficile à tenir sur la durée  
- **2** – Lourd : ça passe, mais avec tension visible  
- **3** – Correct : globalement tenable, quelques pics  
- **4** – Bon : charge et climat maîtrisés la plupart du temps  
- **5** – Très bon : charge réaliste, climat serein  

### 2. Moral & énergie

Point de vue individuel : le ressenti.

> « Comment évalues-tu en ce moment :  
> – ton moral global,  
> – et ton niveau d'énergie / fatigue ? »

**Échelle (0–5) :**

- **0** – Épuisement / moral très bas  
- **1** – Très fatigué(e), moral fragile  
- **2** – Fatigué(e), moral en baisse  
- **3** – Ça tient : ni bien ni mal, dans la norme  
- **4** – Plutôt en forme, moral correct à bon  
- **5** – En pleine forme, moral et énergie au top  

---

## Calcul du score global

Le barème n'est pas figé sur un effectif. Il dépend du **nombre de réponses individuelles reçues** (N).

- **N** : nombre de réponses  
- **Nombre de critères** : 2  
- **Note max par critère** : 5 (soit 10 points max par personne)  

**Score max total** : N × 10  
**Score max par critère** : N × 5  
**Score total** = somme de toutes les notes (sur N × 10).

Exemple avec 6 réponses :

- Critère 1 (Travail & Charge) : [3, 2, 4, 3, 2, 3] → 17/30  
- Critère 2 (Moral & énergie) : [2, 3, 3, 2, 2, 3] → 15/30  
- **Score total** : 32/60  

Avec 4 réponses, le même barème donnerait un max de 40 (4 × 10) et 20 par critère.  

---

## Seuil d'alerte individuel

Le score global décrit le climat d'équipe. Il ne suffit pas : une météo correcte peut masquer une personne en difficulté.

**Seuil** : la **somme des deux critères** (sur 10) déclenche une **alerte individuelle** si elle est **inférieure ou égale à 3** (donc strictement inférieure à 4).

| Total / 10 | Lecture | Action |
|------|---------|--------|
| **4 à 10** | Dans la norme ou au-dessus | Pas d'alerte. |
| **≤ 3** (0, 1, 2 ou 3) | Signal de surcharge, tension, fatigue ou mal-être | Alerte : proposer un 1:1 et du soutien. |

Règles d'usage :

- L'alerte se lit sur **les deux critères réunis**, pas sur chaque note isolée. Un 1 peut être compensé par un 3 (total 4 : pas d'alerte). Un 0 et un 3 (total 3) lèvent une alerte.
- Une météo d'équipe ensoleillée peut quand même masquer une personne sous le seuil.
- Les réponses individuelles restent entre le lead et la personne concernée. Elles ne sont **pas affichées** sur la slide KPI.
- Une alerte n'est pas un jugement : c'est un signal pour ouvrir la conversation.

Exemple : même si la météo d'équipe reste « averses », une personne à 1 + 2 (total 3/10) déclenche une alerte individuelle.

---

## Paliers météo (emojis)

Le score total est traduit en « météo de l'équipe » **par rapport au score max** (N × 10), pas sur un barème fixe à 60.

| Ratio du max | Ex. 6 réponses (/60) | Météo | Interprétation |
|--------------|----------------------|---------|------------------|
| **≥ 80 %**   | 48–60 | ☀️ Grand soleil | Équipe globalement en très bonne forme, charge et moral bons. |
| **60–79 %**  | 36–47 | ⛅ Éclaircies / nuages | Ça tient, mais avec des signes de fatigue ou de tension à surveiller. |
| **40–59 %**  | 24–35 | 🌦️ Averses | Climat difficile : charge et/ou moral clairement dégradés. Ouvrir le sujet en review. |
| **20–39 %**  | 12–23 | 🌧️ Pluie battante | Situation préoccupante, risque de burn-out / désengagement. Agir rapidement. |
| **< 20 %**   | 0–11 | ⛈️ Orage | Crise ouverte : équipe en grande souffrance, action immédiate requise. |

---

## Affichage sur la slide KPI

Exemple de rendu (6 réponses) :

- **Météo équipe** : 32/60 → 🌦️ Averses  
- **Détail par critère** (optionnel) :  
  - Travail & Charge : 17/30  
  - Moral & énergie : 15/30  
- **Alertes individuelles** : indiquer uniquement le *nombre* de personnes sous le seuil (≤ 3/10), jamais les noms ni les notes.

Si le dispositif est répété sprint après sprint, ajouter une **flèche de tendance** (↑ / → / ↓) ou une mini-courbe d'évolution du score total.

---

## Cadre et limites (à expliciter à l'équipe)

- **Format** : individuel, identifié, non anonyme.  
- **Objectif** : détecter des situations de mal-être et proposer du soutien, pas juger.  
- **Usage** :  
  - le score global alimente la slide KPI,  
  - les réponses individuelles restent entre le lead et chaque personne (1:1 si le total est ≤ 3/10, ou si la personne le souhaite).  

**Si le/la lead fait partie du problème** :

- Il est explicite que chacun peut **escalader** (N+2, RH, autre manager, référent bien-être, etc.).  
- Ce canal doit être **clair, connu et crédible** (déjà utilisé sans représailles).  

Exemple de notice à mettre en intro du formulaire :

> « Ce questionnaire est individuel et identifié. Il est conçu pour que je puisse repérer les situations difficiles et vous proposer du soutien.  
>  
> Si je fais moi-même partie des difficultés que vous rencontrez, vous pouvez en parler à [N+2 / RH / autre contact], sans passer par moi.  
>  
> L'objectif n'est pas de juger, mais d'agir : si votre situation est difficile, le mieux est qu'on en parle directement. »

---

## Rythme recommandé

- **Fréquence** : en fin de sprint, avant l'itération review.  
- **Temps de réponse** : 2–3 minutes max par personne.  
- **Collecte** : 24–48h avant la review, avec deadline claire.  
- **Restitution** :  
  - météo globale sur la slide KPI,  
  - 1:1 ciblés si le total individuel est ≤ 3/10, ou à la demande.  
