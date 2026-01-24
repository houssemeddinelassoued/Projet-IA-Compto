# 🚀 GROUPE 3 : ÉTUDES / SAV

## Exercice 10 : Diagnostic Onduleur (Multimodal)

**Énoncé :** Diagnostiquer anomalie équipement via photo + manuel

**Fichiers :**
- Manuel : `EN-UM-SG125CX-P2-User-Manual-V12-202205 - Hamdi Jemi.pdf`
- Photo : [Prendre screenshot ou photo équipement]

**Scénario :**
```
SITUATION TERRAIN :
- Site : Centrale PV Skhira
- Équipement : Onduleur SG125CX
- Problème : Code d'erreur "F02", LED rouge clignotante
- Client : Appelé support (vous !)
```

**Prompt :**
```
Je suis technicien SAV.

Problème terrain :
- Onduleur SG125CX
- Code erreur F02
- LED rouge clignotante
- Client signale : "Plus d'électricité depuis ce matin"

Upload Manuel SG125CX :
[Manuel uploadé]

DIAGNOSTIC :
1. Que signifie F02 ? (Cherche dans manuel)
2. Causes probables (3-5 ordonnées par probabilité)
3. Actions diagnostiques terrain (sans outil)
4. Decision : Redémarrer / Remplacer / Expert ?
5. Client message (1 phrase simple en français)

Format : Rapport WHATSAPP-READY (on peut envoyer direct client)
```

**Résultat Attendu :**
```
DIAGNOSTIC ONDULEUR SG125CX - CODE F02
───────────────────────────────────────

⚠️ CODE F02 = Perte de communication réseau (Grid Down)

CAUSES PROBABLES (ordre) :
1. 70% : Disjoncteur AC déclenché
   → Vérifier position switch AC (ON/OFF)
   
2. 20% : Câble réseau débranché / endommagé
   → Inspecter connectique RJ45
   
3. 10% : Défaut électronique interne
   → Si câbles OK, problème électronique

ACTIONS TERRAIN (No-Tool) :
1. Vérifier disjoncteur AC (position ON)
2. Regarder connectique RJ45 (câble branché ?)
3. Attendre 2 min, puis redémarrer onduleur

RÉSULTAT ATTENDU :
→ Si câble OK + disjoncteur ON : LED verte = ✅ (Problème résolu)
→ Si LED reste rouge : Appeler expert (prob. défaut électronique)

CLIENT MESSAGE :
"Bonjour, c'est probable un câble débranché ou disjoncteur
déclenché. On va vérifier ça ensemble. Je vous rappelle
dans 5 min. Merci ! 👍"
```

**✅ Vérification :**
- [ ] Code erreur interprété correctement
- [ ] Causes listées par probabilité
- [ ] Actions terrain claires & simples
- [ ] Message client rassurant

---

## Exercice 11 : Analyse Comparative Équipements

**Énoncé :** Choisir moteur/équipement pour application client

**Fichiers :**
- `JAM66D45 605-630 LB 30 Frame Standard Product Global_EN_20241105A - Nessrine Ben Nejma.pdf`
- `Manuel SUN2000` (si besoin comparaison hybride)

**Prompt :**
```
Je suis ingénieur avant-vente.

CLIENT demande : "Quel équipement choisir pour [Application] ?"

J'ai documentation du produit candidat uploadée.

ANALYSE :
1. À quoi sert ce produit ? (Industrie, usage, puissance)
2. Caractéristiques principales (puissance, dimensions, efficacité)
3. Environnement applicatif (Température, humidity, protection)
4. Normes de sécurité / conformité
5. Coûts opérationnels (Consommation, maintenance)
6. Point fort vs point faible
7. Pour client type, je recommande : OUI / NON / AVEC RÉSERVES

Format : Fiche synthétique 1 page (client-ready)
```

