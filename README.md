# smart-contracts
Repo with all our smart contracts
Here we will be focusing on some general aspects of our first smart contract code.

1. **SafeMath Library**: Provides arithmetic functions that prevent integer overflows and underflows. Examples:
   - `add`: Returns the sum of two numbers.
   - `sub`: Returns the difference of two numbers.
   - `mul`: Returns the product of two numbers.
   - `div`: Returns the division of two numbers.

2. **IERC20 Interface**: Defines the standard functions for an ERC-20 token contract, like getting the total supply, transferring tokens, and approving spending by others.

3. **Ownable Contract**: Manages ownership of the contract, allowing only the owner to perform specific functions, like transferring ownership.

4. **IFactory Interface**: Used for creating and fetching pairs of tokens in a decentralized exchange.

5. **IRouter Interface**: Deals with adding/removing liquidity and performing swaps between different tokens on a decentralized exchange.

6. **ETFrocks Contract**: Defines the main token, including its supply, symbol, balances, and various settings. Contains functions for transferring tokens, updating fees, and managing limits.

7. **swapAndLiquify Function**: Part of a mechanism to provide liquidity to the decentralized exchange. Swaps tokens for ETH, then adds liquidity to the pair, supporting the price stability of the token.

This is a high-level overview of some core components in your code, related to a typical DeFi token with liquidity and trading functionalities. If you need details on specific functions or aspects, please let us know!
