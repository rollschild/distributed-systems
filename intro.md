# Intro

## Networked Systems and Distributed Systems

### Decentralized Systems vs. Distributed Systems

- A decentralized system is a networked computer system in which pro-
  cesses and resources are necessarily spread across multiple computers.
- A distributed system is a networked computer system in which pro-
  cesses and resources are sufficiently spread across multiple computers

- **Content Delivery Networks** (**CDN**)
- **Centralized solutions** are _NOT_ always bad
- A logically centralized solution can be implemented in a highly scalable distributed manner
  - **DNS**

### Studying Distributed Systems

- **Distributed systems are all about processes**

## Design Goals

- Resource Sharing
  - **transparency**

### Transparency

- Access Transparency
- Location Transparency
  - **URI**
- Migration Transparency
- Replication Transparency
- Concurrency Transparency
  - locking
  - transactions
- Failure Transparency
- Discussions against Distribution Transparency
  - use more message-style communication
  - more explicitly post requests to and get results from remote machines (like Web)
  - **copy-before-use**

### Openness

- Define interfaces using **Interface Definition Language (IDL)**
- **Interoperability**
- **Portability**

> What wee need is a separation between policy and mechanism

### Dependability

- partial failures
- **Fault**
  - **transient**
  - **intermittent**
  - **permanent**

### Security

#### Cryptography

- **multi-party computation**

### Scalability

- Queue theory

#### Scalability Dimensions

- size scalability
- geographical scalability
- administrative scalability

### Classification of distributed systems

- Multi-processor machines - sharing unified memory
- Multi-computer system
- Message-passing models
- Distributed-memory systems
- Distributed shared-memory multicomputers (DSM systems)
- **Cluster computing** vs. **Grid computing**
- Distributed Transaction Processing
  - **Remote Procedure Calls (RPC)**
  - **Transactional RPC**
  - **Transaction-processing monitor (TP Monitor)**
    - uses the **distributed commit** protocol to coordinate the commitment of subtransactions
-
