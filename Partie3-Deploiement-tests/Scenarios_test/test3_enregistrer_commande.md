# Test 3 — Enregistrer une commande client

## Informations générales

| Champ | Détail |
|-------|--------|
| Module | Vente |
| Fonctionnalité testée | Création et confirmation d'une commande client |
| Chemin | Vente → Commandes → Nouveau |
| Date d'exécution | 23/03/2026 |
| Statut | Réussi ✅ |

## Objectif

Vérifier que le module Vente permet d'enregistrer une commande client avec plusieurs produits et de la confirmer.

## Données de test

### Commande 1 — S00001
| Champ | Valeur |
|-------|--------|
| Client | TechStore Cotonou |
| Produit 1 | Ordinateur portable HP — Qté 2 — 900 000 CFA |
| Produit 2 | Souris sans fil Logitech — Qté 5 — 75 000 CFA |
| Total HT | 975 000 CFA |
| TVA 18% | 175 500 CFA |
| Total TTC | 1 150 500 CFA |

### Commande 2 — S00002
| Champ | Valeur |
|-------|--------|
| Client | InfoPlus Bénin |
| Produit 1 | Clavier USB Dell — Qté 10 — 105 000 CFA |
| Produit 2 | Écran 24 pouces Samsung — Qté 1 — 145 000 CFA |
| Total HT | 387 000 CFA |
| TVA 18% | 69 660 CFA |
| Total TTC | 456 660 CFA |

## Étapes réalisées

1. Aller dans le module **Vente**
2. Cliquer sur **Commandes** dans le menu du haut
3. Cliquer sur **Nouveau**
4. Sélectionner le client dans le champ Client
5. Ajouter les lignes de produits avec les quantités
6. Cliquer sur **Confirmer**
7. Répéter pour la deuxième commande

## Résultat obtenu

Les 2 commandes ont été confirmées avec succès. Elles apparaissent dans la liste avec les numéros S00001 et S00002, le statut **À facturer** et les montants corrects.

## Capture d'écran

`test3_commandes_liste.png` — Liste des 2 commandes confirmées
