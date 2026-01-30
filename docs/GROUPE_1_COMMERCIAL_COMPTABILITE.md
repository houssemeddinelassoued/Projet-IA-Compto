# 🚀 GROUPE 1 : COMMERCIAL / COMPTABILITÉ / CONTRATS

> **Formation IA Générative - Gemini Pro pour Compto**
> 
> **Sessions :** Samedi 24/01/2026 et 31/01/2026 - Bureaux du Lac
> 
> **Formateur :** Houssem Eddine Lassoued

---

## 📋 Participants & Fichiers de travail

| Participant | Fichier disponible | Exercice(s) associé(s) |
|-------------|-------------------|------------------------|
| Skander BOUCHLAGHEM | `Offre technique S1-MT-257-25 24 KV ETELPHA BURKINA FASO.docx` | Ex. 2, 3 |
| Mohamed Ali Ben Tria | `Collecte des données - Mohamed Ali Ben Tria.xlsx` | Ex. 5, 6 |
| Amira BEDOUI | `TEST IMPAYE - Amira BEDOUI.xlsx` | Ex. 5, 6 |
| Malika OTHMANI | `mc_Ansässigkeit_allgemein_2026 - Malika OTHMANI.pdf` | Ex. 7 |
| Imen HAMDI (KEFI) | `CCAP SE.25.4.0011 VF - Imen KEFI.pdf` | Ex. 3, 4 |
| Salwa Jouini | `_PROJET CONTRAT ANONYME_1MWc & 2MWc (1) - Salwa Jouini.docx` | Ex. 3, 4 |
| Sarrah Othmani | `9999 - Sarrah Othmani.pdf` | Ex. 8 |
| Eya Ben Gouider | `BL2026 - Eya Ben Gouider.pdf` | Ex. 5 |
| Linda EL KEBIR | `Loi-de-finances-2017 - Linda Elkebir.pdf` | Ex. 3, 4 |
| Abir Belguesmi | `modalités de paiement - Abir Belguesmi.pdf` | Ex. 3 |

---

## Exercice 1 : Votre Première Requête Simple

**Énoncé :** Analyser rapidement une spécification technique ou un document client

**Fichier suggéré :** `Attachment H1 TGP-JE-GTPT-000-HV-SPE-0001 HVAC Specification - Direction Projets.pdf`

**Étapes :**
1. Ouvrir Gemini (gemini.google.com)
2. Cliquer "+" pour nouveau chat
3. Uploader le PDF

**Prompt :**
```
Je viens de recevoir cette spécification technique client.

Elle vient d'être uploadée.

Résume en 5 points CLÉS :
1. Qu'est-ce que c'est (industrie, usage) ?
2. Paramètres principaux (dimensions, puissance, etc.) ?
3. Normes de conformité ?
4. Délais requis ?
5. Budget estimé (si mention) ?

Réponds simplement pour non-technicien. Pas de jargon excessif.
```

**Résultat Attendu :**
```
Spec HVAC - 5 points clés
1. C'est une ventilation industrielle pour [bâtiment/usine]
2. Puissance X kW, débit Y m³/h, pression Z Pa
3. Normes ISO XXX, NF...
4. Délai 8-12 semaines
5. Budget estimé : ~50 000 EUR HT
```

**✅ Vérification :**
- [ ] Réponse claire en 5 points
- [ ] Pas trop technique
- [ ] Temps < 1 min
- [ ] Prêt à présenter au directeur

---

## Exercice 2 : Rédaction Email Commercial (Relance Devis)

**Énoncé :** Rédiger un email de relance pour un devis client export

**Contexte réel (inspiré du fichier Skander) :**
```
Client : ETELPHA (Burkina Faso)
Contact : Directeur Technique
Devis : S1-MT-257-25 pour équipement 24 KV
Statut : Offre envoyée le 23/12/2025, pas de retour
Enjeu : Marché export Afrique de l'Ouest, timing serré
```

**Prompt :**
```
Tu es Directeur Commercial chez Compto (Tunisie), spécialiste équipements électriques.

CLIENT : ETELPHA (Burkina Faso)
CONTACT : Directeur Technique
SITUATION : Offre technique S1-MT-257-25 (équipement 24 KV) envoyée il y a 32 jours,
pas de réponse. Timing serré pour projet (installation prévue Q1 2026).

Rédige email de RELANCE :
- Tone : Professionnel, courtois mais direct (pas timide)
- Longueur : 150-200 mots
- Inclus : Référence offre, enjeu timing, appel à action clair
- Format : Prêt à copier-coller dans Outlook

Terminer par : "Cordialement, [Signature Compto]"
```

**Résultat Attendu :**
```
Objet : [Suivi] Offre S1-MT-257-25 - Équipement 24 KV

Cher Monsieur,

Suite à notre offre technique S1-MT-257-25 transmise le 23/12/2025 
concernant votre projet d'équipement 24 KV, je me permets de vous 
relancer pour connaître l'état de vos réflexions.

Compte tenu du délai de fabrication et d'expédition vers le Burkina Faso, 
une validation rapide nous permettrait de garantir une livraison 
conforme à votre planning du premier trimestre 2026.

Pourriez-vous me faire part de :
- Votre décision sur l'offre présentée
- D'éventuelles questions techniques ou commerciales
- Votre calendrier de décision

Je reste à votre entière disposition pour un échange téléphonique 
si vous le souhaitez.

Cordialement,
[Signature Compto]
```

**✅ Vérification :**
- [ ] Professionnel et courtois
- [ ] Référence offre mentionnée
- [ ] Urgence timing exprimée
- [ ] Appel à action précis
- [ ] Prêt à envoyer directement

---

## Exercice 3 : Analyse Contrat / Document Juridique pour Risques

**Énoncé :** Extraire les points clés d'un contrat ou document juridique

**Fichiers suggérés :** 
- `CCAP SE.25.4.0011 VF - Imen KEFI.pdf` (Contrat)
- `_PROJET CONTRAT ANONYME_1MWc & 2MWc (1) - Salwa Jouini.docx` (Projet contrat PV)
- `Loi-de-finances-2017 - Linda Elkebir.pdf` (Texte juridique)
- `modalités de paiement - Abir Belguesmi.pdf` (Conditions commerciales)

**Prompt pour CCAP/Contrat :**
```
Je suis responsable contrats chez Compto.

J'ai uploadé un document contractuel (CCAP / Contrat projet).

ANALYSE DEMANDÉE :
1. Objet du contrat (en 2 phrases)
2. Parties impliquées
3. Montant / Budget si mentionné
4. Délais et échéances clés
5. Pénalités / Clauses de garantie
6. Points de vigilance pour Compto (risques à surveiller)

Format : Tableau synthétique + Liste des risques
```

**Prompt pour Loi de Finances (Linda) :**
```
Je suis assistante juridique chez Compto.

J'ai uploadé un extrait de la Loi de Finances.

ANALYSE DEMANDÉE :
1. Quelles dispositions concernent notre secteur (équipements électriques, énergie solaire) ?
2. Y a-t-il des avantages fiscaux pour les énergies renouvelables ?
3. Quels changements de TVA ou droits de douane ?
4. Impact potentiel sur les prix Compto ?

Format : Résumé exécutif (10 lignes) + Points d'action
```

