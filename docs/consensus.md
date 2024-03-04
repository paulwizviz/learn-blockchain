# Consensus

In this section, we examine consensus algorithms: concepts, design and implementations.

## Design Considerations

The goal of consensus is to reach agreement. see [Consensus and & Organising Coffee](https://www.youtube.com/watch?v=jn3DBzr--Ok)

The key considerations when designing consensus algorithm are summed in two thought experiments:

* [Distributed Systems 2.1: The two generals problem](https://www.youtube.com/watch?v=MDuWnzVnfpI)
* [Distributed Systems 2.2: The Byzantine generals problem](https://www.youtube.com/watch?v=LoGx_ldRBU0)

The two generals experiment illustrates the problem of reliable communications between two distributed entities.

The three generals experiment illustrates the problem when there are more than two entities co-ordinating actions with each other where some entities could go rouge -- i.e. deliberately deceive others. 

## Implementations

According to Dr. Leemon Baird, there are five types of algorithms:

* [#1: Proof-of-work](https://www.youtube.com/watch?v=A467am0fw34)
* [#2: Leader-based, e.g. Paxsos](https://www.youtube.com/watch?v=hVYRkcTY840)
* [#3: Economy-based](https://www.youtube.com/watch?v=EVVso37nie8)
* [#4: Voting-based](https://www.youtube.com/watch?v=HgaG6Vtv1zc)
* [#5: Virtual-voting, e.g. Hashgraph](https://www.youtube.com/watch?v=rleAZVVA3kM)


### Directed Acyclic Graph
 
* [Direct Acyclic Graph (DAG) Based Consensus Protocols: An Introduction | a16z crypto research talks](https://www.youtube.com/watch?v=v7h2rXNtrV0)

### Paxos Agreement

Paxos is a leader-based algorithm.

* [Paxos Agreement - Computerphile](https://www.youtube.com/watch?v=s8JqcZtvnsM)
* [Paxos vs Raft: Have we reached consensus on distributed consensus? — Heidi Howard ](https://www.youtube.com/watch?v=JQss0uQUc6o)

### Proof-of-Authority

* [What is Proof of Authority & How it Actually Works (Animated)](https://www.youtube.com/watch?v=uLPjWeAZ47g)

### Proof of Elapsed Time (PoET)

Each node in the network randomly generate time duration from a trusted hardware chip and each waits until the generated time elapsed. The first node to have its time elapsed has the right to mine a block. 

### Proof of History

* [What is Proof of History & How it Actually Works (Animated)](https://www.youtube.com/watch?v=A5G_FJpzKtk)

### Proof of Reserved

* [What is Proof of Reserves in Crypto & How it Actually Works (Animated)](https://www.youtube.com/watch?v=qzWT0JAyBIc)

### Proof of Stake

* [What is Proof of Stake & How it works (Animated)](https://www.youtube.com/watch?v=HjovHCq4wK4)
* [What is Delegated Proof of Stake & How it Actually Works (Animated)](https://www.youtube.com/watch?v=nd40wO2FgFk)

### Proof-of-Work

* [What is Proof of Work (Animated)](https://www.youtube.com/watch?v=ZTkuleUJV0M)
