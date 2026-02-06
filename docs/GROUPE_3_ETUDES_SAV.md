# 🚀 GROUPE 3 : ÉTUDES / SAV

**📥 Lien Drive :** https://shorturl.at/JV2Bz (téléchargement des fichiers nécessaires)

---

## 👥 Participants & Fichiers de travail

| # | Participant | Email | Fichier disponible | Exercice(s) associé(s) |
|---|-------------|-------|--------------------|------------------------|
| 1 | Jalel DHAOUADI | jalel.dhaouadi@compto-cie.com | - | Ex. 1 |
| 2 | Bechir MSAADI | bechir.msaadi@compto-cie.com | Analyse fonctionnelle rev 1 11 10 2023 - Bechir MSAADI.pdf | Ex. 1, 8 |
| 3 | Walid MEZOUGHI | walid.mezoughi@compto-cie.com | - | Ex. 1 |
| 4 | Khaled Ben Salem | khaled.bensalem@compto-cer.com | - | Ex. 1 |
| 5 | Mehdi Dridi | mehdi.dridi@compto-cie.com | BOMPRN (6) - Mehdi Dridi.pdf | Ex. 14 |
| 6 | Nadia Ayari | nadia.ayari@compto-cer.com | - | Ex. 1 |
| 7 | Hamdi Jemi | hamdi.jemi@compto-cer.com | EN-UM-SG125CX-P2-User-Manual-V12-202205 - Hamdi Jemi.pdf | Ex. 2, 3 |
| 8 | Mohamed Abdelmoumen | mohamed.abdelmoumen@compto-cer.com | DATASET PV SYST - Mohamed Abdelmoumen.xlsx / .csv | Ex. 7 |
| 9 | Abdelmonaam OUESLATI | abdelmonaam.eloueslati@compto.com.tn | - | Ex. 13 |
| 10 | Amal SASSI | amal.sassi@compto-cie.com | - | Ex. 13 |
| 11 | Borhen HAMMAMI | borhen.hammami@compto.com.tn | - | Ex. 12 |
| 12 | Mahdi HAJRI | mahdi.hajri@compto-cie.com | - | Ex. 12 |
| 13 | Abdessattar ELMBARKI | abdessattar.elmbarki@compto-cie.com | Compact NSX_LV431545 - Abdessattar ELMBARKI.pdf | Ex. 12 |
| 14 | Ahlem OMRI | ahlem.omri@compto-cie.com | - | Ex. 13 |
| 15 | Mahmoud REKIK | mahmoud.rekik@compto.com.tn | - | Ex. 1 |
| 16 | Mariem ZIEDI | sav-cie@compto-cie.com | ODP SAV POUR FORMATION - Mariem Ziedi.pdf | Ex. 6 |
| 17 | Miled AJILI | miled.ajili@compto-cie.com | RapportSAV intervention preventive Chokri Hammouda P06-F03vf - Miled Ajili.pdf | Ex. 5 |
| 18 | Sabri HMAIDI | grh@compto-cie.com | - | Ex. 1 |
| 19 | Fatma ABDELMOULA | fatma.abdelmoula@compto-cie.com | FOUNITURES DE BUREAU 2026 - Fatma Abdelmoula.xlsx | Ex. 13 |
| 20 | Aymen RABBOUCHE | it-cie@compto-cie.com | Brochure GI_Commerciale FR TN 004_compressed - Aymen Rabbouche.pdf | Ex. 1 |

---

## 💡 Les 14 Exercices Pratiques

### ✏️ Exercice 1 : Votre Première Requête Simple
**Énoncé :** Analyser rapidement un document technique et extraire l’essentiel

**Fichiers suggérés :**
- `Analyse fonctionnelle rev 1 11 10 2023 - Bechir MSAADI.pdf`
- `Brochure GI_Commerciale FR TN 004_compressed - Aymen Rabbouche.pdf`

**Prompt :**
```
Je suis ingénieur chez Compto.

Je viens de recevoir ce document technique (PDF uploadé).

Analyse rapide demandée :
1. Objet du document (en 1 phrase)
2. 5 points techniques clés à retenir
3. Risques / contraintes mentionnées
4. Actions à prévoir pour l’équipe

Format :
- Résumé simple et clair
- 5 bullets maximum
- Prêt à partager au manager
```

**✅ Vérification :**
- [ ] Résumé clair en moins d’1 minute
- [ ] 5 points clés maximum
- [ ] Actions proposées

---

### ✏️ Exercice 2 : Diagnostic Onduleur (Multimodal)
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

**✅ Vérification :**
- [ ] Code erreur interprété correctement
- [ ] Causes listées par probabilité
- [ ] Actions terrain claires & simples
- [ ] Message client rassurant

---

### ✏️ Exercice 3 : Comparaison Onduleurs (Huawei vs Sungrow)
**Énoncé :** Comparer deux onduleurs et recommander une option

**Fichiers :**
- `Manuel d_utilisation, série SUN2000-(250KTL, 280KTL, 300KTL, 330KTL) (2) - Hiba Mezzi.pdf`
- `EN-UM-SG125CX-P2-User-Manual-V12-202205 - Hamdi Jemi.pdf`

