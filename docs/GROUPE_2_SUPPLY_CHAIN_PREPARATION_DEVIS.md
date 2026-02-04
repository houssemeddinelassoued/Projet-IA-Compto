# 🚀 GROUPE 2 : PRÉPARATION DEVIS / SUPPLY CHAIN / CHIFFRAGE

> **Formation IA Générative - Gemini Pro pour Compto**
> 
> **Sessions :** Jeudi 05/02/2026 et Samedi 14/02/2026 - Ben Arous
> 
> **Formateur :** Houssem Eddine Lassoued

---

## 📋 Participants & Fichiers de travail (22 participants - 15 ayant répondu)

**📥 Lien Drive :** https://shorturl.at/JV2Bz (téléchargement des fichiers nécessaires)

| # | Participant | Fichier disponible | Exercice(s) associé(s) |
|---|-------------|-------------------|------------------------|
| 1 | Abderrahim MERZOUGUI | `Attachment T2 TGP-AEI-GTPT-870-CI-SPE-0003 - Direction Projets.pdf` | Ex. 1, 10 (Specs télécom) |
| 2 | Slim ABID | `DAO N41.2024A stations de pompages - Slim ABID.pdf` | Ex. 1, 5, 6, 8 |
| 3 | Mohamed ZARROUK | `Exemple suivi - Mohamed Zarrouk.xlsx` | Ex. 2, 3 (Doublons) |
| 4 | Mohamed MAAOUIA | - | Ex. 2, 3, 7 |
| 5 | Hiba MEZZI | `Manuel SUN2000 - Hiba Mezzi.pdf` | Ex. 5 (Comparaison), 9, 13 |
| 6 | Nessrine BEN NEJMA | `JAM66D45 - Nessrine Ben Nejma.pdf` | Ex. 5, 9, 13 |
| 7 | Almoez JBELI | `Rapport d_avancement N°4 - Almoez Jbeli.pdf` | Ex. 11 (Reporting) |
| 8 | Mohamed BEN MAHMOUD | `Planning Prévisionnel - Mohamed Ben Mahmoud.pdf` | Ex. 11 |
| 9 | Amenallah HADDOUDI | `18.037_DCE_CCTP-Lot-1-Electricité - Amenallah Haddoudi.pdf` | Ex. 1, 8 (Synthèse CDC) |
| 10 | Rihab ZAALOUNI | `Fiche technique relais Easergy P3U3O - Rihab Zaalouni.pdf` | Ex. 5, 9 |
| 11 | Rim OUERGHI | `CDE N° PO-L-26-013 CIE-SOGELEC - Rim OUERGHI.docx` | Ex. 2, 12 (Commandes) |
| 12 | Ala Eddine FERCHICHI | `Demande de prix CASERNE OUDHNA - Vente Compto.pdf` | Ex. 6, 12 |
| 13 | Sana MESSAOUDI | `DAO -015-MN-2025 - Sana MESSAOUDI.pdf` | Ex. 1, 5, 8 |
| 14 | Molka MELLITI | `CCTP SACNO CHAHIA ELECTRIQUE BT - Molka Melliti.pdf` | Ex. 1, 8 (Synthèse CDC) |
| 15 | Selma TOUATI | `62.2026 OFFRE TECHNIQUE MT - Selma TOUATI.docx` | Ex. 6 (Génération devis) |
| 16 | Jalel DHAOUADI ⚠️ | - (Pas de réponse) | - |
| 17 | Ismail BEJI ⚠️ | - (Pas de réponse) | - |
| 18 | Ibtissem MISSAOUI ⚠️ | - (Pas de réponse) | - |
| 19 | Nour ⚠️ | - (Pas de réponse) | - |
| 20 | Amira Trabelsi ⚠️ | - (Pas de réponse) | - |
| 21 | Houda Ben Chikh ⚠️ | - (Pas de réponse) | - |
| 22 | Riadh TOUATI ⚠️ | - (Pas de réponse) | - |
---

## Exercice 1 : Votre Première Requête Simple

**Énoncé :** Analyser rapidement une spécification technique ou un document client

**Fichier suggéré :** `DAO -015-MN-2025 - Sana MESSAOUDI.pdf` ou `CCTP SACNO CHAHIA ELECTRIQUE BT - Molka Melliti.pdf`

**Étapes :**
1. Ouvrir Gemini (gemini.google.com)
2. Cliquer "+" pour nouveau chat
3. Uploader le PDF

