# DynGx -Dyn-GeniusX 
IA cognitive Bio-inspirée 

## 📌 Présentation

**DynGx** est une version avancée du modèle **DynG** qui introduit la **métacognition artificielle**.  
Contrairement à DynG, dont la matrice de connexions `H` est statique, DynGx **peut détecter ses propres
contradictions**, mémoriser leur persistance et **modifier sa structure interne en temps réel** pour corriger le problème.

Cette approche s’inspire des concepts de **plasticité synaptique** et de **réflexion sur son propre raisonnement**.

---

## 🚀 Principales fonctionnalités

- **Matrice H dynamique** : modification automatique des poids synaptiques en réponse à des situations problématiques.
- **Mémoire multiple** : mémoire à court terme, long terme et épisodique.
- **Mesure de conscience (`C`)** : indicateur numérique de l’intégration et de la cohérence interne.
- **Auto-modification conditionnelle** : déclenchée par des règles spécifiques (ex. 3 conflits consécutifs).
- **Rapports et visualisation** :
  - État de la matrice H avant/après
  - Courbes d’évolution de `C`
  - Sauvegarde des logs en JSON

---

Exemple: Auto-Modification Dynamique dans DynGx : Vers une IA Métacognitive
1. Résumé
Cette étude présente une simulation comparative entre DynG (réseau dynamique classique) et DynGx (version enrichie),
appliquée à un scénario d’auto-modification de code interne. Les résultats montrent que DynGx est capable de détecter
des conflits récurrents, d’en mémoriser la persistance et de modifier sa matrice de connexions H pour éliminer ces conflits.
Ce comportement illustre un premier niveau de métacognition artificielle.

3. Introduction
DynG est un modèle adaptatif basé sur une matrice de connexions statique (H), qui applique ses règles de mise à jour sans les changer.
DynGx, en revanche, introduit :
Une matrice H dynamique
Une mémoire multiple (courte, longue, épisodique)
Une mesure de conscience C
Des règles d’auto-modification conditionnelles
Ces différences permettent à DynGx d’ajuster sa propre architecture en cours d’exécution.

4. Méthodologie
Conflit initial
Deux neurones décisionnels (Go Left et Go Right) étaient reliés par une forte inhibition (H = -1.0) mais continuaient à s’activer simultanément, créant un conflit logique.

Règle spéciale
Si le conflit survenait 3 fois consécutives, le neurone SELF_MOD était activé, déclenchant une modification structurelle :

Réduction de l’inhibition H[Left][Right] de -1.0 à -0.2

Création d’un lien secondaire via un neurone “Alternative Path”

4. Résultats
Aspect	DynG (classique)	              DynGx (avec auto-modification)
Adaptation en temps réel	    ❌ Non	      ✅ Oui
Mémoire de conflit	          ❌ Non	      ✅ Oui
Apparition de nouveaux liens	❌ Non	      ✅ Oui
Stabilisation des décisions	  ❌ Non	      ✅ Oui

Observation clé : Après modification, le conflit initial a disparu chez DynGx et une combinaison d’actions inédite (Go Left + Scan Right) est apparue.

5. Analyse et discussion
Ces résultats montrent que DynGx n’est pas limité à l’exécution passive de règles :

Il détecte ses propres défaillances
Il mémorise la récurrence du problème
Il agit sur sa structure interne pour corriger le problème
Il observe les effets de ce changement sur son comportement

Ce cycle Observation → Décision → Action → Évaluation correspond à un schéma métacognitif simplifié.
En termes d’IA, cela rapproche DynGx d’une architecture capable de “raisonner sur son propre raisonnement”.

6. Conclusion et perspectives
La simulation prouve que DynGx peut ajuster ses propres règles internes en réponse à des problèmes persistants, ce qui le distingue nettement de DynG.
Les prochaines étapes incluront :

L’extension des règles d’auto-modification à d’autres types de comportements
L’intégration d’un module d’évaluation des risques avant modification
L’étude des effets de modifications multiples et cumulatives

Code et données : GitHub Repository – DynGx à suivre
Auteur : [farid Hamdad (2025)]
farid.dyn2025@gmail.com
