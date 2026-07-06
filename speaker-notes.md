# Notes de présentation — « Pourquoi LuxProvide »
### Pour Marco Michon & Gaspard Briand · devant Vittorio Santonocito (Head of Startups)

---

## 00 · Ouverture
**Parle : Marco & Gaspard (ensemble)**
- Merci pour le temps accordé — on sait que le programme INITIATE reçoit beaucoup de dossiers.
- On ne vient pas demander un supercalculateur "pour tout faire" : on a **6 cas d'usage concrets**, déjà pensés, qui ont chacun besoin de puissance de calcul et de souveraineté.
- Deux besoins réels, pas un effet de mode IA : calcul intensif + conformité RGPD pour le secteur bancaire/restauration.

## 01 · Qui nous sommes
**Parle : Marco & Gaspard (ensemble, chacun enchaîne sur l'autre)**
- On est deux cofondateurs, on construit ensemble — pas "chacun sa brique".
- Déjà en production : **SixSeven**, notre app de gestion d'équipe, tourne au rooftop du Royal Hamilius (Luxembourg-Ville), déploiement en cours chez Mess Family Groupe (marque Grand Mess, France).
- Déjà en production aussi : **8 automatisations** dans le Middle/Back Office et le pôle fiscal d'une grande banque de la place — 773h/an libérées, ~0,44 ETP, pour ~120€/mois d'outillage.
- Message clé : on n'est pas deux gars avec une idée sur PowerPoint, on a déjà livré et on facture en B2B au Luxembourg.

## 02 · Le marché
**Parle : Gaspard**
- 58,2 Mt de nourriture gaspillée chaque année dans l'UE = 132 milliards € de valeur perdue (Eurostat 2023).
- La restauration pèse 11% de ce gaspillage — c'est notre terrain de jeu direct.
- Chaque point de gaspillage évité = marge directe pour nos clients restaurateurs, pas juste un argument RSE.

## 03 · Cas d'usage 1 — Prévision à l'échelle de la plateforme
**Parle : Gaspard**
- Pas un modèle, une flotte : des centaines d'établissements × des milliers de références, réentraînés chaque jour.
- Scénario concret : canicule + hausse de prix + nouveau menu → besoin de recalculer l'impact sur les stocks instantanément.
- Sur une infra classique : des jours de calcul. Sur MeluXina : quelques heures.
- ≈ 900–1 400 GPU·h/an estimés pour ce cas d'usage seul.
- Point RGPD à glisser : données de fidélité et de livraison = données clients, doivent rester en UE.

## 04 · Cas d'usage 2 — Optimisation anti-gaspillage
**Parle : Marco**
- Chiffre fort à marteler : **7€ économisés pour 1€ investi** dans la réduction du gaspillage.
- Objectif : -26% de gaspillage dès l'année 1 sur le réseau (114 restaurants, 12 pays dans notre pipeline).
- C'est de l'optimisation combinatoire + simulation à l'échelle — la charge explose avec le nombre de sites, exactement ce que MeluXina est fait pour absorber.
- Rattacher à la Luxembourg AI Factory : secteur durabilité, MeluXina = supercalculateur le plus vert d'Europe → argument qui parle à LuxProvide spécifiquement.
- ≈ 700–1 100 GPU·h/an estimés.

## 05 · Cas d'usage 3 — Données synthétiques (scénario Société Générale)
**Parle : Gaspard**
- Le problème concret : un choix de plat en cantine d'entreprise peut révéler une religion ou un problème de santé — donnée sensible au sens de l'article 9 RGPD.
- Badgeage, fréquentation, régimes alimentaires : aujourd'hui inutilisables librement pour entraîner un modèle.
- Solution : MeluXina génère des données synthétiques statistiquement fidèles, zéro donnée personnelle réelle — les vraies données ne sortent jamais du périmètre client.
- C'est le cas d'usage le plus lourd en calcul : **≈ 1 600–2 200 GPU·h/an** — la génération GPU justifie à elle seule une bonne partie de la demande.
- Message pour Vittorio : c'est exactement le genre de contrainte qui bloquerait un contrat avec un grand compte bancaire si on n'était pas 100% européens, hors de portée du Cloud Act.

## 06 · Cas d'usage 4 — Apprentissage fédéré
**Parle : Gaspard**
- Le modèle voyage, jamais la donnée : chaque site calcule localement, seuls les paramètres du modèle sont agrégés sur MeluXina.
- Privacy by design (article 25 RGPD) — pas un correctif après-coup, une architecture pensée pour ça.
- Argument commercial fort : "vos données ne quittent jamais vos murs" est un argument que peu de nos concurrents peuvent dire sérieusement.
- Cible : banques et hôpitaux — deux secteurs où c'est un différenciateur produit, pas juste un nice-to-have.
- Cas le plus léger en calcul : ≈ 250–400 GPU·h/an (la majorité du calcul reste sur site, pas sur MeluXina).

## 07 · Cas d'usage 5 — Optimisation de menus multi-contraintes
**Parle : Marco**
- 5 contraintes simultanées (coût, nutrition, allergènes, carbone, préférences), des dizaines de sites, des cycles de plusieurs semaines.
- Contexte : cantines scolaires, régimes hospitaliers — les normes ne sont jamais optionnelles.
- Chiffre : 6€ économisés pour 1€ investi en restauration collective (86 sites, 6 pays — référence secteur).
- Deux terrains stratégiques pour LuxProvide en un cas d'usage : durabilité **et** secteur public.
- ≈ 500–800 GPU·h/an estimés.
- Point RGPD : personnaliser selon allergies/régimes touche à des données de santé — encore un argument pour un environnement souverain, pas un cloud générique.

## 08 · Cas d'usage 6 — Construire sur Flinky
**Parle : Marco**
- Ici on ne demande pas juste du calcul brut : on veut adopter Flinky directement.
- OCR souverain branché par API sur nos bons de livraison fournisseurs — ça nous fait gagner des mois de dev.
- LLM souverain pour notre assistant de cuisine.
- Message clé pour Vittorio : on ne veut pas juste être client de MeluXina, on veut être partenaire produit — on construit sur votre stack, pas seulement sur votre machine.
- ≈ 400–650 GPU·h/an estimés.

## 09 · Synthèse
**Parle : Marco & Gaspard (ensemble)**
- Trois cercles qui se recoupent : IA, RGPD, Souveraineté — MeluXina est au centre des trois.
- Résumer en une phrase : un vrai besoin de calcul, un vrai marché, une contrainte réglementaire (RGPD) transformée en avantage technique plutôt qu'en frein.

## 10 · Notre demande
**Parle : Gaspard pour les chiffres, Marco pour la demande/partenariat, les deux pour la conclusion**
- La demande précise : accès au programme INITIATE (calcul + crédits + mentorat) + **un référent ingénieur** pour nous aider à cadrer.
- La roadmap en 4 jalons :
  - **M0** — cadrage avec Luxinnovation + dépôt de l'aide d'État RDI.
  - **M1** — prototypage des cas d'usage prioritaires (données synthétiques, prévision plateforme).
  - **M6** — déploiement du reste des cas d'usage + premier bilan de charge/impact.
  - **M12** — bascule vers Cashback 80% pour l'industrialisation.
- Chiffre total : ≈ 5 450 GPU·h sur 12 mois (fourchette 4 350–6 550) — **à dire explicitement comme une estimation initiale**, pas un chiffre gravé dans le marbre, qu'on veut affiner avec leurs ingénieurs.
- Clore sur : on n'est pas là pour un chèque, on est là pour construire une relation dans la durée — INITIATE aujourd'hui, Cashback 80% demain.

---
### Rappels de ton pour toute la présentation
- Ne jamais nommer la banque : toujours "une grande banque de la place".
- Qualee n'est jamais un "OS" ni un "SaaS" — un partenaire de transition IA pour les restaurants.
- Les chiffres GPU·h sont des estimations à assumer comme telles si on nous challenge dessus.