**Prompt :**
```
Je suis [gestionnaire supply chain / commercial] chez Compto, société d'ingénierie électrique.

Je viens de recevoir ce document technique client (PDF uploadé).

Analyse rapide demandée :
1. Type de projet et périmètre (en 1 phrase)
2. Paramètres techniques principaux (puissance, équipements clés)
3. Normes de conformité exigées
4. Délais de réalisation requis
5. Budget estimé si mentionné (sinon indiquer "Non spécifié")

Format attendu :
- Langage simple pour présentation au responsable
- Pas de jargon technique excessif
- Bullet points clairs et concis

Temps maximal : 2 minutes
```

**Résultat Attendu :**
```
DAO/CCTP - 5 points clés
1. C'est un projet [type] pour [client/site]
2. Puissance X kW, équipements Y...
3. Normes NF C 15-100, IEC...
4. Délai 8-12 semaines
5. Budget estimé : ~XX 000 EUR HT
```

**✅ Vérification :**
- [ ] Réponse claire en 5 points
- [ ] Pas trop technique
- [ ] Temps < 1 min
- [ ] Prêt à présenter au responsable

---

## Exercice 2 : Détection Anomalies Données (Excel/Fichiers)

**Énoncé :** Analyser un fichier Excel pour trouver les erreurs avant traitement

**Fichiers réels des participants :**
- `Exemple suivi - Mohamed Zarrouk.xlsx` ⭐
- `CDE N° PO-L-26-013 CIE-SOGELEC - Rim OUERGHI.docx`

**Prompt (pour fichier suivi articles) :**
```
Je suis gestionnaire supply chain chez Compto.

Voici mon fichier Excel de suivi articles/stock.

ANALYSE DEMANDÉE :
1. Structure du fichier (colonnes, nombre de lignes)
2. Données manquantes ? (cases vides critiques)
3. Doublons ? (même référence article)
4. Quantités aberrantes ? (0, négatif, très élevé)
5. Prix unitaires suspects ? (trop bas ou trop élevé)
6. Incohérences format ?

Pour chaque problème trouvé :
- Localisation exacte (ligne, colonne)
- Description du problème
- Correction proposée

Format : Rapport d'audit + Tableau des corrections
```

**Résultat Attendu :**
```
AUDIT FICHIER DONNÉES
───────────────────────

📊 STRUCTURE :
- Lignes : [N]
- Colonnes : [M]
- Période : [Dates]

✅ RÉSUMÉ QUALITÉ :
- Doublons : X détectés
- Données manquantes : Y cellules
- Valeurs aberrantes : Z

⚠️ CORRECTIONS NÉCESSAIRES :

| Ligne | Colonne | Problème | Correction |
|-------|---------|----------|------------|
| 23 | Qté | 0 unités | Vérifier stock réel |
| 45 | Prix | -150 EUR | Négatif → Corriger |
| 67 | Ref | Vide | Manquant → Compléter |

📈 RÉSULTAT : X lignes valides sur Y
```

**✅ Vérification :**
- [ ] Structure fichier comprise
- [ ] Tous problèmes identifiés
- [ ] Corrections localisées précisément
- [ ] Prêt pour correction et traitement

---

## Exercice 4 : Analyse BOM - Identification Risques

**Énoncé :** Adapter la demande pour auditer la faisabilité de fabrication et la conformité technique

**Fichier :** `BOMPRN (6) - Mehdi Dridi.pdf`

**Étapes :**
1. Upload BOMPRN PDF dans Gemini
2. Utiliser prompt ci-dessous

**Prompt :**
```
Analyse cette Nomenclature de Production (Sous-ensemble critique). Identifie :
L'Identité Technique Exacte : Que fabrique-t-on précisément ? (Specs, Références)*
L'Analyse des "Petites Fournitures" : Y a-t-il incohérence entre le matériel noble (HTA) et la quincaillerie (Visserie) pour un milieu corrosif ?*
Le Séquençage de Montage : Que nous disent les numéros d'opération (OP) sur le processus ?*
Le Kit "Consommables" : Est-il complet pour le câbleur ou manque-t-il des éléments ?"*
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

## Exercice 5 : Comparaison Fournisseurs + Recommandation

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

## Exercice 6 : Génération Devis Automatisée

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

## Exercice 7 : Dataset Excel - Nettoyage + Analyse

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

---

## Exercice 8 : Synthèse Cahier des Charges Technique

**Énoncé :** Extraire les exigences techniques clés d'un CCTP pour préparer le chiffrage

**Fichier :** `CCTP SACNO CHAHIA ELECTRIQUE BT - Molka Melliti.pdf` ou `DAO - Slim ABID.pdf`

**Prompt :**
```
Je suis technicien chiffrage chez Compto.

