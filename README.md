# 🌌 TP API S7-300 : Programmation Avancée (Master Edition)

![TIA Portal](https://img.shields.io/badge/TIA_Portal-V21-blue?style=for-the-badge&logo=siemens)
![HTML5](https://img.shields.io/badge/HTML5-Glassmorphism-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![UI Theme](https://img.shields.io/badge/UI_Theme-Deep_Space_%26_Pixel-BB86FC?style=for-the-badge)

Une application web interactive *(Single-Page Application)* développée comme compte-rendu académique intégral pour le TP d'Automatique Avancée sur automate Siemens S7-300. 

Cette version exhaustive rassemble la préparation théorique, la traduction en langages industriels (LADDER / IL), des GRAFCETs interactifs, et des explications détaillées des mécanismes de mémorisation. Le tout est présenté dans une interface "Astronomie" (Deep Space, Glassmorphism et lueurs néon).

---

## 🎓 Contexte Académique

* **Université :** Université des Sciences et de la Technologie Houari Boumediene (USTHB)
* **Faculté :** Génie Électrique | Département d'Automatique
* **Niveau :** Master 1 - Automatique et Informatique Industrielle (AII)
* **Module :** Automates Programmables Industriels (API)
* **Professeure :** Dr. Achouri Fouzia
* **Année Universitaire :** 2025 / 2026

### 👨‍🚀 Équipe de Développement (Binôme) :
* **Dahane Ahmed Lamine**
* **Meriem Tabbi**

---

## ✨ Structure et Contenu Pédagogique

Ce projet a été architecturé en quatre sections distinctes pour répondre rigoureusement au cahier des charges :

### 1. Introduction et Objectifs
* Définition des objectifs d'implémentation sous TIA Portal.
* Rappels théoriques sur le cycle de scrutation de l'API S7-300 et les principes de mémorisation du GRAFCET.

### 2. Préparation Théorique
* Élaboration des tables des variables (E/S) pour l'adressage physique.
* Implémentation du système en **langage IL (Instruction List / AWL)**, optimisé pour les temps de cycle courts.

### 3. Partie 1 : Système de Remplissage de Cuve
* **GRAFCET interactif** avec animations des étapes et transitions.
* **Explication du mécanisme :** Analyse textuelle de la condition de niveau bas (LSL), de la mémorisation de la pompe, et de la validation de stabilité (Temporisateur TON de 10s) déclenchée par le niveau haut (LSH).
* Schéma de commande en **langage LADDER**.

### 4. Partie 2 : Poste d'Usinage Automatisé
* **GRAFCET interactif (Tâches simultanées) :** Mise en évidence visuelle de la divergence et convergence en ET.
* **Explication du mécanisme :** Description de la séquence asynchrone (Départ cycle, Serrage), de l'activation parallèle des usinages (Fraisage et Lamage), et de la contrainte matérielle liée au distributeur **monostable** lors de l'éjection.
* Schéma de commande LADDER illustrant les bobines SET/RESET et la divergence logique.

---

## 🚀 Comment lancer le projet ?

Ce projet est conçu pour être une documentation interactive **100% autonome**. Il ne nécessite aucune installation de serveur (ni Node.js, ni XAMPP) ni de base de données.

1. Clonez ce dépôt sur votre machine locale :
   ```bash
   git clone [https://github.com/votre-nom-utilisateur/tp-api-s7300-master.git](https://github.com/votre-nom-utilisateur/tp-api-s7300-master.git)
