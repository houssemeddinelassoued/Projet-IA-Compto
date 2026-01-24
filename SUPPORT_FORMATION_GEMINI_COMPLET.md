# 📚 SUPPORT DE FORMATION GEMINI PRO - FIL CONDUCTEUR COMPLET
## Compto Tunisie | Formation | Janvier-Février 2026

---

# TABLE DES MATIÈRES

1. **INTRODUCTION GÉNÉRALE** (30 min)
2. **BLOC 1 - FONDAMENTAUX GEMINI PRO** (90 min)
3. **BLOC 2 - PROMPTING AVANCÉ** (60 min)
4. **BLOC 3 - CAS MÉTIER SPÉCIALISÉS** (60 min)
5. **BLOC 4 - INTÉGRATION WORKFLOWS** (30 min)

---

# 🎯 INTRODUCTION GÉNÉRALE (30 minutes)

## Objectifs de la Session
- Comprendre ce que peut faire Gemini Pro (et ses limites)
- Découvrir les cas d'usage clés de votre métier
- Éliminer les peurs/idées reçues sur l'IA
- Créer de l'enthousiasme pour la pratique

## Slide 1 : "L'IA, C'est Quoi ?"

**Analogie Simple :**
> *"Gemini Pro est comme un collègue ultra-compétent qui a lu des millions de documents, mais qui n'a jamais d'expérience terrain. Il peut résumer, analyser, créer du contenu. À vous de vérifier et de contextualiser."*

**Trois Capacités Clés :**
1. 🧠 **Comprendre** : Lire un PDF, une image, un tableau Excel
2. ✍️ **Créer** : Rédiger, générer des formules, proposer des solutions
3. 🔄 **Itérer** : Affiner la réponse en fonction de votre feedback

**Les Limites (Importantes) :**
- ❌ Ne peut pas cliquer dans SAGE X3 directement
- ❌ Ne connaît pas les données propriétaires (avant upload)
- ❌ Peut halluciner (inventer des chiffres) → **À vérifier toujours**
- ❌ Les données uploadées dépendent de votre plan tarifaire

---

## Slide 2 : "Pourquoi MAINTENANT ?"

**Les Douleurs Identifiées dans l'entreprise Compto (23 participants) :**
| Problème | Temps/Coût | Solution Gemini |
|----------|-----------|-----------------|
| Nettoyage Excel (Compta/Supply) | 2-3h/semaine | 10 min avec prompts |
| Rédaction emails/rapports | 5-10h/semaine | 1-2h avec validation |
| Recherche dans manuels | 30-45 min/doc | 5 min (Chat PDF) |
| Extraction données | 1-2h/semaine | 15 min (Vision + Parse) |
| **Détection doublons Stock** | 4-6h/semaine | 15 min (M. Zarrouk) |
| **Comparaison fiches techniques** | 3-5h/semaine | 10 min (Chiffrage) |
| **Traduction documents** | 2-3h/semaine | 5 min (Export/DG) |
| **TOTAL POTENTIEL** | **25-40h/semaine** | **4-7h/semaine** |

**ROI Simplifié :**
- 1 Ingénieur @ 2500 TND/mois = 125 TND/heure
- Gain 12h/semaine x 125 TND = **1500 TND/semaine**
- Coûts Gemini Pro : ~15 TND/mois pour équipe
- **Payback : < 1 semaine d'implémentation**

---

## Slide 3 : "Votre Roadmap 30 Jours"

```
JOUR 1-2 : Formation (Aujourd'hui)
    ↓
JOUR 3-7 : Essayer sur 1 cas réel
    ↓
JOUR 8-14 : Première automatisation (exemple: Nettoyage Excel)
    ↓
JOUR 15-21 : Intégration dans workflow (SAGE, Email, Excel)
    ↓
JOUR 22-30 : Partage de bonnes pratiques + Champions
```

---

# 🔧 BLOC 1 : FONDAMENTAUX GEMINI PRO (90 minutes)

## I. L'Interface Gemini Pro (15 min)

### 1. Où Accéder ?

**Option 1 : Interface Web (GRATUITE)**
- 🔗 https://gemini.google.com
- Avantage : Rapide, pas de config
- Limite : Fonctionnalités réduites

**Option 2 : Gemini Pro via API (RECOMMANDÉ pour Entreprise)**
- 🔗 Google AI Studio : https://aistudio.google.com/app/apikey
- Avantage : Upload documents, Images, Intégration apps
- Tarif : À partir de 0.001 $ par request

**Option 3 : Gemini dans Google Workspace**
- 📧 Gmail, Docs, Sheets avec Gemini intégré
- Avantage : Native, continuité
- Tarif : Inclus abonnement Workspace

### 2. Démonstration : Première Utilisation

**Live Demo sur Projecteur (5 min)**

```
ÉTAPE 1 : Aller sur gemini.google.com
ÉTAPE 2 : Se connecter (compte Google)
ÉTAPE 3 : Cliquer "+ New Chat"
ÉTAPE 4 : Écrire le premier prompt :

   "Résume en 3 points clés ce qu'est un onduleur 
    photovoltaïque pour quelqu'un qui n'y connaît rien."

ÉTAPE 5 : Observer la réponse (2-3 sec)
```

**Réponse Attendue :**
```
1. Convertisseur d'électricité : Transforme le courant continu 
   des panneaux en courant alternatif pour les maisons/réseaux.

2. Cerveau du système : Optimise la production, surveille 
   les performances, communique avec les appareils.

3. Élément de sécurité : Coupe l'électricité en cas de problème, 
   protège l'installation.
```

**Action Participant (2 min) :**
- Essayer sur son propre ordi/téléphone
- Poser UNE question en rapport avec son métier
- Partager le résultat au groupe

---

## II. Structure d'une Bonne Requête - Le "PROMPT" (30 min)

### Concept : The "CRISPR Framework"

Un bon prompt = une recette. Ingrédients clés :

```
┌─────────────────────────────────────────────────┐
│  PROMPT = Contexte + Rôle + Instruction + Specs │
└─────────────────────────────────────────────────┘
```

### Formule Universelle (À mémoriser)

