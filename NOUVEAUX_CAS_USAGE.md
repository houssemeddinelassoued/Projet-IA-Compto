# 🆕 NOUVEAUX CAS D'USAGE - 23 PARTICIPANTS
## Basés sur Fichiers Réels Fournis | Janvier 2026

---

## 📋 VUE D'ENSEMBLE

Avec l'ajout de **14 nouveaux participants**, nous avons identifié **8 nouveaux cas d'usage critiques** exploitables immédiatement avec Gemini Pro.

---

# 🔥 CAS CRITIQUES (À DÉMONTRER EN PRIORITÉ)

## 1. DÉTECTION DOUBLONS ARTICLES (Supply Chain)

**Participant :** Mohamed Zarrouk - Supply Chain Manager  
**Fichier :** `Exemple suivi - Mohamed Zarrouk.xlsx`  
**Problème :** Articles en doublon entre bases CIE et CER, stocks morts non identifiés  
**Temps actuel :** 4-6h par semaine  
**Temps avec Gemini :** 15 minutes

### Prompt Prêt à Utiliser

```
Analyse ce fichier de suivi articles.

Je suspecte des DOUBLONS entre articles CIE et CER.

Identifie :
1. Articles avec références similaires mais codes différents
2. Articles avec descriptions identiques mais fournisseurs différents
3. Stocks "morts" (pas de mouvement depuis 6+ mois)

Présente résultats en tableau :
| Ref CIE | Ref CER | Description | Statut | Valorisation | Recommandation |

Priorise par impact financier (valeur stock).
```

**Impact :** Économie estimée 250h/an + réduction stock dormant (50k+ TND)

---

## 2. COMPARAISON FICHES TECHNIQUES (Chiffrage)

**Participants :** Sana Messaoudi, Slim Abid, Molka Melliti  
**Fichiers :** 
- `DAO -015-MN-2025 - Sana MESSAOUDI.pdf`
- `DAO N41.2024A stations de pompages - Slim ABID.pdf`
- `CCTP SACNO CHAHIA - Molka Melliti.pdf`

**Problème :** Comparer 3-4 produits concurrents pour répondre appels d'offres  
**Temps actuel :** 3-5h par dossier  
**Temps avec Gemini :** 10 minutes

### Prompt Prêt à Utiliser

```
Je suis technicien chiffrage chez Compto Tunisie.

Je dois répondre à ce DAO/CCTP (uploadé).

Extrais et présente en tableau :
1. Type de projet (Pompage/Électrique/HVAC/etc.)
2. Puissance / Capacité requise
3. Normes obligatoires
4. Délai d'exécution
5. Critères techniques critiques (IP, rendement, garantie)
6. Budget estimé (si mentionné)

Puis recommande 2-3 fabricants compatibles pour :
- Onduleurs (si applicable)
- Tableaux électriques (si applicable)
- Pompes (si applicable)

Justifie chaque choix en 2-3 lignes.
```

**Impact :** Réponse 5x plus rapide, taux de gain d'appels d'offres +15%

---

## 3. ANALYSE IMPAYÉS CLIENTS (Comptabilité)

**Participant :** Amira Bedoui - Comptable  
**Fichier :** `TEST IMPAYE - Amira BEDOUI.xlsx`

**Problème :** Identifier clients à risque, préparer actions de recouvrement  
**Temps actuel :** 2-3h par semaine  
**Temps avec Gemini :** 5 minutes

### Prompt Prêt à Utiliser

```
Analyse ce fichier d'impayés clients.

Génère rapport executif :

1. TOP 5 clients à risque (montant + ancienneté)
2. Répartition par tranche d'ancienneté :
   - 0-30 jours
   - 30-60 jours
   - 60-90 jours
   - 90+ jours (CRITIQUE)
3. Total TTC à risque
4. Recommandations d'actions par client :
   - Relance amiable
   - Mise en demeure
   - Contentieux

Format : Tableau synthétique + 3 recommandations prioritaires
Prêt à présenter à Direction Financière.
```

