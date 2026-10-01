# Volvic « Soutien Collagène » : dossier de sources

Ce dossier suit la méthode du cours (« Où trouver la data ») : tarifs, santé financière, investissements et stratégie, intérêt du public.

Recherches faites le **1er octobre 2026**.

**Carte perceptuelle interactive** des concurrents directs (prix / qualité, chaque point renvoie vers ses sources) : `carte-perceptuelle-concurrents-directs.html`.

**Légende du statut de chaque donnée :**
- ✅ **Vérifié** : la page ou l'API officielle a été ouverte et le chiffre y a été lu.
- 🔎 **À ouvrir vous-même** : le chiffre a été vu dans un résultat de recherche, ou le site bloque les outils automatiques.
- ⛔ **Bloqué** : il faut faire la manipulation vous-même. La marche à suivre est donnée en partie 5.

> Comme le dit le cours : « le chiffre que vous gardez vient de la page que vous avez ouverte ». Avant le rendu, ouvrez chaque lien, vérifiez le chiffre et notez la date du relevé.

---

## 1. Les tarifs
*Méthode du cours : le site de chaque concurrent, relevé à la date ; la Wayback Machine pour les tarifs passés ; les comparateurs et les plateformes.*

> 🎯 **Intérêt pour le projet :** fixer le prix de Volvic Soutien Collagène par rapport à ce que paient déjà les clients. Ces prix forment l'abscisse de la carte perceptuelle.

### 1.a Concurrents directs (prix relevés le 01/10/2026)

> 🎯 **Intérêt pour le projet :** ce sont les seuls produits vraiment comparables : même produit (eau enrichie), mêmes clients. Le prix au litre permet de comparer des formats différents.

