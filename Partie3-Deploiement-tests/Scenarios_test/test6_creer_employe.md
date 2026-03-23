# Test 6 — Créer une fiche employé

## Informations générales

| Champ | Détail |
|-------|--------|
| Module | Employés |
| Fonctionnalité testée | Création d'une fiche employé |
| Chemin | Employés → Nouveau |
| Date d'exécution | 23/03/2026 |
| Statut | Réussi ✅ |

## Objectif

Vérifier que le module Employés permet de créer des fiches employés avec leur poste, leur département et leurs informations professionnelles.

## Données de test

| Nom | Poste | Département |
|-----|-------|-------------|
| Kofi Mensah | Responsable Commercial | Ventes |
| Aïcha Traoré | Gestionnaire de Stock | Logistique |
| Jean-Pierre Adjovi | Comptable | Finance |

## Étapes réalisées

1. Aller dans le module **Employés**
2. Cliquer sur **Nouveau**
3. Remplir les champs Nom, Poste et Département
4. Cliquer sur **Enregistrer**
5. Répéter pour les 3 employés

## Résultat obtenu

Les 3 employés ont été créés avec succès et apparaissent dans la liste (1-4 / 4 en comptant l'administrateur système). Chaque fiche employé est accessible et affiche les informations professionnelles complètes : poste, département, fuseau horaire (Africa/Porto-Novo) et adresse professionnelle (Bénin).

## Captures d'écran

- `test5_employes_liste.png` — Liste des employés par département
- `test6_employe_fiche.png` — Fiche détaillée d'Aïcha Traoré
