# 7. Frais et apports déséquilibrés

Un apport proportionnel conserve les proportions économiques du pool.
Un apport déséquilibré équivaut en partie à des swaps.
WeightedMath sépare donc une portion taxable d’une portion non taxable.
Les frais réduisent les montants utilisés pour calculer les BPT attribués.
Les retraits non proportionnels utilisent une logique analogue.
Comparer seulement les tokens déposés masque l’effet des poids, des frais et des arrondis.

Source : [code du dépôt](../../pkg/pool-weighted/contracts/WeightedMath.sol).

Suite : [Solde interne et autorisations](08-solde-interne.md).
