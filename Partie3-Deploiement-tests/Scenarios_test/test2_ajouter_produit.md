# Test 2 — Ajouter un produit au catalogue

## Informations générales

| Champ | Détail |
|-------|--------|
| Module | Inventaire |
| Fonctionnalité testée | Création d'une fiche produit |
| Chemin | Inventaire → Produits → Nouveau |
| Date d'exécution | 23/03/2026 |
| Statut | Réussi ✅ |

## Objectif

Vérifier que le module Inventaire permet d'ajouter des produits au catalogue avec leur prix de vente et leur quantité en stock.

## Données de test

| Désignation | Prix de vente | Quantité en stock |
|-------------|--------------|-------------------|
| Ordinateur portable HP | 450 000 CFA | 15 unités |
| Souris sans fil Logitech | 15 000 CFA | 50 unités |
| Clavier USB Dell | 10 500 CFA | 40 unités |
| Écran 24 pouces Samsung | 145 000 CFA | 10 unités |
| Disque dur externe 1To | 22 000 CFA | 25 unités |

## Étapes réalisées

1. Aller dans le module **Inventaire**
2. Cliquer sur **Produits** dans le menu du haut
3. Cliquer sur **Nouveau**
4. Remplir les champs Nom, Prix de vente et Quantité en stock
5. Cliquer sur **Enregistrer**
6. Répéter pour les 5 produits

## Résultat obtenu

Les 5 produits ont été créés avec succès. Ils apparaissent dans le catalogue avec leurs prix et quantités en stock affichés en temps réel (1-5 / 5).

## Capture d'écran

`test2_produits_liste.png` — Catalogue des 5 produits avec prix et stocks