**Prompt :**
```
Je suis ingénieur études.

COMPARE ces 2 onduleurs pour un projet PV côtier :
1. Rendement / efficience
2. Robustesse / IP
3. Garantie
4. Conditions environnementales
5. Support local

Score 0-100 + Recommandation justifiée (3 points max).
```

**✅ Vérification :**
- [ ] Critères comparés
- [ ] Scores numériques
- [ ] Recommandation claire

---

### ✏️ Exercice 4 : Analyse Comparative Équipements
**Énoncé :** Choisir un équipement pour application client

**Fichier :**
- `JAM66D45 605-630 LB 30 Frame Standard Product Global_EN_20241105A (11) - Nessrine Ben Nejma.pdf`

**Prompt :**
```
Je suis ingénieur avant-vente.

CLIENT demande : "Quel équipement choisir pour [Application] ?"

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

**✅ Vérification :**
- [ ] Application bien comprise
- [ ] Specs extraites correctement
- [ ] Points forts/faibles identifiés
- [ ] Recommandation justifiée

---

### ✏️ Exercice 5 : Rédaction Rapport SAV Complet
**Énoncé :** Générer rapport professionnel d’intervention SAV

**Fichier :**
- `RapportSAV intervention preventive Chokri Hammouda P06-F03vf - Miled Ajili.pdf`

**Prompt :**
```
Tu es ingénieur SAV senior.

Résume le rapport SAV fourni :
1. Contexte & cause racine
2. Actions correctives
3. Résultat et statut final
4. Recommandations prévention
5. Prochaine maintenance suggérée

Format : Rapport prêt à envoyer par email + archiver
```

**✅ Vérification :**
- [ ] Rapport structuré et professionnel
- [ ] Diagnostic clair
- [ ] Actions détaillées
- [ ] Recommandations utiles

---

### ✏️ Exercice 6 : Synthèse ODP SAV & Plan d’Intervention
**Énoncé :** Transformer une présentation SAV en plan d’action

**Fichier :**
- `ODP SAV POUR FORMATION - Mariem Ziedi.pdf`

**Prompt :**
```
Je suis responsable SAV.

À partir de l’ODP SAV :
1. Résume les points clés (max 8 lignes)
2. Liste 5 actions prioritaires
3. Propose 3 KPI de suivi

Format : Synthèse + plan d’action (bullet points)
```

**✅ Vérification :**
- [ ] Synthèse concise
- [ ] Actions prioritaires claires
- [ ] KPI pertinents

---

### ✏️ Exercice 7 : Dataset PV - Nettoyage & Analyse
**Énoncé :** Analyser un dataset PV pour insights et anomalies

**Fichiers :**
- `DATASET PV SYST - Mohamed Abdelmoumen.xlsx`
- `DATASET PV SYST - Mohamed Abdelmoumen.csv`

**Prompt :**
```
Je suis analyste données.

Fichier uploadé = Dataset PV.

ANALYSE :
1. Qu'est-ce que ce dataset (structure, variables) ?
2. Combien de lignes / colonnes ?
3. Données manquantes ? Doublons ?
4. KPI principaux calculables ?
5. 3 insights intéressants (performance, anomalies, tendances)

Format : Résumé exécutif + Recommandations
```

**✅ Vérification :**
- [ ] Structure bien comprise
- [ ] Qualité données évaluée
- [ ] KPI pertinents identifiés
- [ ] Insights exploitables

---

### ✏️ Exercice 8 : Analyse Fonctionnelle & Exigences
**Énoncé :** Extraire exigences techniques d’une analyse fonctionnelle

**Fichier :**
- `Analyse fonctionnelle rev 1 11 10 2023 - Bechir MSAADI.pdf`

**Prompt :**
```
Je suis responsable bureau d’études.

Analyse le document et fournis :
1. Objet du système (1 phrase)
2. Fonctions principales
3. Contraintes techniques / normes
4. Interfaces clés
5. Risques techniques à surveiller

Format : Tableau synthèse + 5 alertes
```

**✅ Vérification :**
- [ ] Fonctions principales identifiées
- [ ] Contraintes extraites
- [ ] Risques listés

---

### ✏️ Exercice 9 : Spécifications Télécom - Extraction & Chiffrage
**Énoncé :** Extraire spécifications complexes pour chiffrer une solution télécom

**Fichier :**
- `Attachment T2 TGP-AEI-GTPT-870-CI-SPE-0003 GTP-T Telecommunication & Security Systems Specification_ - Direction Projets.pdf`

**Prompt :**
```
Je suis chiffreur solutions télécom chez Compto.

UPLOAD = Spécifications client projet télécom.

EXTRACTION :
1. Équipements requis (détail complet)
2. Quantités (par type d’équipement)
3. Versions / Références exactes
4. Services associés (installation, formation, support)
5. Délais spécifiés
6. Normes/Certifications exigées

