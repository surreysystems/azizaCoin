# azizaCoin
##Aziza Coin Ethereum Smart Contract

The contract has 4 states: CLOSED ,PRIVATE, RESTRICTED, PUBLIC
- CLOSED: No one can buy or sell - transfers are allowed
- PRIVATE: Contract can sell to registered accounts. Other accounts can only sell to registered accounts
- RESTRICTED: Contract can sell to registered accounts. Other accounts can  sell to both  registered and non registered accounts
- PUBLIC: Contact can sell to any account. Any account can sell to any other account. No registration needed
Transfers are not restricted by contract state allowing for tokens to be moved between accounts for no consideration at any time including during the CLOSED state.
The contract state can only progress in  one direction: CLOSED > PRIVATE > RESTRICTED > PUBLIC


