# 5. Swaps multiples et règlement net

batchSwap exécute plusieurs étapes et cumule un delta pour chaque actif.
Un delta positif est dû au Vault ; un delta négatif est versé au destinataire.
Seuls les montants nets sont transférés après les étapes.
Un montant nul peut reprendre le résultat calculé à l’étape précédente.
Cette convention exige un enchaînement compatible et ne fonctionne pas au premier swap.
Les limites signées portent sur chaque delta final.

Source : [code du dépôt](../../pkg/vault/contracts/Swaps.sol).

Suite : [Entrer et sortir d’un pool](06-liquidite.md).
