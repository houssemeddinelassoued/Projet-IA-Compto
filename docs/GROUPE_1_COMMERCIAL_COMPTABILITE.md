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
| Skander BOUCHLAGHEM | `Offre technique BURKINA FASO.docx` | Ex. 2, 3 |
| Houssem MOALLA | `VALORISATION ABB.xlsx` | Ex. 5, 6 |
| Mahjoub Troudi | `Rapprochement Bancaire.xls` | Ex. 5, 6 |
| Mohamed Ali Ben Tria | `Collecte des données.xlsx` | Ex. 5, 6 |
| Amira BEDOUI | `TEST IMPAYE.xlsx` | Ex. 5, 6 |
| Malika OTHMANI | `mc_Ansässigkeit_allgemein_2026.pdf` | Ex. 7 |
| Aida BEN HASSSINE | `ETATS COMMANDES.xlsx` | Ex. 5, 6 |
| Imen HAMDI (KEFI) | `CCAP SE.25.4.0011 VF.pdf` | Ex. 3, 4 |
| Salwa Jouini | `_PROJET CONTRAT ANONYME.docx` | Ex. 3, 4 |
| Sarrah Othmani | `9999.pdf` | Ex. 8 |
| Eya Ben Gouider | `BL2026.pdf` | Ex. 5 |
| Linda EL KEBIR | `Loi-de-finances-2017.pdf` | Ex. 3, 4 |
| Abir Belguesmi | `modalités de paiement.pdf` | Ex. 3 |

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
- `VALORISATION ABB - Houssem MOALLA.xlsx` ⭐
- `TEST IMPAYE - Amira BEDOUI.xlsx` ⭐
- `Rapprochement Bançaire STE X - Mahjoub Troudi.xls`
- `ETATS COMMANDES -2023 01 11 2023 - Aida BEN HASSSINE.xlsx`
- `Collecte des donnés - Mohamed Ali Ben Tria.xlsx`
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

**Fichier suggéré :** `Rapprochement Bançaire STE X - Mahjoub Troudi.xls`

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
| **Comptable** (Houssem, Mahjoub, Amira, M.A. Ben Tria) | Ex. 5, 6 | Leurs fichiers Excel respectifs |
| **Commercial** (Skander, Abdelwaheb) | Ex. 2, 3 | Offre technique, contrats |
| **Assistante commerciale** (Imen, Salwa, Abir) | Ex. 3, 4, 7 | CCAP, Contrats, Modalités |
| **Assistante DG** (Malika) | Ex. 7 | Document allemand |
| **ADV** (Eya) | Ex. 5 | BL2026 |
| **Juridique** (Linda) | Ex. 3, 4 | Loi finances, Contrats |
| **Marketing** (Sarrah) | Ex. 8 | 9999.pdf |
| **Finance/Transit** (Aida) | Ex. 5 | États commandes |

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

*Formation Compto - National Quantum - Janvier 2026*
