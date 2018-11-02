Scene: Solidity and most other smart contract languages are deterministic. Sometimes they need data that is outside of the blockchain.

One of the ways Ethereum has dealt with this issue is by offering oracle services. 

A popular one is Oraclize another is TinyOracle. Both will work well for this task.



You will need to use one of the oracle services to connect to the following JSON file.

[https://variusworldtech.github.io/Technical-Test/casino.json]

You will need to retrieve the list of casino games from the API using oraclise.

The smart contract should store this list of games.
Only the owner of the contract can call this function.

