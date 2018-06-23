Fling is a tool from OpenRelay that can send tokens to lots of accounts in a
single transaction. It supports ERC20 tokens and ETH using a smart contract.

The number of addresses you can fling to depends on the number amount of gas
required to transfer that token, and the current block gas limit. We've tested
it with over 30 addresses, but in theory it should be able to go much higher.
