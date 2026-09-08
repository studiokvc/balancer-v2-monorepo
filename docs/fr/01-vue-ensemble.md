# 1. Un DEX à pools pondérés

Balancer V2 sépare la conservation des tokens et leur formule de prix.
Le Vault conserve les actifs ; chaque pool calcule les échanges selon ses règles.
Un pool pondéré peut viser une répartition 80/20 plutôt que 50/50.
Les arbitragistes échangent lorsque le prix du pool diffère des autres marchés.
Les fournisseurs de liquidité détiennent des BPT représentant leur participation.
Ce parcours étudie V2 ; il ne décrit pas Balancer V3.

Source : [code du dépôt](../../pkg/pool-weighted/contracts/BaseWeightedPool.sol).

Suite : [Vault et comptabilité par pool](02-vault.md).
