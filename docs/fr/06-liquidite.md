# 6. Entrer et sortir d’un pool

joinPool et exitPool appellent les hooks du pool puis règlent les tokens.
Le pool gère la participation ; le Vault gère ses réserves.
L’entrée fixe maxAmountsIn et la sortie minAmountsOut.
Les listes d’actifs doivent correspondre exactement aux tokens enregistrés et à leur ordre.
userData précise le type d’opération que le pool doit interpréter.
Une sortie en un seul actif peut incorporer un échange économique et ses frais.

Source : [code du dépôt](../../pkg/vault/contracts/PoolBalances.sol).

Suite : [Frais et apports déséquilibrés](07-frais.md).
