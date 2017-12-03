# Toy project

## Intro

We will try to implement a simple blockchain in golang. An idea is to eventually also try various (asynchronous) [Byzantine fault
tolerance](https://en.wikipedia.org/wiki/Byzantine_fault_tolerance) algorithms. Possibly also compare them with strong leader (non-Byzanitne) consensus protocols
like [Raft](https://en.wikipedia.org/wiki/Raft_(computer_science)) or [Paxos](https://en.wikipedia.org/wiki/Paxos_(computer_science)).
Also [Proof-Of-Stake](https://en.bitcoin.it/wiki/Proof_of_Stake) is promising, but you need to take care of the nothing at stake problem. Cryptographic sortition using
VRF (Verifiabla Random Functions) like in Algorand is also interesting.

## Resources
* https://jeiwan.cc/posts/building-blockchain-in-go-part-1/
* [Bitcoin full node implementation in Go](https://github.com/btcsuite/btcd)
* [Hashgraph consensus algorithm](http://www.swirlds.com/downloads/SWIRLDS-TR-2016-02.pdf)
* [Raft paper](https://raft.github.io/raft.pdf)
* [Raft animation](http://thesecretlivesofdata.com/raft/)
* [Paxos made simple paper](http://lamport.azurewebsites.net/pubs/paxos-simple.pdf)
* [Verifiable Random Functions](https://www.cs.bu.edu/~goldbe/projects/vrf)
* [Algorand paper](https://people.csail.mit.edu/nickolai/papers/gilad-algorand.pdf)
