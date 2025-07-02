# 🧠 Moneyball FM24 – Optimisation des Transferts sur Football Manager 2024

Ce projet met en œuvre une approche **Moneyball** pour le jeu *Football Manager 2024* sur PC.  
L’objectif est d’utiliser des **données objectives** pour :
- recruter efficacement,  
- maximiser la performance,  
- minimiser les coûts.

Le tout en s’inspirant de la stratégie de recrutement popularisée dans le baseball (voir le film *Le Stratège* avec Brad Pitt) et adaptée ici au football.

<p align="center">
  <img src="https://github.com/user-attachments/assets/47ecaded-7ab7-4b28-a8f0-cca13ce2b532" alt="Moneyball FM" width="400"/>
  <img src="https://github.com/user-attachments/assets/363f834c-a87a-40a4-9a7c-161e6da09299" alt="Exemple Analyse" width="400"/>
</p>

---

## ⚽ Objectifs du projet

- 🔎 Analyser des données de joueurs (de ma partie FM24 en cours) pour détecter des profils sous-évalués.
- 🧩 Trouver des profils intéressants selon les **besoins du club** et les **contraintes budgétaires**.
- 📊 Remplacer le scouting subjectif par une approche **basée sur des données chiffrées** : âge, salaire, note moyenne, xG, etc.

> 🗂️ Le tout sera d'abord fait sur **Excel**, avec une possibilité future d’extraire les données dans une base **NoSQL** (type MongoDB).

---

## 📘 C’est quoi le Moneyball ?

Le Moneyball est une méthode de recrutement fondée sur l’analyse statistique et l’exploitation de données pour repérer des joueurs **sous-cotés** et **rentables**, plutôt que de se fier uniquement à l’œil du recruteur ou au prestige.  
Popularisée dans le baseball (Oakland A’s), cette approche est de plus en plus utilisée dans le football moderne.

📺 [Voir une explication en vidéo (YouTube)](https://youtu.be/mrwwVoD1RQQ?si=6I0QXe_wGcVY_WRI)

---

## 🎮 Contexte de la partie en cours

Je joue actuellement avec **le club espagnol Cultural Leonesa**, fraîchement promu en **3e division espagnole** après deux promotions successives.

<p align="center">
  <img src="https://github.com/user-attachments/assets/6ec01243-2307-423d-9e4b-0b73a0148e16" alt="Cultural Leonesa" width="600"/>
</p>

Le club dispose d’une **enveloppe de 13,4 millions d’euros** pour préparer la saison à venir :

<p align="center">
  <img src="https://github.com/user-attachments/assets/f104981b-2190-4d7a-a31b-05b9b4fad042" alt="Budget transfert" width="500"/>
</p>

### 🔧 Besoins de l’effectif

L’effectif est à reconstruire :  
- Recrutements nécessaires **à chaque poste**.  
- Les remplaçants seront issus de l’effectif actuel ou du **centre de formation**.

<p align="center">
  <img src="https://github.com/user-attachments/assets/d7508fd9-f000-4f1d-92f9-cffb12ffefd7" alt="Effectif actuel" width="600"/>
</p>

---

## 📥 Récupération des données

Je vais récupérer les données des **joueurs ayant joué au moins 450 minutes** cette saison, pour garantir une **base statistique fiable**.  

Critères de sélection :
- Championnats des pays avec les **meilleurs coefficients FIFA**.
- **Valeur maximale : 2,5 millions d’euros**, pour rester dans le budget transfert.
- Objectif : identifier les **joueurs sous-évalués et performants**.

---

## 🎯 Étape 1 – Trouver un buteur

Première mission : identifier un **buteur rentable et performant** dans cette fourchette de prix.

<p align="center">
  <img src="https://github.com/user-attachments/assets/efb4e19b-59d5-4909-ac4c-3bd6ba14e519" alt="Recherche buteur" width="600"/>
</p>

---

## 📊 Données récupérées – Poste : Buteur

Données collectées pour un premier tri :
- Minutes jouées
- xG, buts, tirs cadrés
- Valeur marchande
- Salaire et âge
- Ratio buts/minutes
- Autres indicateurs avancés

---

🔄 La suite très bientôt, avec les premières analyses de profils !

