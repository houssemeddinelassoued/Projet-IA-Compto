# 🚀 GROUPE 2 : SUPPLY CHAIN / PRÉPARATION DEVIS

## Exercice 6 : Détection Doublons Articles (NOUVEAU - Supply Chain)

**Énoncé :** Vous gérez un fichier de suivi articles avec potentiellement des doublons entre bases CIE et CER. Gemini peut les identifier automatiquement.

**Fichier :** `Exemple suivi - Mohamed Zarrouk.xlsx`

**Étapes :**
1. Uploader le fichier Excel dans Gemini
2. Utiliser le prompt de détection

**Prompt :**
```
Analyse ce fichier de suivi articles.

Je suspecte des DOUBLONS entre articles CIE et CER.

Identifie :
1. Articles avec références similaires mais codes différents
2. Articles avec descriptions identiques mais fournisseurs différents
3. Stocks "morts" (pas de mouvement depuis 6+ mois)

Présente résultats en tableau :
| Ref CIE | Ref CER | Description | Statut | Recommandation |

Priorise par impact financier (valeur stock).
```

**Résultat Attendu :**
Tableau avec 10-15 doublons potentiels, quantification financière, recommandations d'action.

**✅ Vérification :**
- [ ] Doublons identifiés avec preuves
- [ ] Valorisation financière claire
- [ ] Actions recommandées
- [ ] Temps < 5 min (vs 4h manuellement)

---

## Exercice 7 : Analyse BOM - Identification Risques

**Énoncé :** Parser BOM complexe pour identifier risques supply chain

**Fichier :** `BOMPRN (6) - Mehdi Dridi.pdf`

**Étapes :**
1. Upload BOMPRN PDF dans Gemini
2. Utiliser prompt ci-dessous

**Prompt :**
```
Je suis gestionnaire supply  .

Fichier uploadé = BOM pour projet PV 1 MWc (Tunisie, zone côtière).

ANALYSE :
1. STATISTIQUES :
   - Composants total ?
   - Catégories principales ?
   - Lead time maximum identifié ?

2. COMPOSANTS CRITIQUES :
   Lister ceux avec lead time > 8 semaines
   (= risque délai pour projet)

3. FOURNISSEURS UNIQUES :
   "Single source" = risque. Identifie-les.
   (Si un seul fournisseur pour composant critique)

4. RECOMMANDATION IMMÉDIATE :
   Qu'est-ce qu'on doit pré-commander MAINTENANT
   pour éviter retard ?

Format : Tableau structuré + Actions prioritaires
```

**Résultat Attendu :**
```
BOM ANALYSIS - 1 MWc CENTRAL PV
───────────────────────────────

STATISTIQUES
├─ Composants total : [N]
├─ Catégories : [Liste]
└─ Lead time max : [Semaines]

⚠️ CRITIQUES (Lead time > 8 sem) :
├─ [Composant A] : 12 semaines (Fournisseur X)
├─ [Composant B] : 10 semaines (Fournisseur Y)
└─ → À commander dès semaine 1

🚨 SINGLE SOURCE :
├─ [Composant D] : 1 seul fournisseur
└─ → Chercher alternative ASAP

✅ ACTIONS IMMÉDIATES (Priorité 1) :
1. PO [Composant A] semaine 1 (lead time -2 sem si rapide)
2. Contacter [Composant D] fournisseur alt
3. Confirmer délai total avec Socomec (distributeur)
```

**✅ Vérification :**
- [ ] Nombre composants correct
- [ ] Lead times identifiés
- [ ] Single source flaggés
- [ ] Actions claires & priorisées

---

## Exercice 7 : Comparaison Fournisseurs + Recommandation

**Énoncé :** Choisir le meilleur fournisseur onduleur (Coût, délai, qualité)

**Fichiers :**
- `Manuel d_utilisation, série SUN2000-(250KTL, 280KTL, 300KTL, 330KTL) - Hiba Mezzi.pdf`
- `EN-UM-SG125CX-P2-User-Manual-V12-202205 - Hamdi Jemi.pdf`

**Prompt :**
```
Je suis acheteur  .

Pour projet 500 kWc, je dois choisir onduleur.
Critères : Rendement, Robustesse, Prix, Délai.

UPLOADS :
1. Huawei SUN2000-280KTL
2. Sungrow SG125CX

COMPARE :
┌─────────────────┬──────────┬──────────┐
│ Critère         │ Huawei   │ Sungrow  │
├─────────────────┼──────────┼──────────┤
│ Rendement (%)   │          │          │
│ Protection (IP) │          │          │
│ Garantie (ans)  │          │          │
│ Coût approx/kW  │          │          │
│ Délai Tunisie   │          │          │
└─────────────────┴──────────┴──────────┘

SCORE FINAL (0-100) + Recommandation justifiée (3 points).

Qui choisir pour projet côtier (corrosion) ?
```