J'ai uploadé un Cahier des Clauses Techniques Particulières (CCTP) pour un projet électrique.

ANALYSE DEMANDÉE :
1. Objet du marché (en 2 phrases)
2. Lots concernés et périmètre
3. Exigences techniques clés (Normes, Puissances, Équipements)
4. Délais et planning exigés
5. Critères de conformité / Essais requis
6. Points de vigilance pour le chiffrage

Format : 
- Tableau récapitulatif des exigences
- Liste des équipements à chiffrer
- Alertes sur points critiques

Sois précis et utilise les données exactes du document.
```

**Résultat Attendu :**
```
SYNTHÈSE CCTP - PRÉPARATION CHIFFRAGE
──────────────────────────────────────

1. OBJET : [Description projet]
   Marché pour [type travaux], surface [X] m², localisation [Y]

2. PÉRIMÈTRE LOTS :
   - Lot 1 : [Description]
   - Lot 2 : [Description]

3. EXIGENCES TECHNIQUES :
┌────────────────────┬────────────────┬─────────────┐
│ Poste             │ Exigence       │ Norme       │
├────────────────────┼────────────────┼─────────────┤
│ TGBT              │ [Puissance]    │ NF C 15-100 │
│ Câblage           │ [Section]      │ UTE         │
│ Protection        │ [Type]         │ IEC         │
└────────────────────┴────────────────┴─────────────┘

4. DÉLAIS :
   - Démarrage : [Date]
   - Livraison : [Date]
   - Pénalités : [%/jour]

5. ÉQUIPEMENTS À CHIFFRER :
   ☐ TGBT [X] kVA
   ☐ Tableaux divisionnaires [N]
   ☐ Câblerie cuivre/alu
   ☐ Appareillage
   ☐ Main-d'œuvre installation

⚠️ POINTS VIGILANCE :
🔴 [Point critique 1]
🟠 [Point à surveiller 2]
```

**✅ Vérification :**
- [ ] Exigences techniques extraites
- [ ] Équipements à chiffrer listés
- [ ] Délais et pénalités identifiés
- [ ] Prêt pour chiffrage détaillé

---

## Exercice 9 : Traduction Document Technique

**Énoncé :** Traduire une fiche technique ou un manuel fournisseur en français professionnel

**Fichiers suggérés :** 
- `Manuel SUN2000 - Hiba Mezzi.pdf` (Anglais → Français)
- `Fiche technique relais Easergy P3U3O - Rihab Zaalouni.pdf`

**Prompt :**
```
Je suis technicien études/chiffrage.

J'ai un document technique en anglais à traduire pour notre équipe.

TRADUIS en français :
- Garde le vocabulaire technique exact
- Conserve les unités (kW, kV, A, etc.)
- Format : Prêt pour diffusion interne

Ajoute un glossaire des termes techniques clés à la fin.

RÉSUMÉ en 10 lignes des caractéristiques principales du produit.
```

**✅ Vérification :**
- [ ] Traduction fidèle au sens
- [ ] Termes techniques corrects
- [ ] Unités conservées
- [ ] Glossaire fourni

---

## Exercice 10 : Analyse Spécification Technique Télécom/Sécurité

**Énoncé :** Analyser une spécification technique complexe pour préparer une offre clé en main

**Fichier :** `Attachment T2 TGP-AEI-GTPT-870-CI-SPE-0003 - Direction Projets.pdf` (Abderrahim MERZOUGUI)

**Prompt :**
```
Je suis directeur de projets chez Compto.

J'ai uploadé une spécification technique pour système Télécom & Sécurité.

ANALYSE DEMANDÉE :
1. Résumé exécutif (5 points clés pour non-technicien)
2. Scope détaillé : Quels systèmes sont requis ?
3. Exigences techniques principales (normes, performances)
4. Équipements à fournir (liste structurée)
5. Points de vigilance pour l'offre commerciale
6. Estimation effort/complexité (Faible/Moyen/Élevé)

