# MLChain (Draft)

A project to provide blockchain based computational infrastructure to facilitate machine learning computation demands.

## why another chain

The peer to peer network of a blockchain computes hashes all the time to make sure achieving the consensus of the whole state of the network. It's an innovative way to maintain a decentralized state but there is a possiblity for the computational power to serve some purposes other than just hashing. The target of this project is to make a blockchain to provide computational power to machine learning computation demands over blockchain technology and provide enough and direct incentives for computational power providers(the miners) and computational power consumers. This blockchain will focus on machine learning computational problems and will be optimized towards that direction rather than becoming a turing complete platform.

## what is in this chain

* There will be jobs, which are machine learning computations, looking for a set of most optimal weights
* Mixed consensus machanism: PoW and PoA(Proof of Answer, thanks to 朱立)
* Training data stored outside blockchain and only the hash will be stored on chain with jobs and answers
* Answers togather with miner's address stored outside blockchain and only the hash will be store on chain
* Miner's program will include PoW part to extend the chain by verify and include all normal tx and answers for the jobs
* Miner's program will also include PoA part which will search a set of more optimal weights
* PoA is a process of co-operate and compete to get a specific chain of answers for a job
* Tokens will be generated during PoW and rewarded to miners
* Tokens will be required to submit a job
* Tokens from a job willl be rewarded to miners who participate in the chain of answers

## what is this PoA

For a specific 
