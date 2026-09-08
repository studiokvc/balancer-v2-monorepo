# 9. Flash loan du Vault

flashLoan transfère temporairement les tokens puis appelle receiveFlashLoan.
Les adresses de tokens doivent être uniques et triées.
Après le callback, le Vault compare les soldes aux soldes initiaux.
Il exige le remboursement du principal et des frais calculés.
Le callback et le remboursement appartiennent à la même transaction.
Un contrôle échoué annule l’ensemble ; aucun crédit durable n’est ouvert.

Source : [code du dépôt](../../pkg/vault/contracts/FlashLoans.sol).

Suite : [Périmètre et limites](10-limites.md).
