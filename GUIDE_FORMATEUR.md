# 🎯 GUIDE FORMATEUR - Gemini Pro CIE/CER
## Instructions d'Exécution et Points Clés | Janvier-Février 2026

---

## 📋 VUE D'ENSEMBLE QUICK

**Durée totale :** 6 heures par groupe (2 séances x 3h)  
**Théorie/Pratique :** 30% / 70%  
**Nombre participants :** 16-22 par groupe  
**Ressources principales :**
1. Ce Support de Formation (SUPPORT_FORMATION_GEMINI_COMPLET.md)
2. Carnet d'Exercices (CARNET_EXERCICES_PRATIQUES.md)
3. Fichiers participants dans `/files/`
4. Templates Prompts (À préparer avant formation)

---

## ⏱️ TIMING DÉTAILLÉ PAR SÉANCE

### **SÉANCE 1 : FONDAMENTAUX (3h) - 9:00-12:00**

```
09:00-09:30 → INTRODUCTION (30 min)
  • Accueil + Contexte CIE/CER
  • Objectives du jour
  • Live Demo simple : "Gemini en 2 min"

09:30-10:30 → DÉMO LIVE CAS MÉTIER (60 min)
  • [30 min] Démo réelle sur fichier du groupe
  • [10 min] Walkthrough interface
  • [15 min] PAUSE
  • [5 min] Q&A première vague

10:30-11:20 → ATELIER 1 : "VOTRE PREMIER PROMPT" (50 min)
  • [5 min] Expliquer "Bonne Structure Prompt"
  • [20 min] Participants écrivent leur prompt
  • [20 min] Testent sur Gemini (1 par 2-3 pers)
  • [5 min] Volontaires partagent résultat

11:20-12:00 → RETOUR + DEVOIRS (40 min)
  • [10 min] Résumé clés retenante
  • [5 min] Montrer Templates Prompts
  • [10 min] Assigner Exercice Maison (carnet)
  • [15 min] Q&A + Feedback session
```

---

### **SÉANCE 2 : AVANCÉ (3h) - 09:00-12:00**

```
09:00-09:20 → RETOURS EXPÉRIENCE (20 min)
  • "Qui a essayé Gemini ? Qu'est-ce qui a marché ?"
  • Partager succès / frustrations
  • Corriger idées fausses

09:20-10:30 → ATELIER 2 : CAS AVANCÉ (70 min)
  • [5 min] Intro cas métier spécialisé
  • [25 min] Participants découvrent cas (docs fournies)
  • [20 min] Test sur Gemini (live)
  • [15 min] Partage résultats
  • [5 min] Débriefing

10:30-11:30 → ATELIER 3 : MULTI-DOCUMENTS (60 min)
  • [10 min] Explique Upload + Multi-Modal
  • [35 min] Atelier pratique (3 PDFs, comparaison)
  • [15 min] Présentation résultats

11:30-12:00 → CLÔTURE (30 min)
  • [5 min] Résumé apprentissages clés
  • [5 min] Plan d'action 30j (distribuer)
  • [10 min] Certification mini (Quiz rapide)
  • [10 min] Feedback forms + évaluation
```

---

## 🎬 DÉMO LIVE - PRÉPARATION CRITIQUE

**AVANT la séance :**

1. **Tester Gemini 48h avant** (Pas de surprise le jour J!)
2. **Préparer prompts démo** (Copy-coller direct, testé)
3. **Préparer fichiers** (PDFs accessibles, testés dans Gemini)
4. **Backup Internet** (Hotspot personnel + Cable)
5. **Microphone OK** (Amplifier projection si nécessaire)

**JOUR J :**

✅ **15 min avant :** Ouvrir Gemini, tester file upload, tester prompt  
✅ **5 min avant :** Préparer 2ème onglet browser (Backup)  
✅ **Ouvrir Chat** : Avoir le prompt visible aux participants

