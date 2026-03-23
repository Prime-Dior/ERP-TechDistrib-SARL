# Test 4 — Générer une facture

## Informations générales

| Champ | Détail |
|-------|--------|
| Module | Facturation |
| Fonctionnalité testée | Génération automatique d'une facture depuis une commande |
| Chemin | Vente → Commandes → ouvrir commande → Créer une facture |
| Date d'exécution | 23/03/2026 |
| Statut | Réussi ✅ |

## Objectif

Vérifier que le système génère automatiquement une facture à partir d'une commande confirmée et que la facture peut être validée (comptabilisée).

## Données de test

### Facture 1 — FAC/2026/00001
| Champ | Valeur |
|-------|--------|
| Client | InfoPlus Bénin |
| Commande source | S00002 |
| Montant HT | 387 000 CFA |
| TVA 18% | 69 660 CFA |
| Total TTC | 456 660 CFA |
| Statut | Comptabilisé |

### Facture 2 — FAC/2026/00002
| Champ | Valeur |
|-------|--------|
| Client | TechStore Cotonou |
| Commande source | S00001 |
| Montant HT | 975 000 CFA |
| TVA 18% | 175 500 CFA |
| Total TTC | 1 150 500 CFA |
| Statut | Comptabilisé |

## Étapes réalisées

1. Ouvrir la commande S00001 dans le module **Vente**
2. Cliquer sur **Créer une facture**
3. Confirmer la création dans la fenêtre qui apparaît
4. Cliquer sur **Confirmer** pour comptabiliser la facture
5. Répéter pour la commande S00002

## Résultat obtenu

Les 2 factures ont été générées automatiquement avec les lignes de produits, les quantités et les montants repris directement des commandes sources. La TVA de 18% a été appliquée automatiquement. Les deux factures sont au statut **Comptabilisé**.

## Captures d'écran

- `test4_factures_liste.png` — Liste des 2 factures comptabilisées
- `test4_facture_detail.png` — Détail de la facture FAC/2026/00002
