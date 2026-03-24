# Test 6 — Créer une fiche employé

## Informations générales

| Champ | Détail |
|-------|--------|
| Module | Employés |
| Fonctionnalité testée | Création de fiches employés |
| Chemin | Employés → Nouveau |
| Date d'exécution | 23/03/2026 |
| Statut | Réussi ✅ |

## Objectif

Vérifier que le module Employés permet de créer des fiches employés avec leur poste, leur département et leurs informations professionnelles.

## Données de test

| Nom | Poste | Département |
|-----|-------|-------------|
| Administrator | Administrateur ERP | Administration |
| Béatrice | Administratrice adjoint | Administration |
| Damien Goal | Responsable RH | Ressources Humaines |
| Jean-Pierre Adjovi | Comptable | Finance |
| Aïcha Traoré | Gestionnaire de Stock | Logistique |
| Kofi Mensah | Responsable Commercial | Ventes |

## Étapes réalisées

1. Aller dans le module **Employés**
2. Cliquer sur **Nouveau**
3. Remplir les champs Nom, Poste et Département
4. Cliquer sur **Enregistrer**
5. Répéter pour les 6 employés

## Résultat obtenu

Les 6 employés ont été créés avec succès et apparaissent dans la liste (1-6 / 6). Ils sont organisés par département : Administration (2), Finance (1), Logistique (1), Ressources Humaines (1) et Ventes (1). Chaque fiche employé affiche les informations professionnelles complètes : poste, département, fuseau horaire (Africa/Porto-Novo) et adresse professionnelle (Bénin).

## Captures d'écran

- `test6_gestion_employes_1.png` — Liste des 6 employés organisés par département
- `test6_gestion_employes_2.png` — Fiche détaillée d'Aïcha Traoré (Gestionnaire de Stock, Logistique)