```
🎯 Rôle : "Tu es un expert en [domaine]"
📋 Contexte : "Je vais te donner [type de données]"
✅ Instruction : "Fais [action précise]"
📊 Format/Détails : "Réponds en [format], en [langue]"
🎁 Bonus : "Inclus [détails supplémentaires si besoin]"
```

### Exemple 1 : Rédaction Email Difficile (Commercial)

**❌ MAUVAIS PROMPT :**
```
"Rédige un email à un client qui n'a pas payé sa facture"
```
⚠️ Résultat : Trop générique, peu professionnel, sans contexte

**✅ BON PROMPT :**
```
Tu es responsable commercial de Compto, une entreprise d'électricité 
industrielle basée en Tunisie.

Client : Enercal (Centrale Photovoltaïque, contact: Jean Dupont, 
directeur de projet)

Contexte : Facture de 45 000 TND (devis n°FA-2025-0147) datant 
de 30 jours n'a pas été payée. Relation commerciale bonne 
jusque-là, mais délai dépassé.

Écris un email de relance PROFESSIONNEL, COURTOIS et FERME :
- Tone : Courtois mais clair (pas de ménagement)
- Longueur : 150-200 mots
- Inclus : N° facture, montant, actions prochaines
- Format : Signature Compto professionnelle

Évite : Menaces, ton agressif, jargon technique
```

**Résultat Attendu : Email de qualité professionnelle immédiate**

---

### Exemple 2 : Analyse Document PDF (Études/SAV)

**❌ MAUVAIS PROMPT :**
```
"Analyse ce document"
```

**✅ BON PROMPT :**
```
Je suis ingénieur SAV chez Compto. J'ai un document PDF : 
[Spécification technique SUN2000-280KTL]

Je vais te l'uploader maintenant. 

Quand tu l'auras reçu, extrais UNIQUEMENT :
1. Puissance nominale (kW)
2. Rendement maximum (%)
3. Indice de protection (IP)
4. Plage de température de fonctionnement
5. Certifications principales

Format réponse : Tableau JSON structuré.

Ne fais PAS d'interprétation personnelle si l'info n'est pas 
clairement dans le document → dis "NON TROUVÉ"
```

---

### Atelier Pratique 1 : "Écrire Votre Premier Bon Prompt" (15 min)

**Consignes :**

1. **Choisir un cas personnel** (2 min)
   - Exemple Groupe 1 : Email de confirmation de devis
   - Exemple Groupe 2 : Nettoyer un tableau Excel
   - Exemple Groupe 3 : Extraire specs d'un manuel

2. **Structurer le prompt** (5 min)
   ```
   Rôle : Je suis [mon poste]...
   Contexte : J'ai [type de document]...
   Action : Fais [ce que je demande]...
   Format : Réponds en [format]...
   ```

3. **Tester sur Gemini** (5 min)
   - Copier-coller le prompt
   - Voir le résultat
   - Ajuster si besoin (Itération)

4. **Partager au groupe** (3 min)
   - 1 personne volontaire présente son prompt et résultat
   - Feedback du groupe

---

## III. Les Quatre Modes Principaux (30 min)

### Mode 1 : TEXT ONLY - Pure Génération/Analyse

**Cas d'Usage :**
- Rédaction (emails, rapports, contrats)
- Analyse de texte (sommaire, Q&A)
- Brainstorming (idées, solutions)

**Exemple Groupe 1 - Rédaction Contrat :**
```
Prompt: "J'ai un brouillon de contrat de maintenance 
pour une centrale PV. Vérifie la complétude avec cette 
checklist : [liste 20 points clés]. Marque chaque point 
OK ou MANQUANT. Propose des améliorations en 3-5 points."

Résultat : Analyse structurée en 2 min (vs 30 min manuel)
```

---

### Mode 2 : VISION - Analyse d'Images

**Capacités :**
- 📸 Lire des graphiques, schémas, photos
- 📊 Extraire données de tableaux manuscrits/scannés
- 🔍 Détection anomalies visuelles

**Exemple Groupe 3 - Anomalie Terrain :**
```
Prompt: "Je te mets une photo d'onduleur sur le terrain.
Vérifie : 1) État général, 2) Indicateurs LED (couleurs/état),
3) Anomalies visibles, 4) Recommandation imédiate SAV."

Upload Photo + Prompt

Résultat : Diagnostic en 20 sec (vs appel SAV 30 min)
```

---

### Mode 3 : DOCUMENT UPLOAD - Chat avec PDF/Excel

**Fonctionnalité :** Uploader un PDF/Excel et poser des questions

**Exemple Groupe 2 - Analyse BOM :**
```
1. Upload : BOMPRN (6) - Mehdi Dridi.pdf
2. Prompt : "Analyse cette BOM (Bill of Materials). 
   - Combien de composants total ?
   - Identifie les pièces critiques (lead time > 8 semaines)
   - Calcule coût matière (si présent)
   - Flag anomalies (doublons, références obsolètes)"

Résultat : Analysis structurée en 1 min (vs 30 min)
```

---

### Mode 4 : MULTIMODAL - Combiner Text + Images + Documents

**Exemple Groupe 3 - Rapport de Conformité :**
```
Uploader 3 fichiers :
1. Spécification Technique Onduleur (PDF)
2. Photo Installation Terrain (JPG)
3. Norme NF C 15-100 (PDF)

Prompt : "Analyse ces 3 documents. La photo montre-t-elle 
une installation CONFORME à la norme et à la spec ? 
Identifie les écarts, suggère corrections."

Résultat : Rapport multimodal en 3 min
```

---

## IV. Démo LIVE - Cas Réel du Groupe (15 min)

### **GROUPE 1 - Commercial**

**Démo Live : "Rédiger une Offre Clés en Main en 3 min"**

**Étape 1 : Upload Document (30 sec)**
```
Upload : Spécification Technique HVAC/Telecom (PDF direction)
```

