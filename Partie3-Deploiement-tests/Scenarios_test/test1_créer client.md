# Test 1 — Créer une fiche client

## Informations générales

| Champ | Détail |
|-------|--------|
| Module | Vente |
| Fonctionnalité testée | Création d'une fiche client |
| Chemin | Vente → Commandes → Clients → Nouveau |
| Date d'exécution | 23/03/2026 |
| Statut | Réussi ✅ |

## Objectif

Vérifier que le module Vente permet de créer et enregistrer une fiche client avec ses informations complètes.

## Données de test

| Champ | Client 1 | Client 2 | Client 3 |
|-------|----------|----------|----------|
| Nom | TechStore Cotonou | InfoPlus Bénin | DigiMarket Abomey |
| Email | techstore@gmail.com | infoplus@gmail.com | digimarket@gmail.com |
| Localisation | Cotonou, Bénin | Calavi, Bénin | Abomey, Bénin |

## Étapes réalisées

1. Aller dans le module **Vente**
2. Cliquer sur **Commandes** dans le menu du haut
3. Cliquer sur **Clients**
4. Cliquer sur **Nouveau**
5. Remplir les champs Nom, Email et Localisation
6. Cliquer sur **Enregistrer**
7. Répéter pour les 3 clients

## Résultat obtenu

Les 3 clients ont été créés avec succès et apparaissent dans la liste clients (1-3 / 3).

## Capture d'écran

`test1_clients_liste.png` — Liste des 3 clients créés