Format : Prêt pour réunion commerciale avec client
```

**✅ Vérification :**
- [ ] Résumé accessible aux non-techniciens
- [ ] Équipements listés clairement
- [ ] Risques identifiés
- [ ] Prêt pour offre commerciale

---

## Exercice 11 : Reporting Avancement & Planning Projet

**Énoncé :** Analyser un rapport d'avancement et un planning pour identifier les points critiques

**Fichiers :** 
- `04 01 26 Rapport d_avancement des travaux N°4 - Almoez Jbeli.pdf`
- `Planning Prévisionnel - Mohamed Ben Mahmoud.pdf`

**Prompt :**
```
Je suis chef de projet chez Compto.

J'ai uploadé un rapport d'avancement de travaux et un planning prévisionnel.

ANALYSE DEMANDÉE :
1. État d'avancement global (% réalisé)
2. Points de blocage ou retards identifiés
3. Tâches critiques sur le planning (chemin critique)
4. Écarts par rapport au planning initial
5. Risques pour les délais finaux
6. Actions correctives recommandées

GÉNÈRE :
- Synthèse exécutive (10 lignes)
- Tableau des points d'attention
- 3 recommandations prioritaires

Format : Prêt pour comité de pilotage
```

**✅ Vérification :**
- [ ] Avancement quantifié
- [ ] Retards identifiés avec causes
- [ ] Actions correctives proposées
- [ ] Prêt pour présentation client

---

## Exercice 12 : Traitement Commandes & Demandes de Prix

**Énoncé :** Analyser une commande client ou une demande de prix pour préparer la réponse

**Fichiers :** 
- `CDE N° PO-L-26-013 CIE-SOGELEC - Rim OUERGHI.docx`
- `Demande de prix CASERNE OUDHNA - Vente Compto.pdf`

**Prompt pour Commande :**
```
Je suis gestionnaire commercial chez Compto.

J'ai uploadé une commande client à traiter.

ANALYSE DEMANDÉE :
1. Informations client (Nom, Contact, Référence)
2. Articles commandés (Tableau : Référence, Désignation, Qté, Prix unitaire si mentionné)
3. Délai de livraison demandé
4. Conditions particulières
5. Vérifications à faire (stock, disponibilité, prix valide)

Format : Fiche récapitulative prête pour saisie SAGE X3
```

**Prompt pour Demande de Prix :**
```
Je suis technico-commercial chez Compto.

J'ai uploadé une demande de prix client.

ANALYSE DEMANDÉE :
1. Client et contexte du projet
2. Liste matériel demandé (Tableau structuré)
3. Spécifications techniques requises
4. Délai de réponse attendu
5. Concurrents potentiels (si mentionnés)
6. Points à clarifier avec le client

GÉNÈRE : 
- Tableau récapitulatif pour chiffrage
- Questions à poser au client
- Checklist avant envoi devis
```

**✅ Vérification :**
- [ ] Informations extraites correctement
- [ ] Tableau structuré pour traitement
- [ ] Actions identifiées
- [ ] Prêt pour saisie/chiffrage

---

## Exercice 13 : Comparaison Multi-Fiches Techniques Panneaux PV

**Énoncé :** Comparer des fiches techniques de panneaux photovoltaïques pour recommandation client

**Fichiers :** 
- `JAM66D45 605-630 LB 30 Frame - Nessrine Ben Nejma.pdf` (Panneaux JA Solar)
- `Manuel SUN2000 - Hiba Mezzi.pdf` (Onduleur Huawei)

**Prompt :**
```
Je suis chargée d'études PV chez Compto.

J'ai uploadé des fiches techniques pour projet solaire.

COMPARE et ANALYSE :
1. Caractéristiques panneaux (Puissance, Rendement, Dimensions, Poids)
2. Compatibilité avec onduleur Huawei SUN2000
3. Avantages/Inconvénients du produit
4. Recommandation pour projet 500 kWc en Tunisie