**Étape 2 : Prompt de Synthèse**
```
Tu es commercial chez Compto. J'ai des spécifications techniques 
complexes pour un projet ("TGP Telecommunication System").

Le client "Alpha Construct" (PME, budget ~50 000 EUR) demande 
une offre SIMPLE et CLAIRE en 1-2 pages.

En relisant ces specs techniques, rédige une OFFRE COMMERCIALE :
- Titre accrocheur
- 3 bénéfices clés pour le client
- Scope du projet (ce qui est inclus)
- Tarif indicatif avec justification
- Délai de livraison
- Conditions de paiement standard Compto

Tone : Professionnel, positif, sans jargon technique excessif
Format : Prêt à envoyer par email (signature en bas)
```

**Résultat Immédiat :**
```
─────────────────────────────────────────
📧 OFFRE DE SERVICE - INSTALLATION TÉLÉCOM
─────────────────────────────────────────

Cher Alpha Construct,

Merci de votre confiance. Compto propose une solution 
COMPLÈTE pour votre infrastructure de télécommunication :

✅ INCLUS :
   - Design système complet
   - Installation et mise en service
   - Formation technique (2 jours)
   - Garantie 2 ans + support

💰 TARIF : 48 500 EUR HT (vs 52 000 EUR estimé)
   Conditions : 30% acompte, 70% livraison

⏱️ DÉLAI : 12 semaines (validation contrat → installation)

Valable jusqu'au 31/01/2026.

Cordialement,
[Signature]
```

**Impact :** De 45 min de travail → 3 min + 15 min vérification

---

### **GROUPE 2 - Supply Chain / Comptabilité**

**Priorités identifiées :**
1. **Détection doublons articles** (M. Zarrouk - CRITIQUE)
2. Analyse BOM complexe (200+ lignes)
3. **Valorisation stocks & impayés** (Comptabilité)
4. Génération devis automatisée
5. Prévisions délais fournisseur
6. Nettoyage fichiers Excel chaotiques

**Démo Live : "Analyser BOMPRN et Identifier Risques"**

**Étape 1 : Upload**
```
Upload : BOMPRN (6) - Mehdi Dridi.pdf
```

**Étape 2 : Prompt d'Analyse**
```
Je suis gestionnaire de supply chain chez Compto.
Je dois analyser cette BOM pour un projet de 
1 MWc central photovoltaïque.

Analyse et fournis :
1) Nombre total composants & catégories
2) Composants critiques (lead time préoccupant)
3) Fournisseurs principaux identifiés
4) Risques potentiels (obsolescence, délai, coût)
5) Recommandations d'actions

Format : Tableau structuré + Section Recommandations
```

**Résultat :**
```
📊 ANALYSE BOM PROJET PV 1 MWc
─────────────────────────────────

STATISTIQUES GÉNÉRALES
├─ Composants Total : 287
├─ Catégories : Onduleurs (10), Racks (8), Cabling (45), etc.
├─ Fournisseurs : 24 principaux
└─ Coût Matière Estimé : 445 000 TND

⚠️ RISQUES IDENTIFIÉS
├─ [CRITIQUE] 3 composants lead time 16+ semaines
├─ [MAJEUR] Fournisseur asiatique délai + tarif volatile
└─ [MINEUR] 2 références obsolètes = remplaçants dispo

✅ RECOMMANDATIONS
1. Pré-commander onduleurs (délai +4 sem vs normal)
2. Diversifier cabling suppliers (2 sources min)
3. Remplacer références obsolètes → coût neutre
```

**Impact :** Analyse complète en 2-3 min vs 2h réunion d'équipe

---

### **GROUPE 3 - Études/SAV/Chiffrage**

