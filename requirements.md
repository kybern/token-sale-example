# Requirements for the token sale

[List of requirements](https://www.ietf.org/rfc/rfc2119.txt)
## Requirements

### MUST:   

- Have a dynamic supply, meaning that each incoming ETH must result in the minting of new tokens. 
- Have a maximum supply of **100M tokens (not sub-units!)**.
- Have a total of **2 temporal phases**: *{ pre-sale, ico}*.
- Have a defined range of dates for those phases (take some future arbitrary dates)
- Have a whitelist for investment on *pre-sale*.
- Have a total of **5 price steps**.
- Have a hard-cap of $10M.
- Have the following **bonus structure**, equally distributed:

    | Step | Bonus |
    | ------ | ------ |
    | 1 | 20% |
    | 2 | 15% |
    | 3 | 10% |
    | 4 |  5%  |
    | 5 |  0% |

- Have the possibility to set the price after the deployment.
- Have a list of allocation accounts (dynamic).
- Have a bunch of succesful mocha-tests validating the all the given requirements.


### MUST NOT   

- Allow anybody to invest before a sale phase.
- Allow non *white-listed* accounts to invest in pre-sale phase.
- Exceed the hard-cap.



### SHOULD   

 - Be commented.
 - Be splited in different contracts, and make use of standarized [Zeppelin Smart Contracts](https://github.com/OpenZeppelin/zeppelin-solidity)
 - Follow ethereum [coding standards](https://github.com/ethereum/cpp-ethereum/blob/develop/CodingStandards.txt)
 - Use [libraries](https://ethereum.stackexchange.com/questions/21395/understanding-solidity-libraries) when possible instead of inheritance. 

## Helpful links

- [Smart Contract best practices](https://github.com/ConsenSys/smart-contract-best-practices)
- [ICO best practices](https://github.com/Scanate/Tokensale)

