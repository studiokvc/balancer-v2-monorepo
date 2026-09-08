# 3. Invariant pondéré

WeightedMath calcule un invariant de la forme produit des balances élevées à leurs poids.
Les poids sont normalisés ; une pondération plus forte modifie la sensibilité du prix.
La formule de sortie utilise le rapport des poids des deux tokens échangés.
Les calculs en virgule fixe imposent des arrondis conservateurs.
Les limites _MAX_IN_RATIO et _MAX_OUT_RATIO valent 30 % dans cette bibliothèque.
Ce sont des limites par opération, pas une garantie contre une variation de marché.

Source : [code du dépôt](../../pkg/pool-weighted/contracts/WeightedMath.sol).

Suite : [Échange et protection du montant](04-swap.md).