**Résultat Attendu :**
```
ANALYSE CONTRAT - SYNTHÈSE
──────────────────────────

1. OBJET : [Description courte]

2. PARTIES :
   - Maître d'ouvrage : [...]
   - Titulaire : [...]

3. MONTANT : [X EUR HT]

4. DÉLAIS :
   - Démarrage : [Date]
   - Livraison : [Date]
   - Garantie : [Durée]

5. CLAUSES CRITIQUES :
   ⚠️ Pénalités retard : [X% par jour]
   ⚠️ Garantie décennale requise
   ⚠️ Assurance RCP minimum [X EUR]

6. RISQUES POUR COMPTO :
   🔴 [Risque 1]
   🟠 [Risque 2]
   🟢 [Point favorable]
```

**✅ Vérification :**
- [ ] Objet bien compris
- [ ] Montants et délais extraits
- [ ] Risques identifiés
- [ ] Format prêt pour réunion juridique

---

## Exercice 4 : Extraction Clauses Clés + Format Tableau

**Énoncé :** Créer un tableau récapitulatif à partir de documents contractuels

**Fichiers :** 
- `CCAP SE.25.4.0011 VF - Imen KEFI.pdf`
- `_PROJET CONTRAT ANONYME_1MWc & 2MWc (1) - Salwa Jouini.docx`

**Prompt :**
```
J'ai uploadé un ou plusieurs documents contractuels.

Crée un TABLEAU RÉCAPITULATIF pour suivi interne :

COLONNES :
- Clause / Article
- Sujet (Délai, Paiement, Garantie, Pénalité...)
- Contenu résumé
- Date / Montant associé
- Niveau de risque (Faible / Moyen / Élevé)

EXTRAIS les 10 clauses les plus importantes.

Format : Prêt à copier-coller dans Excel.
```

**Résultat Attendu :**
```
| Clause | Sujet | Résumé | Date/Montant | Risque |
|--------|-------|--------|--------------|--------|
| Art. 5 | Délai | Livraison en 8 semaines | 15/03/2026 | Moyen |
| Art. 8 | Paiement | 30% acompte, solde à réception | 45 000 EUR | Faible |
| Art. 12 | Pénalités | 0,5% par jour de retard | Max 10% | Élevé |
| Art. 15 | Garantie | 2 ans pièces et MO | 24 mois | Moyen |
[...]
```

**✅ Vérification :**
- [ ] Clauses clés identifiées
- [ ] Dates et montants extraits
- [ ] Risques évalués
- [ ] Format Excel prêt

---

## Exercice 5 : Détection Anomalies Données Comptables

**Énoncé :** Analyser un fichier Excel comptable pour trouver les erreurs avant saisie SAGE

**Fichiers réels des participants :**
- `TEST IMPAYE - Amira BEDOUI.xlsx` ⭐
- `Rapprochement EXEMPLE TEST.xlsx` ⭐
- `Collecte des données - Mohamed Ali Ben Tria.xlsx`
- `BL2026 - Eya Ben Gouider.pdf`

**Prompt (pour fichier Amira - TEST IMPAYE) :**
```
Je suis comptable chez Compto.

Voici mon fichier Excel de suivi des impayés clients.

ANALYSE DEMANDÉE :
1. Structure du fichier (colonnes, nombre de lignes)
2. Données manquantes ? (cases vides critiques)
3. Doublons ? (même client + même facture)
4. Dates aberrantes ? (futures, trop anciennes)
5. Montants suspects ? (négatifs, très élevés)
6. Incohérences format ? (dates, devises)

Pour chaque problème trouvé :
- Localisation exacte (ligne, colonne)
- Description du problème
- Correction proposée

Format : Rapport d'audit + Tableau des corrections
```

**Prompt (pour fichier Houssem - VALORISATION ABB) :**
```
Je suis chef comptable chez Compto.

Voici un fichier de valorisation stock (produits ABB).

ANALYSE DEMANDÉE :
1. Total valorisation actuelle
2. Articles avec valorisation nulle ou négative
3. Articles avec quantités aberrantes (0, négatif, très élevé)
4. Doublons de références articles
5. Prix unitaires suspects (trop bas ou trop élevé)

Propose un résumé exécutif + liste des actions correctives.
```

**Résultat Attendu :**
```
AUDIT FICHIER COMPTABLE
───────────────────────

📊 STRUCTURE :
- Lignes : 150
- Colonnes : 8
- Période : Jan-Dec 2025

✅ RÉSUMÉ QUALITÉ :
- Doublons : 2 détectés
- Données manquantes : 5 cellules
- Dates aberrantes : 1
- Montants suspects : 3

⚠️ CORRECTIONS NÉCESSAIRES :

| Ligne | Colonne | Problème | Correction |
|-------|---------|----------|------------|
| 23 | Date | 31/02/2025 | Date invalide → Vérifier |
| 45 | Montant | -1500 EUR | Négatif → Confirmer avoir |
| 67 | Client | Vide | Manquant → Compléter |
| 89 | = Ligne 12 | Doublon exact | Supprimer |

📈 RÉSULTAT : 145 lignes valides sur 150
```

**✅ Vérification :**
- [ ] Structure fichier comprise
- [ ] Tous problèmes identifiés
- [ ] Corrections localisées précisément
- [ ] Prêt pour correction et saisie SAGE

---

## Exercice 6 : Rapprochement & Croisement de Données

**Énoncé :** Croiser deux fichiers pour identifier les écarts

**Fichier suggéré :** `Rapprochement EXEMPLE TEST.xlsx`

**Prompt :**
```
Je suis comptable chez Compto.

J'ai uploadé un fichier de rapprochement bancaire.

ANALYSE DEMANDÉE :
1. Quel est le solde comptable vs solde bancaire ?
2. Quelles opérations sont en suspens (non rapprochées) ?
3. Y a-t-il des écarts inexpliqués ?
4. Quelles sont les écritures les plus anciennes non rapprochées ?

Présente sous forme de :
- Tableau de rapprochement synthétique
- Liste des écritures en suspens par ancienneté
- Recommandations d'actions

Format prêt pour présentation à la Direction Financière.
```

**Résultat Attendu :**
```
RAPPROCHEMENT BANCAIRE - SYNTHÈSE
─────────────────────────────────

SOLDES AU [DATE] :
├─ Solde Comptable : XXX,XX EUR
├─ Solde Bancaire  : XXX,XX EUR
└─ Écart           : XXX,XX EUR

OPÉRATIONS EN SUSPENS :
┌─────────┬──────────┬───────────┬─────────────┐
│ Date    │ Libellé  │ Montant   │ Ancienneté  │
├─────────┼──────────┼───────────┼─────────────┤
│ 15/11   │ Chèque X │ 1 500 EUR │ 70 jours    │
│ 22/12   │ Virement │ 3 200 EUR │ 33 jours    │
└─────────┴──────────┴───────────┴─────────────┘

ACTIONS RECOMMANDÉES :
1. Relancer le chèque X (> 60 jours)
2. Vérifier virement du 22/12 avec la banque
```

**✅ Vérification :**
- [ ] Écarts identifiés
- [ ] Ancienneté calculée
- [ ] Actions priorisées
- [ ] Prêt pour présentation

---

## Exercice 7 : Traduction Document Technique / Administratif

**Énoncé :** Traduire un document étranger en français professionnel

**Fichier réel :** `mc_Ansässigkeit_allgemein_2026 - Malika OTHMANI.pdf` (Document allemand)

**Prompt :**
```
Je suis assistante de Direction Générale chez Compto.

J'ai uploadé un document officiel en ALLEMAND.

TÂCHES :
1. Traduis intégralement en français professionnel
2. Conserve la mise en forme (titres, paragraphes, listes)
3. Explique les termes techniques ou juridiques allemands
4. Indique si c'est un formulaire à remplir et quels champs

Format : 
- Traduction complète
- Notes explicatives en [brackets]
- Résumé de l'objectif du document
```

