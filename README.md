
Gridmaster development tree

Gridmaster is a PoS-based cryptocurrency.

Gridmaster is dependent upon libsecp256k1.

The recommended build is included in the src directory. This is not the latest but is the one that has more success building the client.

Dynamic rewards
Block Spacing: 60 Seconds
Stake Minimum Age: 4 Hours

Port: 51180
RPC Port: 51181

Gridmaster includes an Address Index feature, based on the address index API (searchrawtransactions RPC command) implemented in Bitcoin Core but modified implementation to work with the Gridmaster codebase (PoS coins maintain a txindex by default for instance).

Initialize the Address Index By Running with -reindexaddr Command Line Argument.  It may take 10-15 minutes to build the initial index.


