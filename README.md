# Projet 2 — Conception et Déploiement d'un ERP avec Odoo

**Université d'Abomey-Calavi — Institut de Formation et de Recherche en Informatique (IFRI)**
**Année académique 2025-2026**
**Enseignant : Dr TABA CHABI K Wahabou**

---

## Contexte

TechDistrib SARL est une entreprise fictive spécialisée dans la distribution de matériel
informatique. Ce projet consiste à concevoir et déployer un ERP basé sur Odoo pour
automatiser et intégrer ses processus métier (commercial, stock, comptabilité, RH).

---

## Structure du dépôt
```
ERP-TechDistrib-SARL/
│
├── Analyse-conception/
│   ├── rapport_partie1.docx
│   ├── diagramme_cas_utilisation.svg
│   ├── diagramme_classes.svg
│   ├── diagramme_sequence.svg
│   └── diagramme_activites.svg
│
├── Installation-configuration/
│   ├── docker-compose.yml
│   ├── rapport_partie2.docx
│   └── captures/
│       ├── 01_odoo_accueil.png
│       ├── 02_module_crm.png
│       ├── 03_module_inventaire.png
│       ├── 04_module_comptabilite.png
│       ├── 05_module_rh.png
│       └── 06_donnees_test.png
│
├── Deploiement-tests/
│   ├── rapport_partie3.docx
│   ├── scenarios_tests/
│   │   ├── test1_creer_client.md
│   │   ├── test2_ajouter_produit.md
│   │   ├── test3_enregistrer_commande.md
│   │   ├── test4_generer_facture.md
│   │   ├── test5_gestion_stock.md
│   │   └── test6_gestion_employes.md
│   ├── captures_tests/
│   └── questions_reflexion.md
│
└── rapport-final/
    └── Rapport_ERP_TechDistrib_SARL_Final.docx
```

---

## Technologies utilisées

| Technologie | Version | Rôle |
|-------------|---------|------|
| Odoo | 16 | Plateforme ERP |
| PostgreSQL | 15 | Base de données |
| Docker Compose | — | Orchestration des conteneurs |

---

## Lancer le projet en local
```bash
# Cloner le dépôt
git clone https://github.com/<votre-compte>/ERP-TechDistrib-SARL.git
cd ERP-TechDistrib-SARL

# Démarrer les conteneurs
cd Installation-configuration
docker-compose up -d

# Accéder à Odoo
# Ouvrir http://localhost:8069 dans le navigateur
```

---

## Contenu par partie

**Analyse & Conception**
Analyse des besoins, modélisation UML (cas d'utilisation, classes, séquence, activités)
et planification Scrum du projet.

**Installation & Configuration**
Déploiement d'Odoo via Docker Compose, configuration des modules CRM, Inventaire,
Comptabilité et Ressources Humaines, avec données de test.

**Déploiement & Tests**
Exécution des 6 scénarios de test fonctionnels, captures d'écran des résultats
et réponses aux questions de réflexion sur les ERP.