**Prompt alternatif (pour document technique anglais) :**
```
Je suis assistante commerciale.

J'ai un document technique en anglais à traduire pour notre équipe.

TRADUIS en français :
- Garde le vocabulaire technique exact
- Conserve les unités (kW, kV, etc.)
- Format : Prêt pour diffusion interne

Ajoute un glossaire des termes techniques clés à la fin.
```

**Résultat Attendu :**
```
TRADUCTION - FORMULAIRE ALLEMAND
────────────────────────────────

TITRE ORIGINAL : Ansässigkeitsbescheinigung
TITRE FRANÇAIS : Attestation de résidence fiscale

OBJECTIF : Ce formulaire permet de certifier la résidence 
fiscale d'une entreprise pour éviter la double imposition.

[Traduction complète du document...]

CHAMPS À REMPLIR :
☐ Raison sociale de l'entreprise
☐ Numéro d'identification fiscale
☐ Adresse du siège social
☐ Signature du représentant légal

NOTES :
- "Finanzamt" = Administration fiscale
- "Steuernummer" = Numéro fiscal
```

**✅ Vérification :**
- [ ] Traduction fidèle au sens
- [ ] Termes techniques corrects
- [ ] Format conservé
- [ ] Champs à remplir identifiés

---

## Exercice 8 : Génération Contenu Marketing / Communication

**Énoncé :** Créer du contenu marketing à partir d'informations produit

**Fichier suggéré :** `9999 - Sarrah Othmani.pdf` (si contenu produit) ou contexte général

**Prompt :**
```
Tu es responsable marketing chez Compto, spécialiste équipements électriques 
et solutions photovoltaïques en Tunisie.

CONTEXTE :
- Nouveau produit : Centrale solaire clé en main pour industriels
- Cible : Directeurs d'usines et responsables énergie
- Canal : LinkedIn + Emailing

GÉNÈRE :
1. Post LinkedIn (150 mots max) - Accrocheur, professionnel
2. Objet d'email + 3 premières phrases
3. 5 arguments de vente clés (bullet points)
4. Call-to-action recommandé

Ton : Professionnel mais accessible. Pas de jargon excessif.
```

**Résultat Attendu :**
```
📱 POST LINKEDIN
────────────────
🌞 Industriels tunisiens : Et si votre facture d'électricité 
baissait de 40% ?

Chez Compto, nous installons des centrales solaires 
"clé en main" adaptées à votre consommation.

✅ Étude personnalisée gratuite
✅ Installation en 8 semaines
✅ ROI en moins de 4 ans
✅ Maintenance incluse 2 ans

👉 Contactez-nous pour un diagnostic énergétique offert.

#SolaireTunisie #TransitionEnergetique #IndustrieDurable

────────────────

📧 EMAIL
Objet : Réduisez votre facture électrique de 40% avec le solaire

Bonjour [Prénom],

Face à la hausse des coûts de l'énergie, de plus en plus 
d'industriels tunisiens font le choix du photovoltaïque. 
Compto vous accompagne de l'étude à la mise en service.
Nous avons équipé [X] sites industriels cette année.

[CTA : Demandez votre étude gratuite]
```

**✅ Vérification :**
- [ ] Message clair et accrocheur
- [ ] Arguments pertinents
- [ ] CTA présent
- [ ] Prêt à publier/envoyer

---

## 🎓 Récapitulatif des Exercices par Profil

| Profil | Exercices recommandés | Fichier à utiliser |
|--------|----------------------|-------------------|
| **Comptable** (Amira, M.A. Ben Tria) | Ex. 5, 6 | TEST IMPAYE, Rapprochement TEST |
| **Commercial** (Skander) | Ex. 2, 3 | Offre technique ETELPHA, contrats |
| **Assistante commerciale** (Imen, Salwa, Abir) | Ex. 3, 4, 7 | CCAP, Contrats, Modalités |
| **Assistante DG** (Malika) | Ex. 7 | Document allemand Ansässigkeit |
| **ADV** (Eya) | Ex. 5 | BL2026 |
| **Juridique** (Linda) | Ex. 3, 4 | Loi finances, Contrats |
| **Marketing** (Sarrah) | Ex. 8 | 9999.pdf |

---

## ✅ Checklist Post-Session

**À faire dans la séance :**
- [ ] Tester Gemini sur 1 de VOS fichiers personnels
- [ ] Identifier votre cas #1 (gain de temps le plus évident)
- [ ] Partager votre meilleur prompt avec le groupe

**À faire en 1 semaine (Session 2) :**
- [ ] 3 utilisations minimum sur cas réels / participant
- [ ] Noter les prompts qui fonctionnent bien
- [ ] Montrer les résultats
- [ ] Préparer 1 question pour la session 2

---

# 🚀 SESSION 2 : EXERCICES AVANCÉS (Niveau Intermédiaire/Avancé)

> **Objectif :** Maîtriser des cas complexes et multi-fichiers avec Gemini Pro
> 
> **Durée :** 3h (2 séances × 1h30)
> 
> **Prérequis :** Avoir complété Exercices 1-8

---

## 📝 COLLECTE DE CAS MÉTIERS - Contribution des Participants

**Important :** Avant de commencer les exercices avancés de Session 2, nous vous demandons de **partager vos expériences métier réelles** avec Gemini Pro !

### 🎯 Objectif de la collecte

Documenter les **cas d'usage concrets** que vous avez testés pour :
- Améliorer continuellement la formation
- Créer une **base de cas métiers Compto**
- Identifier les meilleures pratiques du groupe
- Adapter les exercices futurs à vos vrais besoins

### 📋 Formulaire à remplir