Format : Tableau comparatif + Recommandation justifiée
```

**✅ Vérification :**
- [ ] Caractéristiques extraites
- [ ] Compatibilité vérifiée
- [ ] Recommandation claire
- [ ] Prêt pour proposition client

---

## 🎓 Récapitulatif des Exercices par Profil

| Profil | Exercices recommandés | Fichiers à utiliser |
|--------|----------------------|---------------------|
| **Supply Chain** (M. Zarrouk, M. Maaouia) | Ex. 2, 3, 7 | Exemple suivi.xlsx |
| **Chiffrage/Devis** (Sana, Slim, Molka, Amenallah) | Ex. 1, 5, 6, 8 | DAO.pdf, CCTP.pdf |
| **Bureau d'études PV** (Hiba, Nessrine) | Ex. 5, 9, 13 | Manuel SUN2000.pdf, JAM66D45.pdf |
| **Gestion projets** (Almoez, M. Ben Mahmoud, Abderrahim) | Ex. 1, 10, 11 | Rapport avancement.pdf, Planning.pdf, Spec Telecom.pdf |
| **Commercial/ADV** (Rim, Ala Eddine, Selma) | Ex. 2, 6, 12 | Commande.docx, Demande prix.pdf, Offre technique.docx |
| **Technique** (Rihab) | Ex. 5, 9 | Fiche relais.pdf |

---

## ✅ Checklist Post-Session 2

**À faire dans la séance :**
- [ ] Tester Gemini sur cas avancé (Multi-fichiers)
- [ ] Générer au moins 1 rapport complet (Ex. 9, 11 ou 13)
- [ ] Mesurer gain temps réel (Avant vs Après Gemini)
- [ ] Identifier 2-3 cas à automatiser en continu

**Suite après la formation :**
- [ ] Implémenter Gemini dans processus mensuel (Ex. 13)
- [ ] Valider avec Direction les nouveaux workflows
- [ ] Documenter processus (Pour continuité)
- [ ] Adopter une Politique d'utilisation IA dans un milieu entreprise 

---


## 📊 Fichiers Disponibles - Récapitulatif Complet

| Fichier | Participant | Type | Exercice(s) |
|---------|-------------|------|-------------|
| `Exemple suivi - Mohamed Zarrouk.xlsx` | M. Zarrouk | Excel | Ex. 6 |
| `DAO -015-MN-2025 - Sana MESSAOUDI.pdf` | Sana | DAO | Ex. 7, 10 |
| `DAO N41.2024A stations de pompages - Slim ABID.pdf` | Slim | DAO | Ex. 7, 8, 10 |
| `CCTP SACNO CHAHIA ELECTRIQUE BT - Molka Melliti.pdf` | Molka | CCTP | Ex. 10 |
| `18.037_DCE_CCTP-Lot-1-Electricité - Amenallah Haddoudi.pdf` | Amenallah | CCTP | Ex. 10 |
| `Cahier des clauses techniques particulières - Amenallah Haddoudi.pdf` | Amenallah | CCTP | Ex. 10 |
| `Fiche technique relais Easergy P3U3O - Rihab Zaalouni.pdf` | Rihab | Fiche tech | Ex. 7, 11 |
| `Manuel SUN2000 - Hiba Mezzi.pdf` | Hiba | Manuel | Ex. 7, 11, 15 |
| `JAM66D45 - Nessrine Ben Nejma.pdf` | Nessrine | Fiche tech | Ex. 7, 11, 15 |
| `04 01 26 Rapport d_avancement N°4 - Almoez Jbeli.pdf` | Almoez | Rapport | Ex. 13 |
| `Planning Prévisionnel - Mohamed Ben Mahmoud.pdf` | M. Ben Mahmoud | Planning | Ex. 13 |
| `CDE N° PO-L-26-013 CIE-SOGELEC - Rim OUERGHI.docx` | Rim | Commande | Ex. 14 |
| `Demande de prix CASERNE OUDHNA - Vente Compto.pdf` | Ala Eddine | Demande prix | Ex. 14 |
| `extrimite interieur - Vente Compto.pdf` | Ala Eddine | Fiche tech | Ex. 7 |
| `62.2026 OFFRE TECHNIQUE MT - Selma TOUATI.docx` | Selma | Offre tech | Ex. 8 |
| `Attachment T2 TGP-AEI-GTPT-870-CI-SPE-0003 - Direction Projets.pdf` | Abderrahim | Spec tech | Ex. 12 |




## 📊 Évaluation de la Formation

**Nous apprécions votre retour !** 

Veuillez compléter le formulaire d'évaluation pour nous aider à améliorer la formation :

👉 **[Formulaire d'évaluation Session 2 →](https://forms.gle/GQdu65u5JiwYfBYk9)**

Votre avis est précieux pour l'amélioration continue de nos formations.

---

*Formation Compto - Groupe 2 Préparation Devis / Supply Chain - National Quantum - Février 2026*