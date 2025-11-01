# First Xperience — Application de suivi de recherche d’emploi

## Présentation

**First Xperience** est un prototype d’application web destiné à accompagner les personnes en recherche d’emploi, notamment les jeunes diplômés.
 Elle permet aux demandeurs d'emploi d'organiser, suivre et optimiser leurs candidatures grâce à un tableau de bord intelligent, des statistiques personnalisées, un outil de préparation aux entretiens, et l'accès direct à des offres d'emploi en ligne.
Ce projet a été développé en Python à l'aide du framework Streamlit.

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
```
---

## Installation & Exécution

### Installer les dépendances

```bash
pip install -r requirements.txt
```

Puis lancez l'application via le point d'entrée :

```bash
streamlit run Accueil.py
```

## Construit avec
- Streamlit : Interface front et routing
- Pandas : Gestion des données
- Python / CSV : Stockage local des comptes, candidatures et notes entretien
- RapidAPI (jSearch) : Recherche d’offres d’emploi
- Pathlib : Gestion de fichier

## Auteurs
GRILLON Pauline,
BA Ibrahima