**Format Projecteur :**
```
╔════════════════════════════════════════╗
║  GEMINI DEMO - CAS GROUPE [X]          ║
║  "Titre provocant + temps estimé"      ║
╠════════════════════════════════════════╣
║                                        ║
║  [Écran Gemini projeté - font large]  ║
║                                        ║
║  PROMPT EN HAUT (visible à tous)      ║
║  RÉSULTAT EN BAS (live generation)    ║
║                                        ║
╚════════════════════════════════════════╝
```

---

## 📊 DÉMOS RECOMANDÉES PAR GROUPE

### **GROUPE 1 - Commercial**

**Démo 1 (S1) : Email Difficile → Pro en 2 min**
```
Fichier : Aucun (Text-only)
Prompt : Voir SUPPORT_FORMATION p.XX
Temps : 3-4 min live
Résultat attendu : Email prêt à envoyer
```

**Démo 2 (S2) : Offre Devis depuis Spec Technique**
```
Fichier : Attachment H1 HVAC (PDF)
Prompt : [Template disponible]
Temps : 5 min (Upload + Generate)
Résultat : Devis 1-2 pages
```

---

### **GROUPE 2 - Supply Chain**

**Démo 1 (S1) : BOM Analysis en 2 min**
```
Fichier : BOMPRN (6) - Mehdi Dridi.pdf
Prompt : [Template SUPPORT_FORMATION]
Temps : 3-4 min (Upload peut être lent)
Résultat : Tableau risques + Recommandations
```

**Démo 2 (S2) : Comparaison Fournisseurs + Score**
```
Fichiers : 2 manuels onduleurs
Prompt : [Voir CARNET_EXERCICES Exercice 7]
Temps : 5 min
Résultat : Tableau comparatif + Score 0-100
```

---

### **GROUPE 3 - Études/SAV**

**Démo 1 (S1) : Manuel Technique → Synthèse Client**
```
Fichier : Manuel SUN2000-280KTL (Hiba)
Prompt : "Résume en 3 points pour client qui ne comprend PAS la technique"
Temps : 2-3 min
Résultat : Synthèse simple & claire
```

**Démo 2 (S2) : Comparaison Multi-Docs (Multimodal)**
```
Fichiers : 2-3 PDFs techniques
Prompt : [Voir SUPPORT_FORMATION]
Temps : 4-5 min
Résultat : Tableau comparatif + Recommandation
```

---

## 🛠️ MATÉRIEL & TECH CHECKLIST

**1 Semaine Avant :**
- [ ] Connexion Internet testée (vitesse > 10 Mbps recommandé)
- [ ] Compte Gemini créé (ou vérifier accès corporate)
- [ ] Fichiers participants téléchargés & testés
- [ ] Hotspot personnel préparé (backup)
- [ ] Slides PowerPoint prêtes (ou PDF)

**2 Jours Avant :**
- [ ] Tous les PDFs uploadés & testés dans Gemini
- [ ] Prompts démo copied/tested
- [ ] Salle visitée (Prise internet, Projecteur, Chaises)
- [ ] Feuilles de présence imprimées
- [ ] Certificats participants prêts

**1 Heure Avant :**
- [ ] Projecteur testé + Windows / Mac branché
- [ ] Microphone OK (test son)
- [ ] Gemini ouvert + Chat prêt
- [ ] Participant sample list disponible
- [ ] Eau / Café disponible

---

## 💡 CONSEILS FORMATEUR CLÉS

### Conseil 1 : Commencer par SUCCÈS Immédiat

**Ne pas faire :**
```
❌ "Voici la théorie du Deep Learning..."
❌ "Historique OpenAI vs Google..."
```

**À faire :**
```
✅ Démo 30 sec : Poser question → Gemini répond bien
✅ "Vous venez de voir l'IA en action. C'est aussi simple."
```

**Impact :** Engagement immédiat vs sommeil.

---

### Conseil 2 : Itération = Clé du Success