**Résultat Attendu :**
```
FICHE TECHNIQUE - JAM66D45 MOTOR
─────────────────────────────────

APPLICATION : Moteur électrique triphasé à induction
PUISSANCE : [kW] | VITESSE : [rpm] | RENDEMENT : [%]

CARACTÉRISTIQUES CLÉS :
├─ Tension : 400V triphasé
├─ Protection : IP55 (résistant poussière & eau)
├─ Température : -5 à +40°C
├─ Montage : Bride standard
└─ Garantie : 2 ans

ENVIRONNEMENT :
✅ Convient : Industrie, extérieur, conditions humides
❌ Ne convient pas : Très haute température (>60°C)

NORMES : IEC 60034-1, CE, RoHS

COÛTS ANNUELS ESTIMÉS :
- Électricité : [€]
- Maintenance : [€]
- Total TCO : [€]

VERDICT : ✅ RECOMMANDÉ
Raison : Bon rapport qualité/prix, robuste, support local

PRIX INDICATIF : [EUR]
```

**✅ Vérification :**
- [ ] Application bien comprise
- [ ] Specs extraites correctement
- [ ] Points forts/faibles identifiés
- [ ] Recommandation justifiée

---

## Exercice 12 : Rédaction Rapport SAV Complet

**Énoncé :** Générer rapport professionnel d'intervention SAV

**Contexte :**
```
INTERVENTION SAV :
- Date : 18/01/2026
- Site : Centrale Sfax
- Équipement : Onduleur Huawei SUN2000-280KTL
- Problème : Surchauffe + arrêt productif
- Durée : 2.5 heures
- Actions : Nettoyage ventilation, vérification capteurs
- Résultat : Remise en route OK, Monitoring actif 24h
```

**Prompt :**
```
Tu es ingénieur SAV senior.

INTERVENTION SAV à documenter :
- Date : 18/01/2026
- Site : Centrale Sfax
- Équipement : Onduleur SUN2000-280KTL
- Technicien : [Your Name]
- Problème : Surchauffe détectée, arrêt productif 3 heures
- Actions : Inspection & nettoyage ventilation + Vérif capteurs temp
- Durée : 2h30
- Résultat : Remise en route normal, monitoring 24h activé
- Pièces changées : Aucune
- Nouveau problème trouvé : Non

GÉNÈRE RAPPORT SAV PROFESSIONNEL :

Sections :
1. En-tête (Compto logo, date, N° intervention, site)
2. Résumé exécutif (3 lignes)
3. Description problème (client words)
4. Actions correctives détaillées
5. Diagnostic technique
6. Recommandations (Préventif ? Upgrade monitoring ?)
7. Pièces de rechange (si applicable)
8. Prochaine maintenance préventive (date)
9. Signature + Cachet

Tone : Professionnel, rassurant, clair
Format : Prêt à envoyer par email + archiver

Langue : Français (possible client français)
```

**Résultat Attendu :**
```
────────────────────────────────────────────
RAPPORT D'INTERVENTION SAV - Compto
────────────────────────────────────────────

EN-TÊTE :
Centrale Sfax | 18/01/2026 | Intervention n° SAV-2026-0847
Technicien : [Votre Nom]

RÉSUMÉ EXÉCUTIF :
Onduleur Huawei SUN2000-280KTL présentait surchauffe thermique
(arrêt productif 3h). Cause identifiée : Ventilation obstruée.
Solution appliquée : Nettoyage & Vérification. Équipement remis
en route normal. Monitoring 24/7 activé.

DESCRIPTION PROBLÈME :
Client a signalé arrêt productif du 16/01 08:00 au 16/01 11:00.
Alerte LED rouge "Surchauffe". Production zéro pendant période.
Client préoccupé par continuité service.

ACTIONS CORRECTIVES :
1. Inspection visuelle onduleur (Boîtier + Ventilation)
   → Constat : Grille ventilation obstruée poussière/feuilles
   
2. Nettoyage ventilation (Soufflerie, brosse douce)
   → Résultat : Passage d'air rétabli
   
3. Vérification capteurs température
   → Test électrique OK, valeurs cohérentes

4. Redémarrage progressif onduleur
   → Initialisation normale
   → Production reprise à 100% 12 min après restart

5. Activation monitoring 24/7 (Huawei iManager)
   → Alertes temps réel vers équipe SAV

DIAGNOSTIC :
Surchauffe due à ventilation insuffisante. Cause racine = 
Accumulation naturelle poussière/débris en zone côtière (sel).

RECOMMANDATIONS :
✅ Maintenance préventive mensuelle (Nettoyage ventilation)
✅ Considérer écran anti-poussière pour climat côtier
✅ Monitoring continu (Huawei iManager déjà actif)

PIÈCES DE RECHANGE : Aucune (Nettoyage suffisant)

PROCHAINE MAINTENANCE PRÉVENTIVE :
Inspection complète + Nettoyage : 18/02/2026 (prévoir 2h)

Travaux effectués sans frais additionnel (maintenance incluse).

────────────────────────────────────────
Signature & Cachet Compto
```

