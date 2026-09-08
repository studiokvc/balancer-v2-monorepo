# 2. Vault et comptabilité par pool

Un même token peut servir plusieurs pools sans que leurs soldes soient confondus.
Le Vault identifie le pool par un poolId et maintient ses balances enregistrées.
registerTokens associe aussi un Asset Manager éventuel à chaque token.
Les spécialisations GENERAL, MINIMAL_SWAP_INFO et TWO_TOKEN réduisent les données nécessaires au swap.
Le solde ERC-20 global du Vault ne suffit donc pas à connaître les réserves d’un pool.
Lire les balances du pool, dans leur ordre enregistré, est indispensable.

Source : [code du dépôt](../../pkg/vault/contracts/PoolTokens.sol).

Suite : [Invariant pondéré](03-invariant.md).