| Produit | Prix relevé | Format | Prix au litre | Source | Statut |
|---|---|---|---|---|---|
| **VIWA – Body Pro Collagène** | 2,50 € (2,00 € la canette) | 60 cl (ou canette 33 cl) | **4,17 €/L** | https://viwa-store.fr/ (prix) et https://www.viwafrance.fr/nos-produits/ (composition) | ✅ |
| **Squad Nutrition – Vitamin Water COLLAGEN+** | 2,90 € (2,45 € l'unité par 12) | 50 cl | **5,80 €/L** | https://www.squad-nutrition.fr/en/products/vitamin-water-collagen | ✅ |
| **D0SE** (vitamine C + zinc, vegan) | 1,99 € (1,77 € en abonnement) | canette 33 cl | **6,03 €/L** | https://d0se.fr/produit/framboise-fruit-du-dragon/ | ✅ |
| **Humble Collagen Water** | 2,99 € (≈2,54 € en promo) | canette 33 cl | **9,06 €/L** | https://www.pharmacasse.fr/articulations-tendons-et-muscles/28251-humble-collagen-water-framboise-gingembre-330-ml-collagene-3770018309170.html | 🔎 |
| **Vital Proteins Collagen Sparkling Water** (Nestlé, États-Unis) | 29,99 $ les 12 | 12 × 355 ml | 7,04 $/L (≈5,98 €/L à 1 $ ≈ 0,85 €) | https://www.vitalproteins.com/products/collagen-sparkling-waters | ✅ |
| **Vitaminwater** (Coca-Cola) | 2,60 € (prix de lancement en France, 2006) | 50 cl | 5,20 €/L | https://www.rayon-boissons.com/boissons-sans-alcool-et-eaux/vitaminwater-les-debuts-de-la-pepite-de-coca-cola-en-france-5873 | 🔎 (ancien) |

### 1.b Repères de prix : grande distribution et Volvic

> 🎯 **Intérêt pour le projet :** le plancher de prix. C'est ce que le client paie aujourd'hui pour une eau aromatisée, y compris chez Volvic. Cela permet de justifier le surcoût d'une eau enrichie.

| Produit | Prix | Prix au litre | Source | Statut |
|---|---|---|---|---|
| **Volvic Juicy Fraise** 1,5 L | 1,40 € (1,14 € en promo « 4 achetés, 3 payés ») | 0,93 €/L | https://www.carrefour.fr/p/eau-plate-aromatisee-fraise-juicy-volvic-3057640467233 | 🔎 (carrefour.fr bloque les robots) |
| **Cristaline aromatisée pêche** 1,5 L (premier prix) | 1,17 € | 0,78 €/L | https://www.carrefour.fr/p/eau-plate-aromatisee-au-jus-peche-cristaline-3254381047995 | 🔎 |
| **Carrefour Sensation**, eau gazeuse citron (marque de distributeur) | 2,94 € les 6 × 50 cl | ≈0,98 €/L, ≈0,52 €/L avec la carte | https://www.carrefour.fr/p/eau-gazeuse-aromatisee-citron-carrefour-sensation-3560071453213 | 🔎 |
| **Volvic Vitamin+** (Royaume-Uni, 2026) | 2,20 £ les 75 cl | ≈2,93 £/L | https://www.foodanddrinktechnology.com/news/65730/volvic-dives-into-functional-water-category/ | ✅ |

### 1.c Wayback Machine (tarifs passés) ⛔

> 🎯 **Intérêt pour le projet :** voir si les concurrents ont augmenté ou baissé leurs prix depuis leur lancement, ce qui montre la tension du marché.
web.archive.org refuse les connexions depuis mes outils. La manipulation à faire est en partie 5.

---

## 2. La santé financière
*Méthode du cours : les comptes annuels sur l'Annuaire des entreprises ou Pappers, sur plusieurs années ; le rapport annuel quand c'est un groupe ; les procédures collectives au BODACC.*

> 🎯 **Intérêt pour le projet :** savoir si Volvic a les moyens de lancer la gamme, et si les concurrents sont solides ou fragiles.

> **Source technique.** Les chiffres ci-dessous viennent de l'**API officielle de l'Annuaire des entreprises** (recherche-entreprises.api.gouv.fr) et du **jeu de données « Ratios financiers BCE/INPI »** (https://data.economie.gouv.fr/explore/dataset/ratios_inpi_bce/). Ce sont les données que l'Annuaire des entreprises affiche dans son onglet « Données financières ».
> Les pages de l'Annuaire et de Pappers bloquent mes outils (erreurs 403 et 503). **Ouvrez-les vous-même** pour vérifier et faire vos captures d'écran :
> - https://annuaire-entreprises.data.gouv.fr/donnees-financieres/395780059
> - https://www.pappers.fr/entreprise/sev-societe-des-eaux-de-volvic-395780059

### 2.a Société des Eaux de Volvic (SEV), SIREN 395 780 059 ✅

> 🎯 **Intérêt pour le projet :** prouver que Volvic peut financer le lancement : le chiffre d'affaires et la rentabilité sont en hausse.

Fiche d'identité :
- Activité : NAF 11.07A (eaux de table).
- Siège : Volvic (63).
- Création : 1957.
- Effectif : 500 à 999 salariés (tranche INSEE « 41 »).
- Comptes publics.

| Exercice | Chiffre d'affaires | Résultat net | EBE | Marge d'EBE | Marge nette |
|---|---|---|---|---|---|
| 2025 | **558,3 M€** | 41,2 M€ | 74,6 M€ | 13,4 % | 7,4 % |
| 2024 | 547,0 M€ | 45,0 M€ | 83,3 M€ | 15,2 % | 8,2 % |
| 2023 | 515,5 M€ | 23,0 M€ | 58,0 M€ | 11,3 % | 4,5 % |
| 2022 | 500,8 M€ | 16,3 M€ | 43,9 M€ | 8,8 % | 3,3 % |
| 2021 | 459,8 M€ | 34,1 M€ | 58,6 M€ | 12,7 % | 7,4 % |
| 2020 | 473,9 M€ | 14,7 M€ | 40,4 M€ | 8,5 % | 3,1 % |
| 2019 | 484,4 M€ | 21,7 M€ | 46,5 M€ | 9,6 % | 4,5 % |
| 2018 | 495,6 M€ | 15,4 M€ | 29,1 M€ | 5,9 % | 3,1 % |
| 2017 | 493,6 M€ | 16,3 M€ | 33,0 M€ | 6,7 % | 3,3 % |
| 2016 | 469,3 M€ | 26,3 M€ | 47,2 M€ | 10,1 % | 5,6 % |

**Lecture :**
- Le chiffre d'affaires progresse de **+19 % entre 2016 et 2025** et de **+2,1 % entre 2024 et 2025**.
- La rentabilité a nettement remonté depuis 2022 : la marge d'EBE passe de 8,8 % à 13,4 %.
- L'entreprise est saine et peut financer un lancement.
- Attention : ce sont les comptes de la **société d'embouteillage**, pas le chiffre d'affaires mondial de la marque Volvic.

### 2.b Concurrents directs

> 🎯 **Intérêt pour le projet :** mesurer la force des concurrents directs. Ce sont des jeunes entreprises : Volvic part avec un gros avantage de taille et de distribution.

| Entreprise (SIREN) | Données | Source | Statut |
|---|---|---|---|
| **Squad Nutrition** (930 926 779), Montluçon, créée le 10/07/2024 | Pas de données financières publiées. Comptes déposés en septembre 2026 (BODACC) | API Annuaire + BODACC | ✅ |
| **VIWA France** (940 235 773), Paris, créée le 28/01/2025 | Pas de données financières publiées | API Annuaire + BODACC | ✅ |
| **D0SE** (930 852 983), Paris, créée le 08/07/2024 | Pas de données financières publiées. Comptes déposés en novembre 2025 | API Annuaire + BODACC | ✅ |
| **Humble+** (853 303 923), Paris, créée en 2019 | Pas de données financières publiques. ⚠️ SIREN identifié par le nom : vérifiez-le dans les mentions légales de humbleplus.com | API Annuaire + BODACC | ✅ / ⚠️ |

**Lecture :**
- Les concurrents directs (Squad, VIWA, D0SE) sont des **jeunes entreprises de 2024-2025, sans chiffres publics**. Ce sont de petites structures.
- Vital Proteins (Nestlé) et Vitaminwater (Coca-Cola) appartiennent à de très grands groupes. C'est la vraie menace si l'un d'eux lance une eau au collagène en France.

### 2.c BODACC : procédures collectives ✅

> 🎯 **Intérêt pour le projet :** vérifier qu'aucun concurrent n'est en difficulté et ne va disparaître du marché.
Recherche faite sur l'API officielle du BODACC, par SIREN :
https://bodacc-datadila.opendatasoft.com/explore/dataset/annonces-commerciales/

**Aucune procédure collective** (sauvegarde, redressement, liquidation) pour SEV, Squad Nutrition, VIWA France, D0SE ou Humble+.
On n'y trouve que des créations, des modifications et des dépôts de comptes. Exemple : SEV a déposé ses comptes le 21/04/2026 au greffe de Clermont-Ferrand.

### 2.d Rapport annuel du groupe Danone ✅

> 🎯 **Intérêt pour le projet :** montrer que le groupe est solide et que les eaux en Europe progressent, en particulier l'eau vitaminée Volvic.
- **Communiqué des résultats annuels 2025**, publié en février 2026 (l'aide-mémoire annonce une publication le 20/02/2026) :
  https://www.danone.com/newsroom/press-releases/full-year-results-2025.html
  - Chiffre d'affaires : **27 283 M€**, **+4,5 % à périmètre comparable** (volume et mix +2,7 %, prix +1,8 %).
  - Marge opérationnelle courante : **13,4 %** (+44 points de base).
  - Free cash flow : **2,8 Md€**.
  - Objectif 2026 : croissance des ventes de **+3 à +5 %**.
- **Aide-mémoire des résultats 2025** (PDF) :
  https://www.danone.com/content/dam/corp/global/danonecom/investors/aide-memoire/2025/aidememoiredanoneFY25.pdf
  - Ventes **Eaux en Europe** : T1 2025 = 487 M€ (+4,7 %), T2 = 591 M€ (+1,4 %), T3 = 605 M€ (+3,0 %).
  - Citation de la conférence du T3 2025 : *« strong demand for our recently launched vitamin water under the Volvic brand »* (forte demande pour l'eau vitaminée lancée récemment sous la marque Volvic).

---

## 3. Les investissements et la stratégie
*Méthode du cours : la presse (par les bases de la BU) et la presse spécialisée ; les communiqués ; les offres d'emploi, qui disent ce qu'une entreprise prépare.*

> 🎯 **Intérêt pour le projet :** montrer que le projet est cohérent avec ce que Volvic et Danone font et préparent vraiment.

### 3.a Investissements à Volvic

> 🎯 **Intérêt pour le projet :** l'outil industriel est modernisé (nouvelle ligne de production) et l'image « eau préservée » est un argument de communication. Les critiques sur les prélèvements d'eau sont un risque d'image à anticiper.

| Information | Source | Statut |
|---|---|---|
| **50 M€ d'ici 2030** à l'usine du Chancet, annoncés le 28/09/2026 par le PDG de Danone pour les 50 ans du site. L'argent ira à l'eau (projet ReUse), à la décarbonation et à la modernisation des lignes de production | ICI Auvergne : https://www.ici.fr/auvergne-rhone-alpes/puy-de-dome-63/volvic/danone-poursuit-ses-investissements-sur-le-site-des-eaux-de-volvic-6156270 | ✅ |
| Le projet **ReUse** recyclera 80 % de l'eau de lavage, soit **220 millions de litres économisés par an**, à partir de 2028. Prélèvements actuels : **plus de 2,3 milliards de litres par an**. **800 emplois directs, 1 400 avec les indirects**. La préfecture impose de baisser les prélèvements de **5 % par an**. L'association Preva juge l'effort insuffisant | France 3 Auvergne-Rhône-Alpes : https://france3-regions.franceinfo.fr/auvergne-rhone-alpes/puy-de-dome/clermont-ferrand/volvic-danone-annonce-50-millions-d-euros-d-ici-2030-pour-preserver-l-eau-des-associations-jugent-l-effort-insuffisant-3424967.html | ✅ |
| Même annonce dans la presse professionnelle | LSA : https://www.lsa-conso.fr/agro-industriel/boissons-et-liquides/eaux-minerales-a-volvic-le-pdg-de-danone-annonce-un-plan-de-50m-dinvestissements-pour-produire-mieux.43LQS3N3G5FANCQNQ6XMALFAWQ.html, et Just Drinks : https://www.just-drinks.com/news/danone-invest-volvic-site/ | 🔎 (LSA est payant : passez par Europresse via la BU) |

### 3.b Stratégie : Volvic se lance déjà dans l'hydratation fonctionnelle (information clé)

> 🎯 **Intérêt pour le projet :** c'est l'argument le plus fort du dossier. Danone a déjà validé le concept d'eau enrichie Volvic. La gamme collagène en est la suite logique.

| Information | Source | Statut |
|---|---|---|
| **Volvic Vitamin+** : lancement au Royaume-Uni et en Irlande le 06/04/2026. Eau minérale + **magnésium, vitamines B6 et C**, goûts pêche et framboise, bouteille 75 cl en plastique 100 % recyclé, **2,20 £**. Lancement fondé sur « deux ans de bonnes performances en Europe continentale ». Selon Danone, 67 % des consommateurs britanniques de boissons préfèrent obtenir des bénéfices santé par la boisson plutôt que par des compléments | Food & Drink Technology, 01/04/2026 : https://www.foodanddrinktechnology.com/news/65730/volvic-dives-into-functional-water-category/ | ✅ |
| Même lancement : selon The Grocer, la gamme a été le **premier moteur de pénétration des boissons fonctionnelles en Allemagne** sur deux ans | The Grocer : https://www.thegrocer.co.uk/news/volvic-enters-functional-water-category-with-vitamin-range/717182.article, et FoodBev : https://www.foodbev.com/news/volvic-enters-functional-hydration-with-vitamin-launch-in-uk-and-ireland | 🔎 |
| Stratégie Danone 2026 : l'hydratation saine et fonctionnelle est un **moteur de croissance**. L'eau vitaminée Volvic est un succès en Europe. Danone voit un potentiel pour de nouveaux lancements | Dairy Reporter, 13/02/2026 : https://www.dairyreporter.com/Article/2026/02/13/inside-danones-2026-strategy/ | ✅ |

**Lecture pour le projet :** « Volvic Soutien Collagène » s'inscrit dans **la stratégie réelle de Danone**, qui a déjà testé l'eau vitaminée en Europe puis l'a lancée au Royaume-Uni en 2026. C'est un argument fort pour justifier le budget.

### 3.c Marché (rappel des sources de l'analyse concurrentielle) ✅

> 🎯 **Intérêt pour le projet :** chiffrer la taille et la croissance de la demande en collagène.
- **IQVIA**, avril 2026 : compléments alimentaires à **2 Md€ (+4,7 %)**, **collagène +22 %**, gummies −5 %, Amazon +19 %.
  https://www.iqvia.com/fr-fr/locations/france/blogs/2026/04/complements-alimentaires-en-france
- **Synadiet** : marché de 3 Md€, 61 % des Français consomment des compléments, la pharmacie fait 55 % des ventes.
  https://www.synadiet.org/les-complements-alimentaires/leur-consommation/
- **Food Dive**, 06/04/2026 : Vital Proteins (Nestlé) lance une eau pétillante au collagène aux États-Unis.
  https://www.fooddive.com/news/vital-proteins-collagen-sparkling-water/816716/

### 3.d Offres d'emploi ✅

> 🎯 **Intérêt pour le projet :** une offre d'emploi révèle ce que l'entreprise prépare, ici des innovations Volvic.
- **Stage d'assistant chef de produit Volvic**, janvier 2027, à Rueil-Malmaison, publié le 18/08/2026.
  https://careers.danone.com/fr/fr/jobs/stage-assistant-chef-de-produit-volvic-janvier-2027-h-f-26644-fr-fr.html
  - Missions : suivi des panels **Circana et Kantar**, veille concurrentielle, « participation aux **innovations et rénovations produits** », suivi des performances des innovations.
  - Ce que ça montre : Volvic prépare des innovations pour 2027.

### 3.e Réglementation ✅ (à citer pour le marketing)

> 🎯 **Intérêt pour le projet :** savoir ce qu'on a le droit d'écrire sur l'étiquette et dans les publicités.
- **Règlement (UE) n° 432/2012** : seule l'allégation « la vitamine C contribue à la formation normale de collagène » est autorisée, avec des conditions de dose. Il n'existe **aucune allégation pour le collagène lui-même**.
  https://eur-lex.europa.eu/eli/reg/2012/432/oj/fra

---

## 4. L'intérêt du public : Google Trends ✅
*Méthode du cours : Google Trends, pour voir ce que les gens cherchent et quand.*

> 🎯 **Intérêt pour le projet :** prouver que la demande existe et trouver les mots que les clients utilisent, pour le nom du produit et les publicités.

Les données ont été extraites de Google Trends pour la **France, du 01/10/2021 au 30/09/2026**. Le fichier brut est dans `data/google-trends-fr-2021-2026.csv`.

**Pour refaire la recherche et faire votre capture d'écran :**
https://trends.google.fr/trends/explore?date=2021-10-01%202026-09-30&geo=FR&q=collag%C3%A8ne,kombucha,eau%20aromatis%C3%A9e,compl%C3%A9ments%20alimentaires

Indice moyen par an (100 = pic de popularité du terme le plus recherché sur la période) :

| Année | collagène | eau aromatisée | compléments alimentaires |
|---|---|---|---|
| 2021 (oct.-déc.) | 10,4 | 0,2 | 2,0 |
| 2022 | 15,0 | 0,6 | 2,4 |
| 2023 | 24,8 | 0,6 | 2,5 |
| 2024 | 27,4 | 0,5 | 2,9 |
| 2025 | 27,3 | 0,6 | 3,3 |
| 2026 (janv.-sept.) | 26,0 | 0,7 | 4,0 |

*(Le lien de recherche compare aussi « kombucha ». Cette colonne est retirée ici, elle ne sert pas pour les concurrents directs.)*

**Lecture :**
- Les recherches sur « collagène » ont été **multipliées par environ 2,6** entre fin 2021 et 2024, puis se stabilisent à un haut niveau. Le **pic** se situe en février 2025.
- « Eau aromatisée » est très peu cherché : les gens cherchent un **bénéfice** (le collagène), pas une **catégorie** de boisson. Il faut donc **mettre le bénéfice en avant**.

**Recherches associées à « collagène »** (France, 12 derniers mois) :
- Les plus fréquentes : collagène marin, meilleur collagène, collagène poudre, collagène peau, collagène visage, collagène pharmacie.
- En forte hausse : « stick collagène » (+160 %), masques au collagène, Nutri&Co collagène marin.
- Ce que ça montre : le **collagène marin domine**. Le **vegan n'est pas encore cherché** : l'indice de « collagène vegan » est proche de 0 dans le premier relevé. C'est un **créneau à éduquer**, donc il faut prévoir un budget de communication.

---

## 5. Ce que vous devez faire vous-mêmes ⛔

> 🎯 **Intérêt pour le projet :** le cours demande que chaque chiffre vienne d'une page que vous avez ouverte vous-mêmes.

Mes outils sont bloqués sur ces sites. Il faut faire ces relevés depuis votre navigateur.

1. **Wayback Machine (tarifs passés)**
   - Ouvrez les adresses suivantes :
     - https://web.archive.org/web/*/squad-nutrition.fr/*collagen*
     - https://web.archive.org/web/*/d0se.fr/produit/*
     - https://web.archive.org/web/*/volvic.fr/nos-produits/*
     - https://web.archive.org/web/*/viwa-store.fr/*
   - Choisissez une capture d'il y a 12 mois et notez le prix et la date de capture.
   - Comparez avec le prix d'aujourd'hui pour calculer l'évolution.
2. **Carrefour.fr / Leclerc Drive** : relevez à la date du jour le prix de Volvic Juicy, Volvic nature, Cristaline aromatisée et Carrefour Sensation. Faites des captures d'écran.
3. **Annuaire des entreprises / Pappers** : faites une capture de l'onglet « Données financières » de SEV (395 780 059) pour l'annexe. Les chiffres doivent être identiques au tableau 2.a.
4. **Base de presse de la BU (Europresse)** : cherchez « Volvic Vitamin+ », « Volvic 50 millions » et « eau fonctionnelle Danone » pour lire les articles LSA et Les Échos en entier.

---

## Limites
- SEV est l'entité qui **embouteille** Volvic. Son chiffre d'affaires de 558 M€ n'est pas le chiffre d'affaires mondial de la marque. Le chiffre de « 800 M€ » pour la marque Volvic, vu dans un article LSA que je n'ai pas pu ouvrir, **n'est pas retenu**.
- Les données Google Trends sont des **indices relatifs**, pas des volumes de recherche.
- Les prix marqués 🔎 viennent d'extraits de recherche. Ils varient selon le magasin et les promotions.