Format : Tableau chiffrage avec références fournisseur
```

**✅ Vérification :**
- [ ] Équipements identifiés
- [ ] Quantités exactes
- [ ] Services listés
- [ ] Références incluses

---

### ✏️ Exercice 10 : Reporting Avancement Projet
**Énoncé :** Créer un rapport d’avancement à partir de données brutes

**Fichier :**
- `04 01 26 Rapport d_avancement des travaux N°4 - Almoez Jbeli.pdf`

**Prompt :**
```
Je suis directeur opérationnel.

Fichier uploadé = données avancement projet.

GÉNÈRE RAPPORT D'AVANCEMENT :
1. Statut global (Vert/Orange/Rouge)
2. % avancement physique et financier
3. Retards critiques (max 3)
4. Actions correctives recommandées
5. Décisions à valider

Format : 1 page max, prêt à envoyer au client
```

**✅ Vérification :**
- [ ] Statut global clair
- [ ] Retards identifiés
- [ ] Actions correctives proposées

---

### ✏️ Exercice 11 : Planning & Risques (PMO)
**Énoncé :** Identifier risques et jalons dans un planning projet

**Fichier :**
- `PMBOK compliant project management (by Sensei Project Solutions) - Mohamed Ali Sakkar.mpp`

**Prompt :**
```
Je suis PMO.

À partir du planning :
1. Jalons clés
2. Chemin critique
3. Risques de retard
4. Recommandations d’optimisation

Format : Synthèse + tableau risques
```

**✅ Vérification :**
- [ ] Jalons identifiés
- [ ] Risques listés
- [ ] Recommandations claires

---

### ✏️ Exercice 12 : Analyse Matériel BT (Compact NSX)
**Énoncé :** Extraire les spécifications techniques d’un équipement BT

**Fichier :**
- `Compact NSX_LV431545 - Abdessattar ELMBARKI.pdf`

**Prompt :**
```
Je suis chargé d’affaires BT.

Résumé demandé :
1. Référence exacte
2. Caractéristiques électriques clés
3. Conditions d’installation
4. Normes et certifications
5. Points de vigilance

Format : Fiche technique synthétique
```

**✅ Vérification :**
- [ ] Spécifications extraites
- [ ] Conditions d’installation mentionnées
- [ ] Points de vigilance listés

---

### ✏️ Exercice 13 : Nettoyage Excel & Priorisation Achats
**Énoncé :** Analyser un fichier Excel pour nettoyage et priorisation

**Fichier :**
- `FOUNITURES DE BUREAU 2026 - Fatma Abdelmoula.xlsx`

**Prompt :**
```
Je suis assistante administrative.

Fichier Excel = achats fournitures.

ANALYSE :
1. Doublons / incohérences
2. Valeurs manquantes
3. Top 10 articles par coût
4. Propositions d’économies (3 actions)

Format : Tableau + recommandations
```

**✅ Vérification :**
- [ ] Doublons identifiés
- [ ] Top 10 extrait
- [ ] Recommandations utiles

---

### ✏️ Exercice 14 : Analyse BOM / Nomenclature
**Énoncé :** Identifier les risques et incohérences dans une BOM

**Fichier :**
- `BOMPRN (6) - Mehdi Dridi.pdf`

**Prompt :**
```
Analyse cette nomenclature de production :
1. Nombre de composants
2. Pièces critiques (lead time long)
3. Risques d’approvisionnement
4. Actions de mitigation

Format : Tableau synthèse + priorités
```

**✅ Vérification :**
- [ ] Composants comptés
- [ ] Risques identifiés
- [ ] Actions priorisées

---

## 🎓 Récapitulatif des Exercices par Profil

| Profil | Exercices recommandés | Fichiers à utiliser |
|--------|------------------------|---------------------|
| **Technicien / SAV** | Ex. 2, 5, 6 | Manuel SG125CX, Rapport SAV, ODP SAV |
| **Bureau d’études** | Ex. 1, 3, 4, 8, 12 | Analyse fonctionnelle, Manuels onduleurs, JAM66D45, Compact NSX |
| **Monitoring / Data** | Ex. 7 | Dataset PV |
| **Chef projet / PMO** | Ex. 10, 11 | Rapport avancement, Planning PMBOK |
| **Télécom / Chiffrage** | Ex. 9 | Specs télécom T2 |
| **Admin / Achats** | Ex. 13 | Fournitures bureau |
| **Production / BOM** | Ex. 14 | BOMPRN |

---

## ✅ Checklist Post-Session 1

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

## 📅 Informations Pratiques

**Sessions & Formateur :**
- **Sessions :** Samedi 07/02/2026 et Jeudi 12/02/2026
- **Lieu :** Ben Arous
- **Formateur :** Houssem Eddine Lassoued
- **Durée :** 10 heures total (2 séances × 5h)

**Ressources Complémentaires :**
- https://gemini.google.com
- https://github.com/houssemeddinelassoued/Projet-IA-Compto/blob/main/SUPPORT_FORMATION_GEMINI_COMPLET.md
- https://github.com/houssemeddinelassoued/Projet-IA-Compto/blob/main/CARNET_EXERCICES_PRATIQUES.md
- https://github.com/houssemeddinelassoued/Projet-IA-Compto/blob/main/GUIDE_FORMATEUR.md