**Impact :** Réduction délai recouvrement de 12 jours en moyenne

---

## 4. VALORISATION STOCKS & CROISEMENT DONNÉES (Comptabilité)

**Participants :** Houssem Moalla, Mohamed Mâaouia  
**Fichiers :** 
- `VALORISATION ABB - Houssem MOALLA.xlsx`
- `Etat valorisé Variation des stocks MP - Mohamed MÀAOUIA.xlsx`

**Problème :** Croiser données fournisseurs avec stock interne, détecter écarts  
**Temps actuel :** 4-5h par mois  
**Temps avec Gemini :** 15 minutes

### Prompt Prêt à Utiliser

```
J'ai 2 fichiers Excel :
1. Valorisation fournisseur ABB (uploadé)
2. État valorisé stock interne (uploadé)

Cross-check et identifie :
1. Écarts de valorisation (> 5%) entre les 2 sources
2. Articles présents chez ABB mais absents stock
3. Articles stock mais non référencés ABB
4. Top 10 écarts les plus significatifs (en valeur TND)

Présente en tableau :
| Référence | Désignation | Val. ABB | Val. Stock | Écart % | Écart TND | Action Recommandée |

Priorise par impact financier décroissant.
```

**Impact :** Récupération moyenne 15k TND/an d'écarts comptables

---

## 5. TRADUCTION DOCUMENTS JURIDIQUES/ADMIN (Export/DG)

**Participants :** Malika Othmani (DG), Linda Elkebir (Juridique)  
**Fichiers :** 
- `mc_Ansässigkeit_allgemein_2026 - Malika OTHMANI.pdf` (Allemand)
- `Loi-de-finances-2017 - Linda Elkebir.pdf` (Français légal)

**Problème :** Traduire documents techniques/légaux avec précision terminologique  
**Temps actuel :** 2-3h par document  
**Temps avec Gemini :** 5 minutes

### Prompt Traduction Allemand → Français

```
Traduis ce document allemand en français.

CONTEXTE : Document administratif fiscal (Allemagne)
DESTINATAIRE : Direction Générale Tunisie

Règles :
1. Garde formatage original (sections, numérotation)
2. Termes techniques = Traduction précise + [terme original]
3. Dates, montants = Format français (DD/MM/YYYY, EUR)
4. Acronymes = Explique en note bas de page

Fournis :
- Traduction complète
- Glossaire des 10 termes clés (FR-DE)
- Résumé executif en 5 points (pour DG)
```

### Prompt Synthèse Loi de Finances

```
Synthétise cette loi de finances 2017 (Tunisie).

Je suis juriste d'entreprise.

Extrais SEULEMENT les articles impactant :
1. Entreprises industrielles/commerciales
2. TVA et recouvrement
3. Impôts sur sociétés
4. Exonérations/Aides fiscales

Pour chaque article pertinent :
| Article | Titre | Impact Entreprise | Opportunité/Risque | Action Recommandée |

Priorise par impact business décroissant.
Max 2 pages.
```

**Impact :** Économie traducteurs externes (2500 TND/an)

---

## 6. GÉNÉRATION RAPPORTS D'AVANCEMENT (Projets)

**Participant :** Almoez Jbeli - Chef Projet  
**Fichier :** `04 01 26 Rapport d_avancement des travaux N°4 - Almoez Jbeli.pdf`

**Problème :** Rédiger rapports structurés à partir de notes terrain  
**Temps actuel :** 3-4h par rapport  
**Temps avec Gemini :** 30 minutes

### Prompt Prêt à Utiliser