**👉 [Cliquez ici pour remplir le formulaire de collecte des cas métiers](https://forms.gle/DQBJgRKqRp1L6ZbYA)**

### ❓ Ce qu'on vous demande

Après avoir testé Gemini Pro en Session 1, **remplissez ce formulaire en 5-10 min** :

1. **Votre nom**
3. **Sujet de l'expérience : Cas métier testé** : Quel problème avez-vous résolu ?
4. **Lien ou Prompt que vous avez utilisé** : Partagez votre meilleur prompt (copier-coller)


**⏰ Délai:** Remplissez le formulaire **avant de commencer Session 2** (5-10 min seulement !)

---

## Exercice 9 : Analyse Trésorerie 2025 - Consolidation & Prévisions

**Énoncé :** Analyser la trésorerie de 2025 à partir de plusieurs sources (Impayés, Rapprochement Bancaire, Commandes) et proposer des recommandations

**Fichiers suggérés (croisement) :**
- `TEST IMPAYE - Amira BEDOUI.xlsx` (Impayés clients)
- `Rapprochement EXEMPLE TEST.xlsx` (Soldes et écarts)
- `Collecte des données - Mohamed Ali Ben Tria.xlsx` (Données complémentaires)
- `DATASET PV SYST - Mohamed Abdelmoumen.xlsx` (Revenus supplémentaires)

**Prompt :**
```
Je suis directeur financier chez Compto.

J'ai uploadé 4 fichiers Excel pour analyse de trésorerie 2025 :
1. Fichier impayés clients (TEST IMPAYE)
2. Rapprochement bancaire (Rapprochement EXEMPLE TEST)
3. Collecte de données complémentaires
4. Revenus supplémentaires (DATASET PV)

ANALYSE DEMANDÉE :
1. Synthèse trésorerie globale 2025 (Entrées vs Sorties)
2. Position trésorerie mois par mois (Graphe suggéré)
3. Impact des impayés sur cash-flow (Montant + Timing)
4. Engagement fournisseurs à payer (Budget vs Réel)
5. Recommandations prioritaires pour améliorer trésorerie

Format demandé :
- Tableau récapitulatif (Mois, Entrées, Sorties, Solde, Prévision)
- Synthèse des risques (3-5 points critiques)
- Actions recommandées (3-5 actions prioritaires avec timing)

Sois précis, utilise les données exactes des fichiers.
```

**Résultat Attendu :**
```
ANALYSE TRÉSORERIE 2025 - SYNTHÈSE EXÉCUTIVE
─────────────────────────────────────────────

📊 POSITION GLOBALE :
├─ Trésorerie entrante (Ventes + Autres) : 2 450 000 EUR
├─ Trésorerie sortante (Achats + Charges) : 1 980 000 EUR
├─ Solde net prévu 2025 : +470 000 EUR
└─ Solde actuel (Janvier) : [Valeur du rapport bancaire]

📈 DÉTAIL MENSUEL :
┌──────┬──────────┬──────────┬─────────┬────────────┐
│Mois  │ Entrées  │ Sorties  │ Solde   │Tendance    │
├──────┼──────────┼──────────┼─────────┼────────────┤
│Jan   │ 120 000  │  85 000  │+35 000  │ ↗ Bon      │
│Fév   │ 115 000  │  92 000  │+23 000  │ ↘ Attention|
│Mar   │ 140 000  │ 110 000  │+30 000  │ ↗ OK       │
[...]

⚠️ RISQUES IDENTIFIÉS :
🔴 CRITIQUE : Impayés clients = 180 000 EUR (7% du cash)
              → 3 clients majeurs en retard > 60 jours
🟠 MAJEUR : Engagement fournisseurs Q2 = 450 000 EUR
            → Risque de crunch trésorerie Avril-Mai
🟡 MOYEN : Saisonnalité : Creux en Novembre-Décembre

✅ ACTIONS PRIORITAIRES :
1. [URGENT] Relancer 3 clients impayés (Impact: +180k EUR)
   Timing: Semaine 1-2 janvier | Propriétaire: Direction Commerciale
   
2. [IMPORTANT] Étaler les paiements fournisseurs Q2 (Impact: -50k EUR)
   Timing: Avant 15 Février | Propriétaire: Directeur Achats
   
3. [PRÉVENTION] Accélérer encaissement Janvier (Discount 2%)
   Timing: Immédiat | Propriétaire: Direction Administrative

RECOMMANDATION GLOBALE : Trésorerie saine mais vigilance Q2 requise.
```
Exemple de Rapport Infographique par GEMINI Pro (Mode Canvas):
https://gemini.google.com/share/8c9d9fc6cafe 


**✅ Vérification :**
- [ ] Tous les fichiers utilisés dans l'analyse
- [ ] Données précises extraites (Pas d'approximations)
- [ ] Synthèse claire avec 5 points clés
- [ ] Actions recommandées avec propriétaires identifiés
- [ ] Prêt pour présentation à Direction Générale

---

## Exercice 10 : Comparaison Multi-Contrats & Risques Cumulés

**Énoncé :** Analyser 3 contrats en parallèle pour identifier les incohérences et conflits de conditions

**Fichiers suggérés :**
- `CCAP SE.25.4.0011 VF - Imen KEFI.pdf` (Contrat 1)
- `_PROJET CONTRAT ANONYME_1MWc & 2MWc - Salwa Jouini.docx` (Contrat 2)
- `modalités de paiement - Abir Belguesmi.pdf` (Contrat 3)

**Prompt :**
```
Je suis gestionnaire contrats chez Compto.

J'ai uploadé 3 documents contractuels à comparer :
1. CCAP SE.25.4.0011 VF
2. PROJET CONTRAT ANONYME (1MWc & 2MWc)
3. Modalités de paiement standard

ANALYSE COMPARATIVE DEMANDÉE :
1. Matrice de comparaison (Délais, Paiements, Garanties, Pénalités)
2. Incohérences détectées (Conflits entre les contrats)
3. Clauses contradictoires (Si présentes)
4. Risques cumulés (Exposition totale)
5. Harmonisation recommandée

Format :
- Tableau comparatif 3 colonnes (Contrat 1, 2, 3)
- Synthèse des 5 principales différences
- Recommandations d'harmonisation

Sois pointilleux sur les détails financiers et délais.
```

**Résultat Attendu :**
```
COMPARAISON MULTI-CONTRATS - MATRICE SYNTHÉTIQUE
─────────────────────────────────────────────────

┌─────────────────────┬──────────────┬──────────────┬──────────────┐
│CRITÈRE              │CCAP SE.25.4  │PROJET 1MWc   │MODALITÉS STD │
├─────────────────────┼──────────────┼──────────────┼──────────────┤
│Délai Livraison      │12 semaines   │8 semaines    │N/A (Services)│
│Paiement Acompte     │30%           │25%           │40%           │
│Solde               │70% à réception│75% à clôture │60% à clôture │
│Délai Paiement       │45 jours      │30 jours      │15 jours      │
│Garantie Pièces      │1 an          │2 ans         │1 an          │
│Garantie MO (Main Œuvre) │3 ans    │2 ans         │2 ans         │
│Pénalité Retard      │0.3%/jour     │0.5%/jour     │1%/jour       │
│Cap Pénalités        │5%            │10%           │3%            │
│Assurance RCP (Resp. Civile) │Oui  │Oui (Min 1M)  │Oui (Min 500k)│
│Frais Litige         │Partagés      │Titulaire     │Maître d'ouvrage│
└─────────────────────┴──────────────┴──────────────┴──────────────┘

⚠️ INCOHÉRENCES MAJEURES IDENTIFIÉES :

🔴 CONFLIT 1 : Pénalités de retard
   ├─ CCAP : 0,3% (Favorable Compto)
   ├─ Modalités : 1% (Défavorable)
   └─ RISQUE : Si on applique Modalités sur CCAP → Exposition +0,7% × Contrats

🔴 CONFLIT 2 : Délais de paiement
   ├─ Projet 1MWc : 30 jours (Serré)
   ├─ Modalités : 15 jours (TRÈS serré)
   └─ IMPACT : Cash-flow difficile si tous appliquent 15j

🟠 CONFLIT 3 : Garantie Pièces
   ├─ 1 an (CCAP, Modalités) vs 2 ans (Projet 1MWc)
   └─ INCOHÉRENCE : Clients reçoivent garanties différentes

📊 EXPOSITION TOTALE COMPTO :
├─ Montant engagé : 850 000 EUR
├─ Pénalités potentielles (Si retard 30j) : 12 750 EUR
├─ Assurance RCP requise : Min 1 000 000 EUR
└─ Risque réputationnel : Élevé (Garanties différentes)

✅ RECOMMANDATIONS D'HARMONISATION :

1. [URGENT] Standardiser délai paiement à 30 jours (Compromis)
   Justification: Équilibre trésorerie vs compétitivité
   Appliquer à: Tous nouveaux contrats

2. [IMPORTANT] Homogénéiser Garanties Pièces à 18 mois
   Justification: Meilleur compromis (Entre 1 et 2 ans)
   Appliquer à: Projet 1MWc (Négocier baisse à 18m)

3. [PRIORITÉ] Réviser clause Pénalités → Plafonner à 0,5%/jour, Max 5%
   Justification: Équité avec CCAP existant
   Appliquer à: Tous contrats futurs

4. [LÉGAL] Harmoniser clause Frais de Litige → "Frais à la charge du perdant"
   Justification: Standard juridique
   Appliquer à: Toute renégociation

5. [CONFORMITÉ] Augmenter Assurance RCP à 1 500 000 EUR (Pour tous)
   Justification: Couverture exposition globale
   Action: Demander devis assurance
```

**✅ Vérification :**
- [ ] Tous 3 contrats analysés en détail
- [ ] Matrice comparative complète (8-10 critères min)
- [ ] Incohérences clairement identifiées
- [ ] Exposition financière quantifiée
- [ ] Recommandations avec justifications
- [ ] Prêt pour réunion Juridi/Contrats

---

## Exercice 11 : Prévisions 2026 & Scénarios (Optimiste/Pessimiste)

**Énoncé :** Utiliser données 2025 pour projeter 2026 avec 3 scénarios

**Fichiers suggérés :**
- `Collecte des données - Mohamed Ali Ben Tria.xlsx` (Portefeuille/Données produits)
- `TEST IMPAYE - Amira BEDOUI.xlsx` (Historique impayés)
- `Rapprochement EXEMPLE TEST.xlsx` (Tendances et suivi)
- `Offre technique S1-MT-257-25 24 KV ETELPHA BURKINA FASO.docx` (Pipeline commercial)

**Prompt :**
```
Je suis responsable planning chez Compto.

Je dois préparer les prévisions 2026 pour Direction Générale.
J'ai uploadé données 2025 (Collecte données, Impayés, Rapprochement, Pipeline commercial).

PRÉVISIONS DEMANDÉES :

Scénario 1 - PESSIMISTE (Croissance -15%)
├─ Hypothèse : Crise économique, réduction budgets clients
├─ Impact : Moins de commandes, plus d'impayés
└─ KPIs : Chiffre affaires, Marge, Trésorerie

Scénario 2 - RÉALISTE (Croissance +5%)
├─ Hypothèse : Légère croissance, stabilité clients
├─ Impact : Croissance modérée, impayés stables
└─ KPIs : Chiffre affaires, Marge, Trésorerie

Scénario 3 - OPTIMISTE (Croissance +20%)
├─ Hypothèse : Marché favorable, nouveaux clients (Africa)
├─ Impact : Forte croissance, risques géopolitiques
└─ KPIs : Chiffre affaires, Marge, Trésorerie

POUR CHAQUE SCÉNARIO :
- Projection mensuelle 2026 (Revenus, Coûts, Bénéfice)
- Hypothèses claires (Justifiées par données 2025)
- Risques spécifiques à chaque scénario
- Recommandations d'action

Format :
- 3 tableaux (Un par scénario)
- Graphe comparatif des 3 scénarios
- Analyse sensibilité (Si variable X ±10%, impact sur résultat ?)

Sois réaliste dans les hypothèses, base-toi sur données réelles 2025.
```

**Résultat Attendu :**
```
PRÉVISIONS 2026 - 3 SCÉNARIOS
─────────────────────────────

HYPOTHÈSE DE BASE 2025 : CA = 2 450 000 EUR | Marge = 18%

SCÉNARIO 1 - PESSIMISTE (Croissance -15%)
┌──────┬────────────┬────────────┬──────────┬─────────────┐
│Mois  │ CA 2026    │ Coûts (-%) │ Bénéfice │ Trésorerie  │
├──────┼────────────┼────────────┼──────────┼─────────────┤
│Jan   │ 165 000    │ 135 200    │ 29 800   │ +15 200     │
│Fév   │ 162 000    │ 132 840    │ 29 160   │ +12 500     │
│Mar   │ 170 000    │ 139 400    │ 30 600   │ +18 000     │
[...]
│Total │1 820 000   │1 491 600   │328 400   │ -50 000     │
└──────┴────────────┴────────────┴──────────┴─────────────┘

HYPOTHÈSES :
- CA réduit de 15% (Baseline 2.45M → 2.08M)
- Coûts variables réduits proportionnellement (-15%)
- Coûts fixes maintenus (1.2M EUR)
- Impayés augmentent : +5% du CA (Impact trésorerie)
- Effet: Bénéfice net -45%, Trésorerie dégradée

RISQUES MAJEURS :
🔴 Trésorerie négative Nov-Déc (Saison creuse amplifiée)
🔴 Besoin de financement court terme : 100k EUR
🟠 Fournisseurs: Risque de réticence sans garanties

---

SCÉNARIO 2 - RÉALISTE (Croissance +5%)
[Tableau similaire avec CA = 2.57M EUR]

HYPOTHÈSES :
- CA croissance modérée +5% (Baseline → 2.57M EUR)
- Coûts variables +5% (Proportionnel)
- Impayés stables (~7% du CA)
- Trésorerie stable toute l'année
- Bénéfice net: +370k EUR

RECOMMANDATION : Scénario de base pour planning budgétaire

---

SCÉNARIO 3 - OPTIMISTE (Croissance +20%)
[Tableau similaire avec CA = 2.94M EUR]

HYPOTHÈSES :
- CA forte croissance +20% (Nouveaux clients Africa)
- Coûts variables +15% (Économies d'échelle)
- Impayés: -2% (Meilleurs clients)
- Risque géopolitique: 10% d'annulations potentielles
- Bénéfice net: +420k EUR

RISQUES SPÉCIFIQUES :
🔴 Flux de trésorerie: Besoin +150k EUR pour financer croissance
🟠 Ressources: Recruter 3 commerciaux supplémentaires
🟡 Géopolitique: Export Afrique = Risque politique/change

---

📊 ANALYSE COMPARÉE - 3 SCÉNARIOS
┌──────────────────────┬────────────┬────────────┬────────────┐
│KPI 2026              │PESSIMISTE  │RÉALISTE    │OPTIMISTE   │
├──────────────────────┼────────────┼────────────┼────────────┤
│CA Total (EUR)        │1 820 000   │2 572 500   │2 940 000   │
│Croissance vs 2025    │-25.7%      │+5.0%       │+20.0%      │
│Bénéfice Net (EUR)    │-180 000    │+370 000    │+420 000    │
│Marge Nette (%)       │-9.9%       │14.4%       │14.3%       │
│Trésorerie Fin Année  │-50 000     │+150 000    │+200 000    │
│Besoin Financement    │+100 000    │0           │-150 000    │
│Risque Global         │ÉLEVÉ       │MODÉRÉ      │MODÉRÉ-ÉLEV│
└──────────────────────┴────────────┴────────────┴────────────┘

✅ SENSIBILITÉ - Si Prix Vente baisse de 5% ?
├─ Pessimiste : CA → 1.729M | Perte → -280k EUR | CRITIQUE
├─ Réaliste : CA → 2.443M | Profit → +250k EUR | Acceptable
└─ Optimiste : CA → 2.793M | Profit → +340k EUR | OK

✅ SENSIBILITÉ - Si Coûts Matière +10% ?
├─ Pessimiste : Bénéfice → -250k EUR
├─ Réaliste : Bénéfice → +250k EUR (Réduction possible)
└─ Optimiste : Bénéfice → +300k EUR

🎯 RECOMMANDATIONS PAR SCÉNARIO :

PESSIMISTE :
1. Réduire coûts fixes (Délocalisation partielle ou restructuration)
2. Accélérer collecte impayés (Besoin urgent)
3. Négocier délai paiement fournisseurs (15 → 30j)

RÉALISTE (Recommandé) :
1. Maintenir trajectoire actuelle
2. Lancer 1-2 nouveaux produits (Croissance +5%)
3. Améliorer collecte impayés (Baisser de 7% → 6%)

OPTIMISTE :
1. Accélérer expansion Africa (Pipeline Burkina/Sénégal)
2. Recruter 3 commerciaux Q1 2026
3. Sécuriser trésorerie: Ligne crédit +200k EUR
4. Assurance risque change pour exports (Si >500k EUR)
```

**✅ Vérification :**
- [ ] 3 scénarios clairement définis avec hypothèses
- [ ] Tableaux mensuels complets (Entrées/Sorties/Soldes)
- [ ] Sensibilité analysée (2-3 variables clés)
- [ ] Risques spécifiques identifiés par scénario
- [ ] Recommandations d'action concrètes
- [ ] Prêt pour présentation Direction Générale

---

## Exercice 12 : Analyse Risques Commerciaux Multi-Critères

**Énoncé :** Évaluer les risques clients/fournisseurs et proposer matrice de priorisation

**Fichiers suggérés :**
- `Offre technique S1-MT-257-25 24 KV ETELPHA BURKINA FASO.docx` (Clients export)
- `TEST IMPAYE - Amira BEDOUI.xlsx` (Historique impayés)
- `Collecte des données - Mohamed Ali Ben Tria.xlsx` (Données fournisseurs)
- `CCAP SE.25.4.0011 VF - Imen KEFI.pdf` (Contrats risqués)

**Prompt :**
```
Je suis responsable risques chez Compto.

J'ai uploadé données clients (Export Africa, Impayés), fournisseurs (Collecte données), et contrats.

ANALYSE DE RISQUES DEMANDÉE :

1. RISQUES CLIENTS (Rating chaque client) :
   Critères : Montant engagé | Historique impayés | Situation géopolitique | Solidité financière
   Formule : Risk Score = (Montant × Impayé%) + Géopolitique + Solidité
   Résultat : Rating AAA à CCC

2. RISQUES FOURNISSEURS (Rating chaque fournisseur) :
   Critères : Concentration (% du besoin) | Délai livraison | Qualité | Substitution possible
   Formule : Risk Score = Concentration + Délai + (-Qualité) + (-Substitution)
   Résultat : Fournisseurs à sécuriser

3. RISQUES CONTRATS (Rating chaque contrat) :
   Critères : Clauses pénalité | Ambiguïtés juridiques | Expositions financières
   Résultat : Contrats à renégocier

4. MATRICE PRIORISATION (Impact × Probabilité) :
   Espace 2D avec quadrants : Gérer/Surveiller/Éliminer/Accepter

Format :
- Tableau scoring clients (Min 10 clients)
- Tableau scoring fournisseurs (Min 5 fournisseurs)
- Tableau scoring contrats (Min 3 contrats)
- Matrice d'impact 2D
- Top 5 actions de mitigation

Sois exhaustif dans la couverture, base-toi sur données réelles.
```

**Résultat Attendu :**
```
ANALYSE RISQUES - SCORING GLOBAL
─────────────────────────────────

┌─────────────────────────────────────────────────────────────────┐
│ SECTION 1 : RISQUES CLIENTS - RATING & SCORING                 │
└─────────────────────────────────────────────────────────────────┘

CLIENT ANALYSIS (Export + Local) :

┌──────────────┬─────────┬────────┬──────────┬────────┬───────┐
│Client        │Montant  │Impayé% │Géopolitique│Solidité│SCORE│
├──────────────┼─────────┼────────┼──────────┼────────┼───────┤
│ETELPHA BF    │250 000  │8%      │HIGH      │Moyen   │ 8.2  │
│Client X TN   │180 000  │2%      │LOW       │Très Bo │ 2.1  │
│Client Y SN   │150 000  │15%     │MEDIUM    │Faible  │ 6.8  │
│Client Z MA   │120 000  │1%      │MEDIUM    │Bon     │ 2.4  │
│[...]         │[...]    │[...]   │[...]     │[...]   │[...] │
└──────────────┴─────────┴────────┴──────────┴────────┴───────┘

RATING MAPPING :
├─ Score 1-2 : AAA (Très faible risque)
├─ Score 2-4 : AA (Faible risque)
├─ Score 4-6 : A (Risque modéré)
├─ Score 6-8 : BBB (Risque notable)
└─ Score 8-10: CCC (Risque critique)

CLIENTS EN ALERTE :
🔴 ETELPHA (Burkina Faso) : Rating BBB → Score 8.2
   Montant: 250k EUR | Impayés 8% | Géopolitique HAUTE
   Action: Réduire exposition à 150k (Limiter risque)

🟠 Client Y : Rating A → Score 6.8
   Montant: 150k EUR | Impayés 15% (Historique mauvais)
   Action: Demander acompte 50% sur prochaine commande

✅ Client X & Z : Rating AA/AAA
   Montants: 180k + 120k EUR | Impayés 1-2% | Fiables
   Action: Accorder conditions favorables, volumes plus importants

---

┌─────────────────────────────────────────────────────────────────┐
│ SECTION 2 : RISQUES FOURNISSEURS - DEPENDENCY & SUBSTITUTION   │
└─────────────────────────────────────────────────────────────────┘

┌────────────────────┬────────┬─────────┬──────────┬────────────┐
│Fournisseur (ABB)   │% Besoin│Délai Liv│Qualité   │Substitution│
├────────────────────┼────────┼─────────┼──────────┼────────────┤
│ABB Power Systems   │45%     │8 semaines│Excellent │Siemens(OK) │
│ABB Automation      │25%     │6 semaines│Bon       │Schneider(OK)│
│ABB Solar           │20%     │12 semaine│Moyen     │SMA(Délai+3s)│
│ABB Spares          │10%     │2 semaines│Bon       │Oui, multi  │
└────────────────────┴────────┴─────────┴──────────┴────────────┘

CONCENTRATION RISK :
🔴 ABB Power Systems = 45% du besoin (TOO HIGH)
   → Risque : Si ABB s'arrête, 45% des opérations bloquées
   → Action : Ajouter Siemens en fournisseur principal (Réduire à 25% ABB)

🟠 ABB Solar = Délai 12 semaines + Qualité moyenne
   → Risque : Livraisons tardives possibles
   → Action : Tester fournisseur SMA avant contrats longs

✅ ABB Spares + Automation = Bien couverts
   → Substitution facile, délais courts
   → Action : Maintenir double sourcing

---

┌─────────────────────────────────────────────────────────────────┐
│ SECTION 3 : RISQUES CONTRATS - EXPOSITION FINANCIÈRE           │
└─────────────────────────────────────────────────────────────────┘

┌──────────────────────┬──────────┬──────────┬────────────┬────────┐
│Contrat              │Montant   │Pénalité%│Cap Pénalité│Risk    │
├──────────────────────┼──────────┼──────────┼────────────┼────────┤
│CCAP SE.25.4.0011    │850 000   │0.3%     │5%          │ Faible │
│PROJET 1MWc & 2MWc   │620 000   │0.5%     │10%         │Moyen   │
│Contrat Modalités    │450 000   │1.0%     │3%          │ Élevé  │
└──────────────────────┴──────────┴──────────┴────────────┴────────┘

EXPOSITION MAXIMALE EN CAS DE RETARD 30J :
- CCAP : 850k × 0.3% × 30 = 76,500 EUR (Capped at 5% = 42,500 EUR)
- Projet 1MWc : 620k × 0.5% × 30 = 93,000 EUR (Capped at 10% = 62,000 EUR)
- Modalités : 450k × 1% × 30 = 135,000 EUR (Capped at 3% = 13,500 EUR)

TOTAL EXPOSITION PÉNALITÉS : 118,000 EUR (Cas pire = 30j retard sur tous)

---

┌─────────────────────────────────────────────────────────────────┐
│ SECTION 4 : MATRICE PRIORISATION 2×2 (Impact × Probabilité)    │
└─────────────────────────────────────────────────────────────────┘

                    IMPACT
                     ↑
        ÉLEVÉ        │
                     │  [GÉRER]      [ÉLIMINER]
                     │
                     │  ETELPHA BF   Contrat Modalités
                     │  (250k, 8%)   (Pénalités 1%)
                     │
                     │  ABB Power    Client Y
        MOYEN        │  (45% besoin) (15% impayé)
                     │
                     │  [SURVEILLER] [ACCEPTER]
                     │
                     │  ABB Solar    Client X, Z
        FAIBLE       │  (Delai 12w)  (AAA rated)
                     │
        PROBABILITÉ →
        BASSE   MOYENNE   ÉLEVÉE

---

┌─────────────────────────────────────────────────────────────────┐
│ TOP 5 ACTIONS DE MITIGATION (Priorité)                          │
└─────────────────────────────────────────────────────────────────┘

1. 🔴 [URGENT] Réduire exposition ETELPHA (250k → 150k EUR)
   Timing : Semaine 1 | Propriétaire : Dir. Commerciale
   Impact : -100k EUR exposition | Réduction risque 40%
   
2. 🔴 [URGENT] Diversifier fournisseur Power Systems (45% → 25%)
   Timing : 2 semaines | Propriétaire : Dir. Achats
   Impact : Réduction dépendance critique
   
3. 🟠 [IMPORTANT] Renégocier Contrat Modalités (Pénalités 1% → 0.5%)
   Timing : 4 semaines | Propriétaire : Juridi/Contrats
   Impact : -67,500 EUR exposition max
   
4. 🟡 [PRÉVENTION] Mettre en place Assurance Crédit export (BFCE)
   Timing : 6 semaines | Propriétaire : Dir. Admin Finance
   Impact : Couverture 80% risque impayés export
   
5. 🟡 [SURVEILLANCE] Augmenter provisionnement Client Y (Impayés 15%)
   Timing : Immédiat | Propriétaire : Comptabilité
   Impact : Couverture financière adéquate

---

📊 RÉSUMÉ RISQUES :

Exposition totale : 2.26M EUR (Clients + Contrats)
Probabilité de sinistre majeur : 15-20% annuel
Impact potentiel : -200k EUR (Sans actions)
Après mitigation : -40k EUR (Risque acceptable)
```

**✅ Vérification :**
- [ ] Tous clients et fournisseurs scorés avec formule transparente
- [ ] Matrice d'impact 2D complète avec quadrants
- [ ] Exposition financière quantifiée précisément
- [ ] 5 actions de mitigation avec propriétaires et timings
- [ ] Prêt pour présentation Comité de Risques

---

## Exercice 13 : Automatisation Reporting Mensuel avec Recommandations

**Énoncé :** Créer template de rapport mensuel automatisé exploitant toutes données disponibles

**Fichiers suggérés (tous) :**
- Tous les fichiers du groupe 1 (Utilisation synthétique)

**Prompt :**
```
Je suis responsable reporting chez Compto.

Je dois créer un TEMPLATE DE RAPPORT MENSUEL AUTOMATISÉ utilisant Gemini Pro.

STRUCTURE DU RAPPORT DEMANDÉE :

1. RÉSUMÉ EXÉCUTIF (1 page)
   - KPIs principaux (CA, Marge, Trésorerie)
   - Comparaison Mois vs Objectifs
   - Top 3 points critiques
   - Top 3 opportunités

2. SECTION TRÉSORERIE (2 pages)
   - Solde début/fin mois
   - Entrées/Sorties détaillées
   - Impayés clients (Nouvelles et anciennes)
   - Engagements fournisseurs
   - Recommandations de cash management

3. SECTION COMMERCIALE (2 pages)
   - CA par segment (Export/Local)
   - Pipeline par client majeur
   - Risques clients identifiés (Nouveaux)
   - Avancement commandes

4. SECTION FINANCE/COMPTABILITÉ (1 page)
   - Marge réelle vs budgétée
   - Anomalies détectées
   - Corrections à apporter
   - Prévisions fin d'année

5. SECTION RISQUES & ALERTES (1 page)
   - Alertes critiques
   - Actions correctives en cours
   - Suivi des risques identifiés

6. RECOMMANDATIONS (1 page)
   - Top 5 actions prioritaires pour mois suivant
   - Propriétaires et timings
   - Budget impacts

Format : Prêt à présenter Direction (Pas de jargon technique)
Include: Tableaux synthétiques, Graphes, Tendances

Comment faire ce rapport efficacement chaque mois ? (Processus proposé)
```

**Résultat Attendu :**
```
═════════════════════════════════════════════════════════════════
RAPPORT DE GESTION MENSUEL - JANVIER 2026
Compto | National Quantum
═════════════════════════════════════════════════════════════════

1️⃣ RÉSUMÉ EXÉCUTIF
───────────────────

KPIs CLÉS :
┌─────────────────────────┬────────────┬────────────┬──────────┐
│KPI                      │ Réalisé    │ Objectif   │Variance% │
├─────────────────────────┼────────────┼────────────┼──────────┤
│Chiffre Affaires (EUR)   │185 000     │180 000     │+2.8%  ✓  │
│Marge Nette (%)          │16.2%       │17.0%       │-0.8%  ⚠️  │
│Trésorerie fin mois (EUR)│120 000     │150 000     │-20% ⚠️   │
│Impayés clients (EUR)    │28 000      │25 000      │+12% ⚠️   │
└─────────────────────────┴────────────┴────────────┴──────────┘

🎯 TOP 3 CRITIQUES :
1. 🔴 Marge en baisse (-0.8%) : Hausse coûts matière ABB (+3%)
2. 🔴 Impayés en hausse (+12%) : 2 clients en retard > 30 jours
3. 🟠 Trésorerie : -20% vs objectif (Saison creuse January)

💡 TOP 3 OPPORTUNITÉS :
1. ✅ CA dépassé +2.8% : Demande forte malgré contexte
2. ✅ Nouveau client Africa approuvé : +250k EUR pipeline Q1-Q2
3. ✅ Efficacité ops : Gain productivité +5% en Janvier

───────────────────────────────────────────────────────────────

2️⃣ SECTION TRÉSORERIE & CASH
──────────────────────────────

POSITION TRÉSORERIE :
┌──────────────────────────────────────────────────────────┐
│ Solde Trésorerie Fin Janvier : 120,000 EUR              │
│ Variation vs Décembre : -30,000 EUR (-20%)              │
│ Trésorerie prévue Février : +85,000 EUR (+70%)          │
└──────────────────────────────────────────────────────────┘

DÉTAIL JANVIER :
ENTRÉES :
├─ Ventes encaissées : 195,000 EUR
├─ Autres revenus : 12,500 EUR
└─ Total ENTRÉES : 207,500 EUR

SORTIES :
├─ Paiements fournisseurs : 145,000 EUR
├─ Charges exploitations : 48,000 EUR
├─ Autres dépenses : 14,500 EUR
└─ Total SORTIES : 207,500 EUR

Résultat Net : 0 EUR (Parfait équilibre)

IMPAYÉS CLIENTS - SUIVI :
┌────────────┬─────────────┬────────┬───────────┐
│Client      │Montant      │Jours   │Status     │
├────────────┼─────────────┼────────┼───────────┤
│Client Y    │15,000 EUR   │45 j    │Relancer!! │
│Client Z    │13,000 EUR   │62 j    │CRITIQUE   │
│Autres      │-            │< 30j   │OK         │
└────────────┴─────────────┴────────┴───────────┘

⚠️ ACTION URGENTE : Relancer Client Z (62j, 13k EUR)
   Proposer : Échelonnement 3 mois ou Chèques de garantie

ENGAGEMENTS FOURNISSEURS (À PAYER FÉVRIER) :
├─ ABB : 125,000 EUR (Confirmer livraison)
├─ Siemens : 45,000 EUR (30 jours standard)
├─ Autres : 18,000 EUR
└─ Total Février : 188,000 EUR

⚠️ TRÉSORERIE FÉVRIER : Entrées (150k) - Sorties (188k) = DÉFICIT -38k EUR
   → Besoin financement court terme OU décaler paiements

─────────────────────────────────────────────────────────────

3️⃣ SECTION COMMERCIALE
───────────────────────

CA PAR SEGMENT :
┌────────────┬─────────────┬─────────────┬──────────┐
│Segment     │Janvier 2026 │Budget Année │Attente%  │
├────────────┼─────────────┼─────────────┼──────────┤
│Local TN    │125,000 EUR  │1,500,000    │8.3%   ✓  │
│Export AF   │60,000 EUR   │750,000      │8.0%   ✓  │
│Autre       │-            │-            │-         │
└────────────┴─────────────┴─────────────┴──────────┘

CA Janvier 185k EUR = Bon démarrage (En track pour objectif 2.5M)

PIPELINE COMMERCIAL :
├─ ETELPHA Burkina : 250,000 EUR (Décision attendue Février)
├─ Nouveau client Sénégal : 180,000 EUR (En négociation)
├─ Client X extension : 120,000 EUR (Devis envoyé)
└─ Autres prospects : 95,000 EUR
   TOTAL PIPELINE : 645,000 EUR (Réaliste : 60% = 387k EUR)

✅ OPPORTUNITÉ : Si ETELPHA + Sénégal signent
   → CA Février-Mars +430k EUR (Très positif)

⚠️ RISQUE : Si ETELPHA retard
   → Besoin alternative rapide pour tenir objectif

─────────────────────────────────────────────────────────────

4️⃣ SECTION FINANCE & COMPTABILITÉ
──────────────────────────────────

ANALYSE MARGE :
Marge Réelle Janvier : 16.2% (vs Objectif 17%)

Décomposition :
├─ Coût matière : 58% des ventes (Hausse ABB +3%)
├─ Main d'œuvre : 18% (Stable)
├─ Charges fixes : 8% (Stable)
└─ Marge nette : 16.2%

ACTION : Renégocier prix ABB (Impact +1% = +1.85k EUR/mois)

ANOMALIES DÉTECTÉES (Audit auto) :
🟡 3 doublons potentiels dans factures fournisseurs
   → Vérification à faire, Impact possible +2k EUR

🟡 2 factures clients non rapprochées
   → À relancer

✅ Corrections à appliquer : Ajustement +2k EUR sur Février

───────────────────────────────────────────────────────────────

5️⃣ SECTION RISQUES & ALERTES
──────────────────────────────

🔴 ALERTES CRITIQUES :

1. Client Z - Impayé 62 jours (13k EUR)
   Urgence : CRITIQUE
   Action : Appel téléphonique + Mise en demeure
   Timeline : Immédiat

2. Trésorerie Février en déficit (-38k EUR)
   Urgence : HAUTE
   Action : Demander line crédit ou décaler paiements
   Timeline : Cette semaine

🟠 RISQUES MAJEURS EN COURS :

1. ETELPHA géopolitique (Burkina Faso risque)
   Mitigation : Limiter exposition à 150k EUR max
   
2. Concentration ABB (45% besoin)
   Mitigation : Ajouter Siemens en source 25% (En cours)

─────────────────────────────────────────────────────────────

6️⃣ RECOMMANDATIONS FÉVRIER
─────────────────────────────

📋 TOP 5 ACTIONS PRIORITAIRES :

1. 🔴 [URGENT] Relancer Client Z impayé (Timeline : Lundi)
   Propriétaire : Dir. Commerciale
   Impact : Récupérer 13k EUR | Améliorer trésorerie

2. 🔴 [URGENT] Sécuriser trésorerie Février (Timeline : Mercredi)
   Propriétaire : Dir. Finance
   Action : Demander line crédit 50k EUR
   Impact : Éviter découvert

3. 🟠 [IMPORTANT] Finaliser ETELPHA (Timeline : Février)
   Propriétaire : Dir. Commerciale
   Impact : +250k EUR si signature | Valider avant Q1

4. 🟡 [SUIVI] Renégocier prix ABB (Timeline : 2 semaines)
   Propriétaire : Dir. Achats
   Impact : +1% marge = +30k EUR/an

5. 🟡 [PRÉVENTION] Tester nouveau fournisseur SMA (Timeline : 4 semaines)
   Propriétaire : Dir. Achats
   Impact : Réduire dépendance ABB Solar

───────────────────────────────────────────────────────────────

📊 PROCESSUS DE CRÉATION MENSUEL (Optimisé Gemini)

ÉTAPE 1 : Collecter données (3-4 fichiers sources)
├─ Impayés / Trésorerie / Commandes / Contrats
└─ Temps : 30 min

ÉTAPE 2 : Upload tous fichiers dans Gemini
└─ Prompt type (comme ci-dessus)

ÉTAPE 3 : Gemini génère rapport brut (15 min)

ÉTAPE 4 : Review + Complétions manuelles (45 min)
├─ Contextualiser résultats
├─ Ajouter commentaires stratégiques
└─ Préparer tableaux

ÉTAPE 5 : Mise en forme finale + Présentation (30 min)

DURÉE TOTALE : 2h (vs 6-8h actuellement en manuel)
GAIN : -75% temps | QUALITÉ : +20% (Plus exhaustif)

───────────────────────────────────────────────────────────────

Approuvé pour Distribution :
Direction Générale ✓
Direction Financière ✓
Direction Commerciale ✓

Rapport généré : 25 Janvier 2026
Prochaine échéance : 25 Février 2026
```

**✅ Vérification :**
- [ ] Rapport couvre 6 sections complètes
- [ ] Tous KPIs chiffrés précisément
- [ ] Alertes critiques clairement identifiées
- [ ] Actions recommandées avec propriétaires et timings
- [ ] Format prêt pour présentation Direction
- [ ] Processus automation claire (Gain temps >75%)
- [ ] Prêt pour mise en œuvre mensuelle automatisée

---

## 🎓 Récapitulatif des Exercices Session 2 par Profil

| Profil | Exercices Session 2 | Fichiers Principaux | Durée |
|--------|---------------------|--------------------|-------|
| **Comptable/Finance** | Ex. 9, 10, 13 | Impayés, Banque, Commandes, ABB | 1h30 |
| **Commercial** | Ex. 9, 11, 12 | Offres, Pipeline, Risques Clients | 1h30 |
| **Assistante Contrats** | Ex. 10, 12 | CCAP, Contrats, Clauses | 1h |
| **Direction Générale** | Ex. 9, 11, 13 | Trésorerie, Prévisions, Reporting | 1h30 |
| **Responsable Risques** | Ex. 12 | Tous les fichiers (Multi-critères) | 1h30 |

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

## 📊 Évaluation de la Formation

**Nous apprécions votre retour !** 

Veuillez compléter le formulaire d'évaluation pour nous aider à améliorer la formation :

👉 **[Formulaire d'évaluation Session 2 →](https://forms.gle/GQdu65u5JiwYfBYk9)**

Votre avis est précieux pour l'amélioration continue de nos formations.

---

*Formation Compto - Session 2 - National Quantum - Janvier 2026*