**Priorités identifiées :**
1. **Comparaison fiches techniques** (Chiffrage - Sana, Slim, Molka)
2. **Extraction spécifications DAO/CCTP** (Documents appels d'offres)
3. Synthèse manuels techniques (SUN2000, Onduleurs)
4. Comparaison équipements (3-4 produits concurrents)
5. Diagnostic anomalies (Multimodal : Photo + Description)
6. Rédaction rapports SAV professionnels

**Démo Live : "Comparer Deux Onduleurs + Recommandation"**

**Étape 1 : Upload**
```
Upload PDF 1 : Manuel SUN2000-280KTL (Hiba Mezzi)
Upload PDF 2 : SG125CX User Manual (Hamdi Jemi)
```

**Étape 2 : Prompt Comparatif**
```
Je suis ingénieur études chez Compto.

Client nous demande : "Quel onduleur choisir pour 
notre centrale 500 kWc en zone côtière (corrosion saline) ?"

Uploads : Datasheets SUN2000-280KTL vs SG125CX

Compare sur critères :
1. Rendement (%)
2. Protection environnement (IP rating)
3. Garantie & support
4. Coût estimé/kW (si disponible)
5. Aptitude zone côtière (anti-corrosion)

Conclusion : Quelle marque pour zone côtière ?
Justifie en 3-5 points.
```

**Résultat :**
```
📊 ANALYSE COMPARATIVE ONDULEURS
─────────────────────────────────

┌──────────────────────┬─────────────┬──────────┐
│ Critère              │ SUN2000-280 │ SG125CX  │
├──────────────────────┼─────────────┼──────────┤
│ Rendement Max        │ 98.6%       │ 98.2%    │
│ IP Rating            │ IP65        │ IP65     │
│ Garantie             │ 5 ans       │ 5 ans    │
│ Coût/kW (estimé)     │ 850 EUR     │ 820 EUR  │
│ Anti-Corrosion       │ Standard    │ Idem     │
└──────────────────────┴─────────────┴──────────┘

✅ RECOMMANDATION : SUN2000-280KTL (Huawei)
Raisons :
1. Rendement légèrement meilleur (+0.4%) = +2 MWh/an
2. Technologie LVRT supérieure (réseau instable)
3. Support France/Tunisie meilleur
4. Plus robuste en conditions marines (garantie + réputation)

❌ CAVEAT : Vérifier gabarit/poids installation site
```

---

# 🎨 BLOC 2 : PROMPTING AVANCÉ (60 minutes)

## I. Les "Patterns" de Prompts Qui Marchent (20 min)

### Pattern 1 : Role-Playing (Rôle Expert)

**Structure :**
```
Tu es un expert en [domaine spécialisé].

Tu as :
- [N ans d'expérience]
- Travaillé sur [secteur/type de projet]
- Certifications : [liste]
- Connaissance des normes : [liste]

Client/Contexte : [Situation réelle]

Ton objectif : [Ce qu'il faut faire]

Tone : [Formel/Décontracté/Technique/Simple]
```

**Exemple Groupe 2 - Supply Chain Expert :**
```
Tu es responsable supply chain senior chez Tesla.

Tu as :
- 12 ans expérience gestion composants électroniques
- Géré supply chaînes pour 5 usines
- Expert en gestion risques / Fournisseurs multiples

Contexte : Compto cherche optimiser sa BOM pour centrale PV 1 MWc

Analyse cette BOM fournie et propose :
1. 3 optimisations de coût (sans perdre qualité)
2. 2 fournisseurs alternatifs critiques
3. Plan mitigation délais

Tone : Conseiller senior, direct et pragmatique
```

**Impact :** Réponses 10x plus pertinentes qu'une question générique

---

### Pattern 2 : Chain of Thought (Penser Étape par Étape)

**Structure :**
```
Résous ce problème ÉTAPE par ÉTAPE.

Étape 1 : Analyse [aspect 1]
Étape 2 : Analyse [aspect 2]
Étape 3 : Identifie la racine cause
Étape 4 : Propose solution

Pour chaque étape, EXPLIQUE ton raisonnement.
```

**Exemple Groupe 3 - Diagnostic Onduleur :**
```
Diagnostic : Onduleur affiche code erreur E04 + LED rouge.

Analyse ÉTAPE PAR ÉTAPE :

Étape 1 : Qu'est-ce que l'erreur E04 signifie ?
         → Cherche dans manuel SUN2000-280KTL
         → Signification : Surcharge thermique détectée

Étape 2 : Causes possibles (3-5)
         → Température ambiante > 50°C
         → Ventilation obstruée
         → Charge trop élevée (overcurrent)
         → Capteur défaillant

Étape 3 : Actions diagnostic terrain
         → Mesurer température boîtier
         → Nettoyer ventilation
         → Vérifier charge réelle vs nominal

Étape 4 : Recommandation client
         → [Proposition d'action]
```

---

### Pattern 3 : Few-Shot Learning (Montrer Exemples)

**Structure :**
```
Voici des exemples de ce que je cherche :

EXEMPLE 1 [structure attendue]
EXEMPLE 2 [structure attendue]
...

Maintenant, applique le MÊME format à :
[Nouvelle demande]
```

**Exemple Groupe 1 - Contrats Uniformes :**
```
Rédige des clauses de PÉNALITÉS pour retard 
similaires à ces 2 exemples :

EXEMPLE 1 (Contrat EDF) :
"Pour tout retard > 5 jours calendaires, 
le prestataire paiera 0.5% du montant contrat 
par jour supplémentaire, plafonné à 5% du montrat total."

EXEMPLE 2 (Contrat Siemens) :
"Retards : 1% du prix par semaine incomplet, 
max 10% après 10 semaines. Jours fériés non-comptabilisés."

Écris clause PÉNALITÉS pour contrat Compto-Client type.
Contexte : Projets électricité industrielle, délai crucial, 
client exigeant. Sois JUSTE mais PROTECTEUR de Compto.
```

---

### Pattern 4 : Meta-Prompting (Affiner avec Feedback)

**Structure :**
```
1ère Itération : Prompt initial → Réponse A
Feedback : "C'est trop [X], pas assez [Y]"
2nde Itération : Prompt raffiné → Réponse B
Feedback : "Bien ! Ajoute [Z]"
3ème Itération : Prompt final → Réponse C ✅
```

**Exemple Groupe 2 - Devis Clairs :**
```
ITER 1 :
Prompt : "Rédige un devis pour centrale PV 500 kWc"
Réponse : Trop technique, 5 pages, client perdu

FEEDBACK : "Trop complexe. Raccourcis à 1 page. 
            Utilise graphiques au lieu de chiffres bruts."

ITER 2 :
Prompt : "Rédige un devis 1 PAGE pour centrale PV 500 kWc, 
         synthétique, avec visuel au lieu de chiffres."
Réponse : Mieux ! Mais manque détails coûts

FEEDBACK : "Parfait. Ajoute breakdown coûts en tableau 
           simple (3 lignes max)."

ITER 3 :
[Final Prompt] → [Perfect Devis] ✅
```

**Atelier Pratique 2 : Itération Interactive (10 min)**

Chaque participant :
1. Pose 1ère question Gemini (simple)
2. Reçoit réponse
3. Donne feedback : "Trop court" / "Trop technique" / "Ajoute X"
4. Voir comment Gemini améliore en 2nde itération
5. Partager le résultat final

---

## II. Les Pièges Courants (& Comment les Éviter) (20 min)

### Piège 1 : L'Hallucination (Inventer des Données)

**Problème :**
```
Q: "Quel est le prix exact du SUN2000-280KTL chez Socomec ?"
R: "850 EUR HT" ← Probablement inventé !
```

**Solution :**
```
Toujours ajouter au prompt :
"Si tu n'es pas sûr de la donnée, dis CLAIREMENT : 'JE NE SAIS PAS'"

Mieux encore, ajoute source :
"Fournis la réponse + cite ta source (PDF uploadé, etc.)"
```

---

### Piège 2 : Réponse Trop Générique

**Problème :**
```
Q: "Rédige un email commercial"
R: "Cher client, nous sommes heureux... [texte générique]"
```

**Solution :**
```
Ajoute SPÉCIFICITÉS :
- Client exact : Enercal, contact Jean Dupont
- Contexte : Facture 45 000 TND, 30 jours, bonne relation
- Ton : Courtois mais ferme
- Longueur : Exactement 150-200 mots
```

**Impact :** Spécificité = Pertinence x10

---

### Piège 3 : Oublier les Limites de Gemini

**Limites Réelles :**
- ❌ Pas d'accès à internet en temps réel
- ❌ Pas de mise à jour des normes/législation post-2024
- ❌ Pas de clic automatique dans SAGE X3
- ❌ Dépend de qualité du PDF uploadé

**Mitigation :**
```
"Beaucoup de ces données changent régulièrement. 
Vérifie avec les sources offiComptolles (ex: ANME pour normes PV)"
```

---

### Piège 4 : Ignorer le Contexte Culturel/Métier

**Problème :**
```
Prompt générique : "Rédige un email professionnel"
Résultat : Format US, ton trop décontracté pour Tunisie
```

**Solution :**
```
"Je suis en Tunisie, secteur électricité industrielle.
Contexte : Client gouvernemental conservateur.
Ton : Formel, respectueux, détails techniques clairs."
```

---

## III. Ateliers Pratiques Avancés (20 min)

### Atelier 3A : Comparaison Multimodal (Groupe 3)

**Scénario :** Comparer 3 équipements complexes en 5 min

**Ressources :** 
- Manuel SUN2000-280KTL
- User Manual SG125CX
- JAM Motor Specs

**Tâche :** Créer tableau comparatif "client" (1 page)

**Instructions :**
```
1. Upload les 3 PDF
2. Utilise ce prompt :

"Tu es ingénieur avant-vente chez Compto.
Client doit choisir onduleur / moteur pour projet mixte PV+stockage.

Uploader 3 options techniques.

Crée TABLEAU COMPARATIF (format client) :
- Colonnes : [Critères clés]
- Lignes : [3 équipements]
- Recommandation finale : 1 phrase justifiée

Format : Prêt à envoyer par email"

3. Copier le résultat dans Word/Google Docs
4. Ajouter logo Compto = Devis instant prêt !
```

**Résultat :** Document professionnel en 3-4 min vs 1h

---

### Atelier 3B : Nettoyage Excel Semi-Automatisé (Groupe 2)

**Scénario :** Dossier Excel chaotique → Données propres

**Ressources :**
- DATASET PV SYST (Excel)

**Tâche :** Identifier erreurs + proposer formules

**Instructions :**
```
1. Upload Excel DATASET PV SYST
2. Prompt :

"Tu es data analyst chez Compto.
J'ai un dataset PV avec probablement des erreurs 
(doublons, valeurs manquantes, formats incohérents).

Analyse :
1) Identifie 5 erreurs principales + localisation
2) Pour chacune, propose formule Excel/Sheets de correction
3) Recommande 3 colonnes à ajouter (KPI utiles)
4) Fournis pseudo-code de nettoyage (liste de steps)

Format : Tableau + Explications."

3. Les participant testent formules sur leur Excel
4. Résultat : Dataset propre en 15 min
```

---

# 📊 BLOC 3 : CAS MÉTIER SPÉCIALISÉS (60 minutes)

## GROUPE 1 : Commercial / Comptabilité / Contrats

### Cas 1.1 : Génération Offres Clés en Main

**Défi :** Créer offres professionnelles en < 5 min (vs 45 min)

**Fichiers Utilisés :**
- Spécifications Techniques (Direction Projets PDFs)
- Modèle d'offre Compto existant

**Prompt Master :**
```
Tu es commercial senior chez Compto Tunisie, 
expert en ventes de solutions EPC (Engineering-Procurement-Construction).

CLIENT : [Nom]. Contact : [Personne]. Budget : [€/TND]
PROJET : [Description brève]
SPÉCIFICATIONS : [Document uploadé]

Crée OFFRE COMMERCIALE 1-2 pages :
- Titre accrocheur & contexte
- 3-4 bénéfices clés (pas trop tech)
- Scope détaillé (inclus/exclus)
- Tarif avec justification coût
- Conditions paiement Compto standard
- Délai réaliste
- Call-to-action clair
- Signature

Format : Prêt à envoyer par email (copier/coller direct)
Tone : Professionnel, chaleureux, décisif (pas timide)
```

**Exemple de Résultat :**
```
─────────────────────────────────────────────
OFFRE DE SERVICE - INSTALLATION COMPLÈTE
─────────────────────────────────────────────

Cher [Client],

Merci de nous faire confiance pour votre projet [X].

Compto propose une solution INTÉGRÉE, du design à la mise en service :

✅ SCOPE INCLUS :
   • Étude de conception détaillée (2 mois)
   • Fourniture équipements [spécifiques]
   • Installation et mise en service (3 mois)
   • Formation d'exploitation (2 jours)
   • Garantie 2 ans + support Y1 inclus

❌ HORS SCOPE :
   • Travaux de génie civil
   • Mise en conformité locaux

💰 INVESTISSEMENT :
   • Montant HT : [Chiffre] TND
   • Conditions : 30% signature, 40% milestones, 30% livraison
   • Validité offre : 30 jours

⏱️ CALENDRIER :
   • Démarrage : [Date]
   • Mise en service : [Date + 5 mois]

Valable jusqu'au [Date].

À bientôt,
[Signature Compto]
```

**Live Demo Participant (15 min)**
```
TEMPS 0 : Upload PDF spec technique
TEMPS 30 sec : Copier prompt + adapter client
TEMPS 2-3 min : Voir résultat généré
TEMPS 3-5 min : Petit ajustement si besoin
RÉSULTAT FINAL : Offre prête à envoyer !
```

---

### Cas 1.2 : Analyse & Synthèse Contrats

**Défi :** Valider contrat en 10 min (vs 1h relecture)

**Prompt Master :**
```
Tu es conseiller juridique spécialisé en contrats 
d'ingénierie/électricité industrielle.

CLIENT : [Nom contractuel]
CONTEXTE : [Type contrat : devis, maintenance, EPC, etc.]
CONTRAT UPLOADÉ : [PDF]

ANALYSE complète :

1. STRUCTURE : Le contrat couvre-t-il ces sections clés ?
   ☐ Définitions claires
   ☐ Scope & livrables
   ☐ Conditions de paiement
   ☐ Délais & jalons
   ☐ Responsabilités & garanties
   ☐ Risques & assurances
   ☐ Clause pénalités/bonus
   ☐ Résiliation

2. RISQUES : Identifie 5 risques pour Compto (Critique/Majeur/Mineur)

3. RECOMMANDATIONS : 
   • 3 points à modifier avant signature
   • 2 clauses à ajouter impérativement

4. SCORE GLOBAL : 1-10 (Sûr de signer ?)

Format : Tableau + Explications
```

---

### Cas 1.3 : Anomalies Factures (Excel → SAGE X3)

**Défi :** Détecter erreurs avant saisie SAGE

**Fichiers :**
- Fichier Excel factures reçues (exemple simulé)

**Prompt :**
```
Tu es contrôleur de gestion chez Compto.

J'ai un fichier Excel avec [N] factures fournisseurs 
à saisir dans SAGE X3.

ANALYSE :
1. Doublons : Existe-t-il factures dupliquées ?
   → Champs comparés : N°Facture, Fournisseur, Montant
   
2. Incohérences : 
   → Dates aberrantes (future date, date très anComptonne)
   → Montants aberrants vs commande
   → Formats dates/devises inconsistent
   
3. Données manquantes :
   → Colonnes vides ?
   → Si OUI : Propose valeur par défaut

4. Format pour SAGE :
   → Liste de corrections avant import
   → Format exact qu'attend SAGE X3
   
Format résultat : Tableau + Export prêt SAGE

Upload le fichier Excel.
```

**Résultat Type :**
```
RAPPORT CONTRÔLE FACTURES
─────────────────────────

✅ ANALYSE :
   - Total factures : 47
   - Doublons détectés : 2 (FAC-2026-001)
   - Dates aberrantes : 3 (2025, date future)
   - Montants manquants : 1

⚠️ CORRECTIONS NÉCESSAIRES :
   Ligne 5 : Supprimer doublon FAC-2026-001
   Ligne 12 : Date corrigée : 20/01/2026 → 20/01/2025
   [...]

📊 FICHIER PRÊT SAGE :
   [Télécharger Excel nettoyé]
```

**Résultat :** Pas d'erreur SAGE, saisie 3x plus rapide

---

## GROUPE 2 : Supply Chain / Préparation Devis

### Cas 2.1 : Analyse BOM + Identification Risques

**Défi :** BOM 200+ lignes → Intelligence actionnable en 2 min

**Fichiers :**
- BOMPRN (6) - Mehdi Dridi.pdf

**Prompt Master :**
```
Tu es gestionnaire supply chain senior.

PROJET : Centrale PV 1 MWc (Tunisie, zone côtière)
BOM UPLOADÉE : [BOMPRN Mehdi Dridi]

ANALYSE COMPLÈTE :

1. STATISTIQUES
   • Nombre composants total
   • Catégories majeures (onduleurs, structures, cabling, etc.)
   • Fournisseurs identifiés
   • Lead time moyen / max

2. COMPOSANTS CRITIQUES (Lead time > 8 semaines)
   → Lister avec justification
   → Recommander pré-commandes

3. RISQUES SUPPLY CHAIN
   • Fournisseur unique (single source) ?
   • Obsolescence potentielle ?
   • Disponibilité Tunisie ?
   • Coûts de transport/douanes ?

4. OPTIMISATIONS COÛT/DÉLAI (3-5 suggestions)
   • Alternatives produits (même fonction, moins cher)
   • Consolidation fournisseurs
   • Batch ordering pour réductions volume

5. PLAN D'ACTION (Priorité)
   Semaine 1 : [Actions]
   Semaine 2-3 : [Actions]
   Semaine 4-8 : [Actions]

Format : Tableau critères + Narratif recommandations
```

**Résultat Attendu :**
```
BOM ANALYSIS - CENTRALE 1 MWc
─────────────────────────────

STATISTIQUES
├─ Composants : 287 lignes
├─ Catégories : 8 (Onduleurs, Structures, Cabling...)
├─ Fournisseurs : 24
└─ Lead time max : 16 semaines

⚠️ CRITIQUES (16+ semaines)
├─ [2 refs onduleur] → Pré-commander immédiatement
├─ [1 ref trafo] → Lead time Chine +4 semaines
└─ Total impact délai : 4 semaines si non-action

✅ RECOMMANDATIONS
1. [Action 1] : Impact délai -2 semaines
2. [Action 2] : Économie 8 000 TND
3. [Action 3] : Améliorer diversification fournisseur

🚀 PLAN 30 JOURS
[Calendrier détaillé]
```

---

### Cas 2.2 : Génération Devis "Client-Ready"

**Défi :** Devis précis & compétitif en 15 min (vs 2h)

**Données :**
- BOM + Coûts matière
- Main-d'œuvre standard Compto
- Normes devis Compto

**Prompt :**
```
Tu es commercial en charge devis chez Compto.

CLIENT : [Nom] | PROJET : [Description] | Budget estimé : [€/TND]

DONNÉES FOURNIES :
- BOM matière : [Fichier upload]
- Coûts standard MO Compto : [Fichier ou infos]
- Délai souhaité : [Jours]
- Marge cible Compto : [%]

GÉNÈRE DEVIS FORMAT CLIENT :

Structure :
1. En-tête (logo Compto, date, numéro devis)
2. Description scope (3-5 lignes clair)
3. Tableau coûts détaillé :
   - Matière (sous-total)
   - Main-d'œuvre (sous-total)
   - Imprévus 10%
   - Montant HT & TVA
4. Conditions paiement
5. Validité 30 jours
6. Signature

IMPORTANT :
- Sois compétitif mais protecteur de marge Compto
- Coûts transparents (client doit comprendre)
- Utilise langage client (pas trop technique)

Export : Format PDF + Excel pour suivi interne

Upload les fichiers nécessaires.
```

---

### Cas 2.3 : Prévision Délai Fournisseur

**Défi :** Prédire risques délai avant problème

**Prompt :**
```
Tu es expert prévisions supply chain.

HISTORIQUE FOURNI : [Données fournisseurs Compto - derniers 12 mois]
- Fournisseur X : Lead time moyen, variance, délais dépassés
- Fournisseur Y : [idem]
[...]

PROJETS À VENIR :
- Projet A : [date livraison requise]
- Projet B : [date livraison requise]

ANALYSE :
1. Probabilité chaque fournisseur livre à temps
2. Facteurs risques identifiés
3. Alertes précoces (warning signs)
4. Plan B (fournisseurs de secours)

Format : Matrice risques + Recommandations
```

---

## GROUPE 3 : Études de Réalisation / SAV

### Cas 3.1 : Analyse Comparative Équipements Complexes

**Défi :** Choisir le bon équipement en 5 min vs 30 min étude

**Fichiers :**
- Manuel SUN2000-280KTL
- SG125CX User Manual
- JAM Motor Specs
- Normes NF C 15-100 (si disponible)

**Prompt Master :**
```
Tu es ingénieur responsable choix équipements chez Compto.

CONTEXTE PROJET :
- Type : Centrale PV 500 kWc
- Zone : Côtière (Gafsa, risque corrosion saline)
- Terrain : Montagne, altitude 800m, variation temp -5 à +45°C
- Client : Gouvernemental (exige garanties maximales)

DOCUMENTS UPLOADÉS :
1. SUN2000-280KTL (Huawei)
2. SG125CX (Sungrow)
3. JAM Motor Specs (pour stockage éventuel)
4. Normes application Tunisie

ANALYSE COMPARATIVE :

Critères pondérés :
┌──────────────────┬────────┬─────────┐
│ Critère          │ Poids  │ Notes   │
├──────────────────┼────────┼─────────┤
│ Rendement        │ 25%    │ [À noter]
│ Robustesse côtière │ 30% │ [À noter]
│ Garantie         │ 20%    │ [À noter]
│ Coût total       │ 15%    │ [À noter]
│ Support local    │ 10%    │ [À noter]
└──────────────────┴────────┴─────────┘

RÉSULTAT :
- Score chaque équipement (0-100)
- Recommandation justifiée (3-5 points clés)
- Risques résiduels & mitigation
- Plan B si recommandé indisponible

Format : Prêt pour présentation directeur/client
```

**Résultat Type :**
```
ÉTUDE COMPARATIVE - CHOIX ONDULEUR
─────────────────────────────────

SCORES
├─ SUN2000-280KTL : 87/100 ⭐ RECOMMANDÉ
├─ SG125CX : 82/100
└─ [Alternative] : 75/100

JUSTIFICATION :
✅ Rendement 98.6% (meilleur)
✅ IP65 + réputation robustesse zone côtière (Huawei agr.)
✅ Garantie 5 ans + support France + Tunisie
✅ Coût compétitif (850 EUR/kW)
⚠️ Légèrement plus cher que Sungrow (-30 EUR/kW)
   MAIS : Gain productible = +4 000 EUR/an

RECOMMANDATION FINALE :
SUN2000-280KTL (Huawei) = Choix optimal
Réduction risque 0 → Gain 40 000 EUR sur 25 ans

➡️ PROCHAIN STEP : Validation avec Socomec (fournisseur)
```

---

### Cas 3.2 : Diagnostic Anomalies Terrain (Vision + PDF)

**Défi :** Diagnostic rapide terrain → Guide techniqu

e en 2 min

**Ressources :**
- Photo équipement (smartphone terrain)
- Manuel technique (PDF)

**Prompt Multimodal :**
```
Je suis techniCompton SAV Compto sur site.

PROBLÈME : Onduleur affiche code erreur [CODE], LED [COULEUR]

UPLOADS :
1. Photo onduleur [JPG] - Vue complète + LED
2. Manuel technique [PDF]

DIAGNOSTIC :
1. Qu'indique le code d'erreur ?
   → Cherche dans manuel

2. Causes possibles (ordre probabilité)
   → [Cause 1] : 70% probable
   → [Cause 2] : 20% probable
   → [Cause 3] : 10% probable

3. Actions diagnostiques terrain (sans outil)
   → Que vérifier visuellement ?
   → Mesures simples (température, tension) ?

4. Décision : On/Off/Appel Expert ?
   → Si ON : Paramètres ?
   → Si OFF : Recommandation client ?
   → Si Expert : Info à fournir ?

5. Guide client (1 paragraphe clair en français)
   → Explique sans jargon

Format : Rapport WhatsApp-friendly (on peut envoyer directement client)
```

**Résultat Type :**
```
RAPPORT DIAGNOSTIC - CODE E04 ONDULEUR SUN2000
───────────────────────────────────────────────

📍 DIAGNOSTIC :
L'erreur E04 = Surchauffe thermique détectée.
L'onduleur a basculé en mode SÉCURISÉ.

⚠️ CAUSE PROBABLE (70%) :
   → Ventilation obstruée (poussière/feuilles)
   → Température boîtier > 75°C (seuil sécurité)

✅ ACTION IMMÉDIATE (Terrain) :
   1. Couper l'onduleur (DC switch)
   2. Nettoyer grille ventilation (soufflerie)
   3. Laisser refroidir 15 min
   4. Redémarrer

📊 RÉSULTAT ATTENDU :
   → Si OK : Onduleur repart, LED verte = ✅
   → Si Erreur persiste : Appel expert (probable défaut capteur)

📞 CLIENT :
"Bonne nouvelle ! C'est juste un besoin de nettoyage. 
 On a remis ça en route. Merci Compto ! 👍"

[Rapport prêt à partager]
```

---

### Cas 3.3 : Rédaction Rapport SAV Complet

**Défi :** Rapport pro en 10 min (vs 1h)

**Prompt :**
```
Tu es ingénieur SAV senior chez Compto.

INTERVENTION SAV :
- Date : [Date]
- Site : [Localisation]
- Équipement : [Type + Modèle]
- Problème rapporté : [Description client]
- Actions effectuées : [Liste détaillée]
- Diagnostic : [Conclusion technique]
- Pièces changées : [Oui/Non + liste]
- Durée intervention : [Heures]

UPLOADS SI BESOIN :
- Photos avant/après
- Données mesures (température, tension)
- Historique équipement (pannes antérieures)

GÉNÈRE RAPPORT SAV PROFESSIONNEL :

Structure :
1. En-tête (Logo Compto, Date, N° intervention)
2. Résumé exécutif (3 lignes)
3. Description problème
4. Actions correctives détaillées
5. Diagnostic technique
6. Recommandations (Préventif ? Monitoring ?)
7. Garantie pièces (si applicable)
8. Signature + Tampon Compto

Tone : Professionnel, clair, rassurant
Langue : Français (client français possible)
Format : Prêt à envoyer par email + archiver

Notes importantes :
- Évite jargon excessif
- Explique ce qui a changé pour client
- Clear next steps
```

---

# 🔌 BLOC 4 : INTÉGRATION WORKFLOWS (30 minutes)

## I. Gemini + Excel (Groupe 2 prioritaire)

### Use Case 1 : Formules Complexes Auto-Générées

**Problème :** Formule de coût complexe = 15 min de développement

**Solution :**
```
Prompt : "J'ai un fichier Excel Compto avec colonnes :
- Matière (USD)
- Transport (+20%)
- Douane (10%)
- Marge Compto (25%)
- TVA (19%)

Génère formule EXCEL complète pour MONTANT FINAL
utilisable dans colonne [D].

Formule doit être :
- Robuste (gère zéro values)
- Arrondie 2 décimales
- Prête à copier-coller

Upload Excel ou donne structure"

Résultat : Formule en 30 sec, testée
```

---

### Use Case 2 : Pivot Tables Auto-Documentées

**Problème :** Pivot table = confus pour utilisateurs

**Solution :**
```
Prompt : "Crée un GUIDE UTILISATEUR pour pivot table Excel :
- Comment la mettre à jour mensuellement
- Comment filtrer par fournisseur
- Comment voir % progrès objectifs

Format : 1-2 pages, screenshots, numérotation

Upload tableau Excel"

Résultat : Doc autonome en 5 min
```

---

## II. Gemini + SAGE X3 (Groupe 1 & 2)

### Use Case 1 : Préparation Données Import

**Flux :**
```
Excel chaotique (50 factures) 
    ↓ [Gemini : Nettoyage]
Excel clean + format SAGE 
    ↓ [Compto : Import SAGE]
Factures saisies & validées
```

**Prompt Template :**
```
"J'importe [N] factures dans SAGE X3 (Tunisie).

Format attendu par SAGE :
[Explication structure SAGE]

Mon fichier Excel actuel :
[Upload ou description]

Transforme mon Excel en format SAGE exact.
Propose aussi checklist avant import pour éviter erreurs."

Résultat : Excel ready-to-import + Checklist
```

---

### Use Case 2 : Audit Avant Clôture Mensuelle

**Problème :** Vérifier intégrité données SAGE = risqué & long

**Solution :**
```
Prompt : "Je dois faire audit données SAGE avant clôture mois.
Génère checklist de 20 points critiques :
- Soldes fournisseur cohérents ?
- Factures non-facturées ?
- Écarts budgétaires > 5% ?
[etc.]

Format : Checklist facile à cocher en Excel

Upload : Exemple rapport SAGE ou describe"

Résultat : Checklist validée en 2 min
```

---

## III. Gemini + Email/Outlook (Tous groupes)

### Use Case 1 : Email Sensibles (Communication Difficile)

**Exemple :**
```
SITUATION : Client mécontent, délai dépassé, qualité questionnable

Prompt : "Je dois écrire email client en Français.
Contexte difficile : [Détails situation]
Ton requis : Professionnel, apologétique, mais ferme
Longueur : 150-200 mots

Génère draft email"

Résultat : Réponse appropriée immédiate (vs 1h d'hésitation)
```

---

### Use Case 2 : Synthèse Long Email Thread

**Exemple :**
```
Prompt : "Voici 8 emails d'échange avec client sur projet [X].
C'est un mess, plusieurs topics mélangés.

Synthétise en 1 email de réponse qui :
1. Recap décisions prises
2. Actions en cours
3. Prochaines steps
4. Questions restantes

Format : Clair, pas de redondance, prêt à envoyer"

Résultat : Email de synthèse en 2 min
```

---

## IV. Roadmap 30 Jours Post-Formation (5 min)

**Chaque groupe reçoit plan personnel :**

### GROUPE 1 (Commercial)
```
JOUR 1-3 : Essayer 1 offre Gemini (cas simple)
JOUR 4-7 : Refiner prompt offre (itération)
JOUR 8-14 : Générer 3 offres réelles clients
JOUR 15-21 : Documenter template Compto + Partager équipe
JOUR 22-30 : Proposer amélioration contrats (feedback)
```

### GROUPE 2 (Supply)
```
JOUR 1-3 : Analyser 1 BOM existante (exercice)
JOUR 4-7 : Identifier risques supply chains 2-3 projets
JOUR 8-14 : Implémentation Excel nettoyage
JOUR 15-21 : Premier devis Gemini-assisted
JOUR 22-30 : Coaching fournisseurs (optimisation)
```

### GROUPE 3 (Études)
```
JOUR 1-3 : Tester comparaison 2 équipements
JOUR 4-7 : Analyse rapport SAV terrain (photo)
JOUR 8-14 : Première rédaction rapport Gemini
JOUR 15-21 : Diagnostic terrain en direct (WhatsApp)
JOUR 22-30 : FAQ support technique (automation)
```

---

# 🎓 RESSOURCES & ANNEXES

## ANNEXE 1 : Templates Prompts Par Métier

**Groupe 1 - Commercial :**
```
[20 templates : Offres, Contrats, Relances, Rapports]
```

**Groupe 2 - Supply :**
```
[20 templates : BOM Analysis, Devis, Planning, Optimisation Coûts]
```

**Groupe 3 - Études :**
```
[20 templates : Comparaisons, Diagnostics, Rapports SAV, Normes]
```

---

## ANNEXE 2 : Guide Dépannage Gemini

**"Pourquoi Gemini dit "Je ne sais pas" ?"**
```
Raison 1 : Info trop récente (post-2024)
Raison 2 : Document uploadé mauvaise qualité (PDF scanné pixelisé)
Raison 3 : Prompt trop vague = pas contexte
Solution : Être plus spécifique, uploader meilleur doc
```

---

## ANNEXE 3 : Cas d'Usage Bonus (Si Temps)

**Groupe 1 :**
- Génération FAQ Clients automatisée
- Chatbot Devis Interne

**Groupe 2 :**
- Prévisions Prix Commodités (IF DATA AVAILABLE)
- Simulation Scénarios Supply

**Groupe 3 :**
- Création Manuel Maintenance (à partir datasheet)
- Support Multi-langue (En/Fr/Ar pour clients)

---

**Version 1.0 | 20 Janvier 2026**
