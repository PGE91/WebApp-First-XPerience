# First Xperience — Application de suivi de recherche d’emploi

## Présentation

**First Xperience** est un prototype d’application web destiné à accompagner les personnes en recherche d’emploi, notamment les jeunes diplômés.

L'outil permet :

✅ d'organiser et suivre ses candidatures  
✅ d'analyser sa recherche via des statistiques personnalisées  
✅ de préparer ses entretiens  
✅ et de rechercher des offres d'emploi en ligne  

Développé en **Python** avec le framework **Streamlit**.

---

## Fonctionnalités principales

### Gestion des utilisateurs
- Création de compte / Connexion / Déconnexion  
- Mot de passe sécurisé via **hachage SHA-256**

### Tableau de bord & suivi
- Suivi complet des candidatures
- Statuts personnalisés

### Ajout de candidatures
- Formulaire détaillé : entreprise, poste, secteur, date, notes, statut

### Statistiques
- Taux de réponse
- Délai moyen
- Secteurs les plus réactifs

### Préparation à l'entretien
- Checklists
- Notes par entreprise
- Questions types

### Offres d'emploi via API externe
- Recherche d'offres selon un poste (API **RapidAPI — jSearch**)

---

## Structure du dépôt
```plaintext
first_xperience/
├── Accueil.py                <-- Point d’entrée Streamlit
├── pages/
│   ├── connexion.py
│   ├── creation_compte.py
│   ├── Mon_suivi.py
│   └── Offres_emploi.py
├── donnees/
│   ├── candidatures.csv
│   ├── notes_entretien.csv
│   ├── utilisateurs.csv
├── image_accueil.png
└── requirements.txt