**Montrer le cycle :**
```
Réponse 1 : "C'est trop technique"
    ↓ [Feedback participant]
Réponse 2 : "Mieux, mais trop court"
    ↓ [Feedback]
Réponse 3 : "Parfait ! Prêt à envoyer"
```

**Impact :** Les participants comprennent que c'est un processus, pas magique.

---

### Conseil 3 : Spécificité Extremale

**Chaque prompt doit avoir :**
- ✅ Client EXACT (nom réel si possible)
- ✅ Contexte PRÉCIS (dates, chiffres, histoire)
- ✅ Contrainte claire (ton, longueur, format)

**Exemple Mauvais :**
```
"Rédige un email commercial"  ← Too generic
```

**Exemple Bon :**
```
"Rédige email pour Jean Dupont (Enercal), 
devis 45 000 EUR, 30j sans réponse, deadline mars,
150-200 mots, courtois mais ferme"  ← Spécifique
```

**Impact :** 10x Meilleur résultat.

---

### Conseil 4 : Gérer Hétérogénéité Niveaux

**Groupe aura :**
- 1-2 persons très à l'aise (Rapides)
- 5-6 "Intermédiaires" (Standard)
- 1-2 Débutants purs (Lents)

**Stratégie :**

```
PENDANT ATELIER PRATIQUE :

Les Rapides :
  → Défi bonus : "Trouve 2 variantes du prompt"
  → Les mentorer sur cas suivant

Les Standard :
  → Follow exercice normal

Les Lents :
  → "Buddy system" (pair avec Standard)
  → Faciliter accès ordi/login
```

---

### Conseil 5 : Les Peurs à Défuser

**Peur 1 : "L'IA va voler mon job"**
```
Réponse : "Gemini n'a jamais 10 ans d'expérience terrain. 
           Vous ajoutez la valeur expérience + jugement."
```

**Peur 2 : "C'est trop compliqué pour moi"**
```
Réponse : "Vous envoyez déjà 20 emails par jour. 
           C'est juste... plus rapide et mieux écrit."
```

**Peur 3 : "Les données ne sont pas sécurisées"**
```
Réponse : "Bon point. Avec plan payant Gemini Pro, 
           c'est chiffré end-to-end. IT a approuvé."
```

---

## 📈 MESURER LE SUCCÈS

**Jour 1 (Immédiat) :**
- ✅ > 80% des participants ont essayé Gemini
- ✅ Tous ont lancé au moins 1 prompt
- ✅ Feedback "C'est rapide !" entendu

**Semaine 1 (Post) :**
- ✅ > 70% ont utilisé hors formation
- ✅ 1-2 success stories partagées
- ✅ 0 abandons (groupe Discord actif)

**Mois 1 (Impact) :**
- ✅ 3-5 cas d'usage en production
- ✅ Gain temps mesurable : 50%+ sur tâche ciblée
- ✅ Satisfaction : 4/5 ou mieux

---

## 🚀 MATÉRIEL À PRÉPARER

### Document 1 : Templates Prompts Personnalisés

**Par groupe, créer fichier avec 20 templates :**

```
FILE : TEMPLATES_PROMPTS_GROUPE1.docx

Sections :
1. Rédaction Email [5 templates]
2. Rédaction Contrats [5 templates]
3. Analyse Documents [5 templates]
4. Data/Excel [5 templates]

Chaque template :
- Titre clair
- Cas d'usage
- Prompt complet (copy-colle ready)
- Exemple résultat
```

---

### Document 2 : Checklist Bonnes Pratiques

```
APRÈS FORMATION - À FAIRE

□ JOUR 1 : Essayer Gemini sur 1 cas simple perso
□ JOUR 3 : Tester cas réel du boulot
□ JOUR 7 : Générer 1ère utilisation production
□ JOUR 14 : Documenter votre cas d'usage
□ JOUR 21 : Partager prompt à équipe
□ JOUR 30 : Proposer amélioration process

Si bloqué → Post dans Groupe Whatsapp
```

---

### Document 3 : FAQ Support

