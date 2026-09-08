# 4. Échange et protection du montant

swap reçoit un pool, deux actifs, un montant et un mode.
GIVEN_IN fixe l’entrée et impose une sortie minimale.
GIVEN_OUT fixe la sortie et impose une entrée maximale.
Le Vault demande le calcul au hook onSwap, puis met à jour les balances.
Il applique la limite et la deadline avant de terminer les transferts.
Une cotation antérieure ne garantit donc pas le résultat d’une transaction ultérieure.

Source : [code du dépôt](../../pkg/vault/contracts/Swaps.sol).

Suite : [Swaps multiples et règlement net](05-batch.md).