**Résultat Attendu :**
```
ÉTUDE COMPARATIVE - ONDULEURS
────────────────────────────

SCORES :
Huawei SUN2000-280KTL : 88/100 ⭐ RECOMMANDÉ
Sungrow SG125CX : 84/100

JUSTIFICATION :
✅ Rendement 98.6% (Huawei) vs 98.2% (Sungrow)
✅ Garantie 5 ans (égal)
✅ Meilleure réputation zone côtière (Asie tropicale)

RECOMMANDATION : Huawei SUN2000-280KTL
Raison : Rendement + Robustesse = Best ROI long-terme

PROCHAIN STEP : Demande de prix à Socomec
```

**✅ Vérification :**
- [ ] Critères comparés
- [ ] Scores numériques
- [ ] Recommandation claire
- [ ] Justification concise

---

## Exercice 8 : Génération Devis Automatisée

**Énoncé :** Créer devis client "clés en main" rapidement

**Données :**
```
CLIENT : EnergiePlus (SARL)
CONTACT : Amira Trabelsi
PROJET : Centrale PV 250 kWc
BUDGET CLIENT : Environ 200 000 EUR HT
MATIÈRE ESTIMÉE : 100 000 EUR
MAIN D'ŒUVRE : 40 000 EUR
MARGE Compto : 25%
DÉLAI SOUHAITÉ : 16 semaines
```

**Prompt :**
```
Tu es commercial.

PROJET :
- Client : EnergiePlus SARL
- Contact : Amira Trabelsi
- Scope : Centrale PV 250 kWc
- Délai : 16 semaines
- Budget approx : 200 000 EUR HT

DONNÉES COÛTS :
- Matière : 100 000 EUR HT
- Main-d'œuvre : 40 000 EUR HT
- Imprévus : 10%
- Marge Compto : 25% sur total

GÉNÈRE DEVIS :

Sections :
1. En-tête (Logo Compto, N°, Date)
2. Description scope (3-4 lignes)
3. Tableau détail coûts
4. Conditions paiement (30% acompte, 40% mid-term, 30% livraison)
5. Validité : 30 jours
6. Signature

Format : Prêt à copier dans Word/Email

Sois professionnel et convainquant. Client doit voir valeur.
```

**Résultat Attendu :**
```
────────────────────────────────────────
DEVIS COMMERCIAL - CENTRALE PV 250 KWc
────────────────────────────────────────

Destinataire :
EnergiePlus SARL
Mlle Amira Trabelsi

Devis n° : DV-2026-0024
Date : 20/01/2026
Validité : 30 jours

DESCRIPTION :
Installation complète centrale photovoltaïque 250 kWc
Terrain [Localisation]. Includes : Panneaux, Onduleurs,
Structures, Cabling, Installation, Tests & Mise en service.

COÛTS DÉTAILLÉS :
├─ Équipement PV (panneaux, onduleurs) : 100 000 EUR
├─ Travaux installation & intégration : 40 000 EUR
├─ Imprévus (10%) : 14 000 EUR
├─ Sous-Total : 154 000 EUR HT
├─ Marge Compto (20%) : 30 800 EUR HT
├─ TOTAL HT : 184 800 EUR
└─ TVA 19% : 35 112 EUR
   MONTANT TTC : 219 912 EUR

CONDITIONS :
- 30% acompte signature (65 944 EUR)
- 40% mi-parcours (87 926 EUR)
- 30% livraison (65 944 EUR)

Délai de réalisation : 16 semaines calendaires

Cordialement,
Compto Tunisie
```

**✅ Vérification :**
- [ ] Tous coûts inclus
- [ ] Tarif calculé correctement
- [ ] Conditions paiement claires
- [ ] Prêt à envoyer

---

## Exercice 9 : Dataset Excel - Nettoyage + Analyse

**Énoncé :** Analyser fichier de données PV complexe

**Fichier :** `DATASET PV SYST - Mohamed Abdelmoumen.xlsx`

**Prompt :**
```
Je suis analyste données.

Fichier uploadé = Dataset PV (Mohamed Abdelmoumen).

ANALYSE :
1. Qu'est-ce que ce dataset (structure, variables) ?
2. Combien de lignes / colonnes ?
3. Données manquantes ? Doublons ?
4. KPI principaux calculables ?
5. 3 insights intéressants (performance, anomalies, tendances)

Format : Résumé exécutif + Recommandations
```

**Résultat Attendu :**
```
DATASET PV - ANALYSE SOMMAIRE
──────────────────────────────

STRUCTURE :
- Données : [Description]
- Période : [Dates]
- Granularité : [Horaire/Journalier/Mensuel]
- Lignes : [N], Colonnes : [M]

QUALITÉ DONNÉES :
✅ Doublons : 0
✅ Données manquantes : [%]
⚠️ Valeurs aberrantes : [N]

KPI CALCULABLES :
- Production journalière moyenne (kWh)
- Rendement système (%)
- [Autres]

3 INSIGHTS :
1. [Observation 1] → Action
2. [Observation 2] → Action
3. [Observation 3] → Action
```

**✅ Vérification :**
- [ ] Structure bien comprise
- [ ] Qualité données évaluée
- [ ] KPI pertinents identifiés
- [ ] Insights exploitables