```
Q: Je me suis trompé dans le prompt, comment recommencer ?
A: Cliquez "+" pour nouveau chat. Ancien chat reste en historique.

Q: Gemini n'a pas répondu correctement...
A: Normal, c'est machine learning. Essayer reformuler.
   Tips : Plus contexte = Meilleur résultat

Q: Comment uploader un fichier ?
A: Cliquez clip 📎 en bas de chat, sélectionnez PDF/Excel.
   Note : Fichier max 100 MB.

Q: Mes données uploadées, où vont-elles ?
A: Serveurs Google sécurisés. Plan payant = données non-utilisées 
   pour training. À vérifier avec IT avant.
```

---

## 🎁 LIVRABLES PARTICIPANTS

**Chacun reçoit :**
1. ✅ Clé USB avec 5 fichiers :
   - Support_Formation_Complet.pdf
   - Carnet_Exercices.pdf
   - Templates_Prompts_[Groupe].docx
   - Checklist_30Jours.pdf
   - FAQ_Support.docx

2. ✅ Accès 1 an à Base Prompts Commune (Google Drive)

3. ✅ Certificat Participation (Signé, Tamponné)

4. ✅ Contact Formateur (Email + WhatsApp pour support)

---

## ⚡ GESTION CRISES DAY-OF

| Problème | Solution |
|----------|----------|
| Internet tombe | Hotspot personal + Slides offline |
| Projecteur cassé | Tableau blanc + Participant partage écran via WhatsApp |
| Participant bébé ne marche pas | Pairer avec collègue, observer first |
| Temps manque | Cuts "Bonus" sections, focus "Quick wins" |
| Demandes au-delà scope | Note pour "Follow-up optionnel", after formation |

---

## 📞 APRÈS FORMATION

**Semaine 1 :**
- Email récap + Templates
- Lien groupe WhatsApp
- 1 coaching collectif (30 min optional)

**Semaine 2-4 :**
- Support via WhatsApp (Questions)
- Monitoring adoption (Survey)
- Highlight "Champions" (Early adopters)

**Mois 2 :**
- Atelier suivi optionnel (2h)
- Documenter best practices collectifs
- Annoncer "Phase 2" avancée (si interest)

---

## ✅ CHECKLISTE FINALE (À IMPRIMER)

```
JOUR DE FORMATION - DERNIER CHECK

LIEU & LOGISTIQUE
☐ Salle réservée confirmée
☐ Projecteur + cables testés
☐ Chaises assez nombreuses
☐ Tableau blanc + marqueurs
☐ Eau + Café disponible

MATÉRIEL PÉDAGOGIQUE
☐ Support print disponible (20 copies)
☐ Carnet exercices print (20 copies)
☐ Certificats prêts
☐ Clé USB preparée (5 copies min)
☐ Feuilles présence

TECH & INTERNET
☐ WiFi testé (vitesse OK)
☐ Gemini login OK
☐ Fichiers uploadés & testés
☐ Hotspot personnel chargé
☐ Browser backup onglet ouvert

FORMATEUR PREP
☐ Slides prêtes
☐ Demos testées (2x)
☐ Prompts print en main
☐ Timing practicé
☐ Gestion peurs préparée (Script)

PARTICIPANT LIST
☐ Liste présence
☐ Contacts emails
☐ Niveau initial (à demander)
☐ Cas d'usage perso collectés

JOUR J - 30 MIN AVANT
☐ Projecteur ON + Image nette
☐ Micro testé
☐ Salle aérée
☐ Gemini ready to go
☐ Café/Water servi

APRÈS SÉANCE
☐ Feedback forms collectés
☐ Certificats distribués
☐ Clé USB distribuée
☐ Contacts formateur partagés
☐ Photos groupe (motivation)
☐ Merci email envoyé (24h)
```

---

**Formation Prête à Lancer ! Bonne Chance 🚀**

*Document Support Formateur v1.0 | 20 Janvier 2026*
