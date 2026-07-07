# Notes de présentation — « Pourquoi LuxProvide » (version simplifiée)
### Pour Marco Michon & Gaspard Briand · devant Vittorio Santonocito (Head of Startups)

---

## 00 · Ouverture
**Parle : Marco & Gaspard (ensemble)**
- Merci pour votre temps — on sait qu'INITIATE reçoit beaucoup de dossiers.
- On ne vient pas demander un supercalculateur "pour tout faire" : on a **6 cas d'usage
  concrets**, déjà pensés.
- Deux vrais besoins : calcul intensif et conformité RGPD, pas un effet de mode IA.

## 01 · Qui nous sommes
**Parle : Marco & Gaspard (ensemble, chacun enchaîne sur l'autre)**
- On est deux cofondateurs, on construit ensemble.
- Déjà en production : **SixSeven**, notre app de gestion d'équipe, au rooftop du Royal
  Hamilius (Luxembourg-Ville), et bientôt chez Mess Family Groupe (marque Grand Mess,
  France).
- Déjà en production aussi : **8 automatisations** dans une grande banque de la place —
  773h/an libérées, ~0,44 ETP, pour ~120€/mois d'outillage.
- Message clé : on a déjà livré, on facture déjà en B2B au Luxembourg.

## 02 · Le marché
**Parle : Gaspard**
- 58,2 Mt de nourriture gaspillée chaque année dans l'UE = 132 milliards € perdus
  (Eurostat 2023).
- La restauration pèse 11 % de ce gaspillage — c'est notre terrain.
- Chaque point de gaspillage évité = marge directe pour nos clients, pas juste un
  argument RSE.

## 03 · Cas d'usage 1 — Prévision à l'échelle de la plateforme
**Parle : Gaspard**
- Pas un modèle, une flotte : des centaines d'établissements, des milliers de références,
  réentraînés chaque jour.
- Exemple : canicule + hausse des prix + nouveau menu → il faut recalculer l'impact sur
  les stocks tout de suite.
- Infra classique : des jours. MeluXina : quelques heures.
- ≈ 900–1 400 GPU·h/an pour ce cas seul.
- RGPD : données de fidélité et de livraison = données clients, doivent rester en UE.

## 04 · Cas d'usage 2 — Optimisation anti-gaspillage
**Parle : Marco**
- Le chiffre à marteler : **7€ économisés pour 1€ investi** contre le gaspillage.
- Objectif : -26 % de gaspillage dès l'année 1 (114 restaurants, 12 pays).
- La charge de calcul explose avec le nombre de sites — exactement ce que MeluXina est
  fait pour absorber.
- Ça rejoint la Luxembourg AI Factory, secteur durabilité — MeluXina est le
  supercalculateur le plus vert d'Europe.
- ≈ 700–1 100 GPU·h/an.

## 05 · Cas d'usage 3 — Données synthétiques (scénario Société Générale)
**Parle : Gaspard**
- Le problème : un choix de plat en cantine peut révéler une religion ou un problème de
  santé — donnée sensible, article 9 du RGPD.
- Aujourd'hui, ces données sont inutilisables pour entraîner un modèle.
- Solution : MeluXina génère des données synthétiques, fidèles statistiquement, mais
  zéro donnée personnelle réelle. Les vraies données ne sortent jamais du client.
- Le cas le plus lourd en calcul : **≈ 1 600–2 200 GPU·h/an** — la génération justifie à
  elle seule une bonne partie de la demande.
- Pour Vittorio : exactement le genre de contrainte qui bloquerait un contrat bancaire si
  on n'était pas 100 % européens, hors de portée du Cloud Act.

## 06 · Cas d'usage 4 — Apprentissage fédéré
**Parle : Gaspard**
- Le modèle voyage, jamais la donnée : chaque site calcule localement, seuls les
  paramètres remontent vers MeluXina.
- Privacy by design (article 25 RGPD) — pensé dès le départ, pas ajouté après coup.
- Argument fort : "vos données ne quittent jamais vos murs" — peu de concurrents peuvent
  le dire sérieusement.
- Cible : banques et hôpitaux.
- Cas le plus léger en calcul : ≈ 250–400 GPU·h/an.

## 07 · Cas d'usage 5 — Optimisation de menus multi-contraintes
**Parle : Marco**
- 5 contraintes en même temps : coût, nutrition, allergènes, carbone, préférences — sur
  des dizaines de sites, plusieurs semaines de cycle.
- Contexte : cantines scolaires, régimes hospitaliers — rien n'est optionnel.
- Chiffre : 6€ économisés pour 1€ investi en restauration collective (86 sites, 6 pays).
- Deux terrains stratégiques en un seul cas d'usage : durabilité et secteur public.
- ≈ 500–800 GPU·h/an.
- RGPD : personnaliser selon allergies/régimes touche à des données de santé — encore un
  argument pour un environnement souverain.

## 08 · Cas d'usage 6 — Construire sur Flinky
**Parle : Marco**
- On ne demande pas juste du calcul brut : on veut adopter Flinky directement.
- OCR souverain sur nos bons de livraison — ça nous fait gagner des mois de dev.
- LLM souverain pour notre assistant de cuisine.
- Message clé : on ne veut pas juste être client de MeluXina, on veut être partenaire
  produit.
- ≈ 400–650 GPU·h/an.

## 09 · Synthèse
**Parle : Marco & Gaspard (ensemble)**
- Trois cercles qui se recoupent : IA, RGPD, Souveraineté — MeluXina au centre.
- En une phrase : un vrai besoin de calcul, un vrai marché, une contrainte réglementaire
  transformée en avantage technique.

## 10 · Notre demande
**Parle : Gaspard pour les chiffres, Marco pour la demande, les deux pour conclure**
- La demande : accès au programme INITIATE (calcul + crédits + mentorat) + un
  **référent ingénieur** pour nous aider à cadrer.
- 4 jalons :
  - **M0** — cadrage avec Luxinnovation + dépôt de l'aide d'État RDI.
  - **M1** — prototypage des cas prioritaires (données synthétiques, prévision
    plateforme).
  - **M6** — reste des cas d'usage déployés + premier bilan.
  - **M12** — bascule vers Cashback 80 % pour l'industrialisation.
- Chiffre total : ≈ 5 450 GPU·h sur 12 mois (fourchette 4 350–6 550) — à dire comme une
  **première estimation**, pas gravée dans le marbre, à affiner avec leurs ingénieurs.
- Pour conclure : on n'est pas là pour un chèque, on est là pour construire une relation
  dans la durée — INITIATE aujourd'hui, Cashback 80 % demain.

---
### Rappels de ton pour toute la présentation
- Ne jamais nommer la banque : toujours "une grande banque de la place".
- Qualee n'est jamais un "OS" ni un "SaaS" — un partenaire de transition IA pour les
  restaurants.
- Les chiffres GPU·h sont des estimations — à assumer comme telles si on nous challenge.