**✅ Vérification :**
- [ ] Rapport structuré et professionnel
- [ ] Diagnose claire
- [ ] Actions détaillées
- [ ] Recommandations utiles
- [ ] Prêt pour client + Archivage

---

## Exercice 13 : Comparaison Spécifications Techniques Multi-PDFs

**Énoncé :** Analyser et comparer 3 manuels techniques pour déc ision client

**Fichiers :**
- `Manuel d_utilisation, série SUN2000-(250KTL, 280KTL, 300KTL, 330KTL) - Hiba Mezzi.pdf`
- `EN-UM-SG125CX-P2-User-Manual - Hamdi Jemi.pdf`
- `JAM66D45 Motor Spec - Nessrine Ben Nejma.pdf`

**Prompt :**
```
Je suis ingénieur études  .

CLIENT question : "Je dois choisir équipement pour mon installation.
Quelle est la meilleure option ?"

Fichiers uploadés :
1. Huawei SUN2000 (onduleur PV)
2. Sungrow SG125CX (onduleur PV alt)
3. JAM Motor (stockage énergie)

ANALYSE COMPARATIVE :

Critères (pondérés) :
┌─────────────────────┬───────┐
│ Rendement / Effica. │ 30%   │
│ Robustesse/Durée    │ 25%   │
│ Prix / m²           │ 20%   │
│ Garantie            │ 15%   │
│ Support local       │ 10%   │
└─────────────────────┴───────┘

Pour chaque option :
- Score 0-100
- Points forts (2-3)
- Points faibles (1-2)

RÉSULTAT FINAL :
- Tableau comparatif
- Scores numériques
- Recommandation + Justification
- Coûts estimés TLC (Total Life Cost)

Format : 1-2 pages, prêt pour réunion client
```

**Résultat Attendu :**
```
ÉTUDE COMPARATIVE - CHOIX ÉQUIPEMENTS
──────────────────────────────────────

TABLEAU SYNTHÉTIQUE :
┌──────────────────┬──────────────┬──────────────┬──────────┐
│ Critère (Poids)  │ SUN2000 (30%)│ SG125CX (25%)│ JAM Motor│
├──────────────────┼──────────────┼──────────────┼──────────┤
│ Rendement        │ 98.6%        │ 98.2%        │ 96%      │
│ Robustesse       │ ⭐⭐⭐⭐⭐   │ ⭐⭐⭐⭐   │ ⭐⭐⭐⭐  │
│ Prix (EUR/kW)    │ 850          │ 820          │ -        │
│ Garantie         │ 5 ans        │ 5 ans        │ 2 ans    │
│ Support Tunisie  │ Excellent    │ Bon          │ Moyen    │
└──────────────────┴──────────────┴──────────────┴──────────┘

SCORES FINAUX :
SUN2000 : 88/100 ⭐ RECOMMANDÉ
SG125CX : 84/100
JAM Motor : 72/100

RECOMMANDATION :
👉 SUN2000-280KTL (Huawei)

JUSTIFICATION :
1. Meilleur rendement (98.6%) = +2% productible
2. Support français + Tunisie (important)
3. Réputation excellente zone côtière
4. Coût additionnel marginal vs gain long-terme

COÛTS TLC (25 ans, 500 kWc) :
├─ SUN2000 : 450 000 EUR (installation + opération + garantie)
├─ SG125CX : 455 000 EUR
└─ → Difference : SUN2000 saving 5 000 EUR sur 25 ans

IMPLÉMENTATION :
- Installer immédiatement (délai 6 sem)
- Monitoring Huawei iManager inclus
- Contrat maintenance Compto 2 ans
```

**✅ Vérification :**
- [ ] Critères évalués objectivement
- [ ] Scores comparables
- [ ] Recommandation justifiée
- [ ] Coûts long-terme analysés
