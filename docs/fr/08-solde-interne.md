# 8. Solde interne et autorisations

manageUserBalance permet de déposer, retirer et transférer des balances internes.
Ces balances sont comptabilisées par utilisateur et par token dans le Vault.
Elles peuvent financer un swap ou recevoir son résultat.
Un transfert interne évite certains transferts ERC-20 répétés.
Un relayer doit être admis par le système et approuvé par l’utilisateur concerné.
Une allowance ERC-20 et une autorisation de relayer ne sont pas la même permission.

Source : [code du dépôt](../../pkg/vault/contracts/UserBalance.sol).

Suite : [Flash loan du Vault](09-flash-loan.md).