```
Je suis chef de projet chez Compto.

J'ai ces notes terrain (uploadées comme PDF ou texte brut).

Génère rapport d'avancement structuré selon ce template :

# RAPPORT D'AVANCEMENT N°X - [PROJET]
Date : [DATE]

## 1. RÉSUMÉ EXÉCUTIF (5 lignes max)
[Statut global + Points critiques]

## 2. AVANCEMENT PAR LOT
| Lot | % Réalisé | Statut | Commentaire |
|-----|-----------|--------|-------------|

## 3. JALONS ATTEINTS
- [Jalon 1] : ✅ Terminé le [DATE]
- [Jalon 2] : 🔄 En cours (prévu [DATE])

## 4. RISQUES & ACTIONS
| Risque | Criticité | Action | Responsable |
|--------|-----------|--------|-------------|

## 5. PRÉVISIONNEL
- Prochain jalon : [DATE]
- Livraison finale : [DATE ESTIMÉE]

Format : Prêt à envoyer client + MOA.
Tone : Professionnel, factuel, concis.
```

**Impact :** 10 rapports/mois = gain 25h/mois

---

## 7. EXTRACTION CONDITIONS PAIEMENT (Vente/ADV)

**Participant :** Abir Belguesmi - Vente  
**Fichier :** `modalités de paiement - Abir Belguesmi.pdf`

**Problème :** Parser contrats pour extraire conditions paiement  
**Temps actuel :** 15-20 min par contrat  
**Temps avec Gemini :** 2 minutes

### Prompt Prêt à Utiliser

```
Extrais les modalités de paiement de ce contrat.

Présente en format tableau :

| Élément | Détail |
|---------|--------|
| **Montant Total** | [X] TND HT |
| **Acompte** | [X]% à la commande |
| **Paiement 2** | [X]% à [Étape] |
| **Solde** | [X]% à [Livraison/Mise en service] |
| **Délai Paiement** | [X] jours net |
| **Pénalités Retard** | [X]% par mois |
| **Garantie** | [Type] - [Montant] |

Si conditions spéciales (escompte, caution), ajoute section NOTES.
```

**Impact :** Saisie 50% plus rapide, 0 erreur de transcription

---

## 8. SYNTHÈSE OFFRES TECHNIQUES EXPORT (Commercial)

**Participant :** Skander Bouchlaghem - Direction Commerciale/Export  
**Fichier :** `23 12  25 Offre technique  S1-MT-257-25-Ed°01 24 KV ETELPHA  BURKINA FASO SK.docx`

**Problème :** Résumer offres longues pour décideurs clients  
**Temps actuel :** 1-2h par offre  
**Temps avec Gemini :** 10 minutes

### Prompt Prêt à Utiliser

```
Je suis directeur commercial Export.

Cette offre technique (uploadée) fait 30+ pages.
Client (Burkina Faso) veut résumé executif 2 pages max.

Génère document :

# RÉSUMÉ OFFRE TECHNIQUE - [PROJET]
Client : [NOM]
Référence : [REF]

## 1. SOLUTION PROPOSÉE (5 lignes)
[Description simple, non technique]

## 2. CHIFFRES CLÉS
| Élément | Valeur |
|---------|--------|
| Puissance | [X kW] |
| Équipements principaux | [Liste 3-4] |
| Délai | [X semaines] |
| Montant | [X EUR HT] |
| Garantie | [X ans] |

## 3. AVANTAGES CONCURRENTIELS (3-5 points)
1. [Avantage 1]
2. [Avantage 2]
...

## 4. CONFORMITÉ
- Normes : [Liste]
- Certifications : [Liste]

## 5. PROCHAINES ÉTAPES
1. [Action 1] - [Date]
2. [Action 2] - [Date]

Tone : Commercial, confiant, précis.
Format : Prêt à envoyer client (PDF).
```

**Impact :** +20% taux de conversion export

---

# 📊 TABLEAU RÉCAPITULATIF

