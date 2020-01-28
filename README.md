Truffle version:
Truffle v5.1.10 (core: 5.1.10)
Solidity v0.5.16 (solc-js)
Node v10.17.0
Web3.js v1.2.1

ERC-721 Token Name: Crypto Star 08
ERC-721 Token Symbol: CS08

"Token Address" on the Rinkeby Network:
0xef98F86c51c34D7e3550EA366BF8674b327fb2cA

Additional Comment:
When running in truffle develop, everything goes well.
However if it's been deployed to the Rinkeby network, When clicking on the "Look Up a Star" button, an error prompts that
"Uncaught (in promise) Error: overflow (operation="setValue", fault="overflow", details="Number can only safely store up to 53 bits")"
I don't know why it this occurs. Later I found that it maybe a common open issue:
https://github.com/ethereum/web3.js/issues/2817