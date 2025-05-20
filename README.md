# 🦷 DentalCare — Plateforme Web de Gestion Dentaire

## 📘 Contexte du projet

**DentalCare** est une application web développée avec **Laravel** et **Blade**, visant à gérer l’activité d’un ou plusieurs cabinets dentaires. Elle permet :

- aux **patients** de prendre rendez-vous en ligne,
- aux **praticiens** (dentistes) de gérer leur planning et les dossiers médicaux,
- aux **administrateurs** de superviser le tout à travers un tableau de bord centralisé.

L’application suit l’architecture **MVC**, sans utilisation d’API externe, et repose sur une base de données relationnelle bien structurée.

---

## 👥 Profils Utilisateurs

- 🧑‍🦱 Patient  
- 🧑‍⚕️ Praticien (dentiste)  
- 🧑‍💼 Administrateur  

---

## 🧩 Fonctionnalités Principales

### 🔐 Authentification & Rôles

- Authentification sécurisée .
- Gestion des rôles : `patient`, `praticien`, `admin`.
- Redirection automatique vers un **dashboard** selon le rôle.

---

### 👨‍⚕️ Patient

- Inscription / Connexion.
- Prise de **rendez-vous** via un calendrier interactif.
- Consultation des **rendez-vous à venir** ou passés.
- Possibilité de **reporter ou annuler** un rendez-vous.
- Accès à un **dossier médical simplifié**, rempli par le praticien.

---

### 🦷 Praticien

- Tableau de bord personnalisé.
- Vue complète de son **planning de rendez-vous**.
- Validation, modification ou annulation des rendez-vous.
- Accès aux **fiches patients** avec ajout de :
  - Diagnostics
  - Traitements réalisés
  - Prescriptions

---

### 🛠️ Administrateur

- Gestion des **praticiens** (ajout, modification, désactivation).
- Définition des **plages horaires disponibles** pour les rendez-vous.
- Vue d’ensemble de **tous les rendez-vous** du cabinet.
- Statistiques :
  - Taux de remplissage
  - Nombre de patients actifs
  - Nombre de consultations par semaine

---

## 🧪 Extra / Features

- 📅 Intégration d’un **calendrier dynamique** (via JavaScript) dans la prise de rendez-vous.
- 📧 Envoi de **notifications email** pour confirmer ou modifier un rendez-vous (via Mailtrap).
- 📊 **Dashboard statistique** avec graphiques (Chart.js).
- 🔍 **Recherche de praticiens** par spécialité ou créneaux disponibles.

---


### 🔍 Soutenance

- **1** : Démonstration utilisateur (navigation, prise de rendez-vous…)
- **2** : Explication du code (routes, contrôleurs, modèles, vues)
- **3** : Session de **questions/réponses** (bonnes pratiques, structure, choix techniques)

---

## ✅ Bon courage dans le développement de DentalCare !