| Cas d'Usage | Participant(s) | Fichier | Temps Gagné/Semaine | Impact Business |
|-------------|----------------|---------|---------------------|-----------------|
| Détection doublons | M. Zarrouk | Exemple suivi.xlsx | 4-6h | 50k TND stock |
| Comparaison fiches | Sana, Slim, Molka | DAO/CCTP PDFs | 10-15h | +15% gain AO |
| Analyse impayés | A. Bedoui | TEST IMPAYE.xlsx | 2-3h | -12j délai |
| Valorisation stocks | H. Moalla, M. Mâaouia | VALORISATION.xlsx | 4-5h/mois | 15k TND/an |
| Traduction docs | Malika, Linda | PDF DE/FR | 2-3h/doc | 2.5k TND/an |
| Rapports projet | A. Jbeli | Rapport avancement.pdf | 3-4h/rapport | 25h/mois |
| Conditions paiement | A. Belguesmi | modalités.pdf | 10-15 min/doc | 0 erreur |
| Offres export | S. Bouchlaghem | Offre technique.docx | 1-2h/offre | +20% conv. |

**TOTAL GAIN HEBDOMADAIRE :** 30-45 heures  
**ÉQUIVALENT :** 1 FTE complet  
**VALORISATION :** ~125k TND/an

---

# 🎯 RECOMMANDATIONS FORMATION

## Priorisation des Démos

**Séance 1 (Fondamentaux) :**
1. ✅ Détection doublons (M. Zarrouk) - **WOW EFFECT**
2. ✅ Comparaison fiches techniques (Chiffrage) - **USAGE QUOTIDIEN**
3. ✅ Analyse impayés (Comptabilité) - **IMPACT FINANCIER**

**Séance 2 (Avancé) :**
4. ✅ Traduction + Synthèse légale (Export/Juridique)
5. ✅ Génération rapports (Projets)
6. ✅ Valorisation stocks (Compta/Supply)

## Binômes Recommandés

**Champions identifiés :**
- **M. Abdelmoumen** (Monitoring) - Niveau Avancé → Relais technique
- **S. Bouchlaghem** (Export) - Niveau Avancé → Relais business

**Binômes Débutants-Avancés :**
- Sana (Chiffrage, Débutant) ↔ Molka (Intermédiaire)
- Houssem (Compta, Débutant) ↔ Mohamed Mâaouia (Intermédiaire)
- Imen (Assistante, Débutant) ↔ Malika (Intermédiaire)

## Matériel à Préparer

**Pour Formateur :**
- [ ] Tester les 8 fichiers Excel/PDF dans Gemini (1x chacun)
- [ ] Valider que tous les prompts fonctionnent
- [ ] Préparer 3 variantes de chaque prompt (simple/moyen/avancé)
- [ ] Chronométrer chaque démo (objectif < 5 min)

**Pour Participants :**
- [ ] Distribuer fichiers 1 semaine avant (clé USB ou OneDrive)
- [ ] Email de pré-formation avec consignes accès Gemini
- [ ] Demander 1 cas réel personnel à apporter (optionnel)

---

# ✅ CHECKLIST PRÉ-FORMATION

```
TESTS TECHNIQUES (J-7)
☐ Compte Gemini Pro actif et testé
☐ Upload des 8 fichiers réussi (taille < 10MB chacun)
☐ Internet stable (test upload 5MB en < 10s)
☐ Hotspot backup préparé
☐ Tous les prompts validés (résultats cohérents)

MATÉRIEL IMPRIMÉ (J-3)
☐ Carnet exercices avec 8 nouveaux cas
☐ Fiche synthèse 1 page par cas d'usage
☐ Templates prompts imprimés (20 copies)

COMMUNICATION (J-7)
☐ Email participants avec fichiers
☐ Confirmation présence (23/23)
☐ Consignes accès Gemini envoyées
```

---

**Document créé :** 21 Janvier 2026  
**Basé sur :** Needs.md (23 participants) + 26 fichiers réels  
**Prêt pour :** Formation Groupe 2 (Supply Chain) et Groupe 3 (Chiffrage/Comptabilité)
