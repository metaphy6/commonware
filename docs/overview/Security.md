1. Proof of Physical Work & Auditing 
Before a provider is rewarded, they must prove their hardware is performing the specific task requested. 

    Hardware Attestation: Nodes must submit cryptographic proofs that they are running specific, authorized hardware. This prevents users from "faking" work or running unauthorized code on virtualized systems that are easier to hide.
    Probabilistic Verification: Networks like Akash or Render can use random sampling to check on active jobs. If a node is caught running unauthorized processes, its stake (tokens they put up as collateral) can be "slashed," meaning they lose money. 

2. Trusted Execution Environments (TEEs)
To protect both the provider and the user, many compute networks use TEEs (like Intel SGX). 

    A TEE is a "secure enclave" inside a processor that encrypts data while it's being processed.
    Technically, this means the person owning the server cannot see what is being computed, and the user cannot easily use the server to access the host's private network for illicit hacking. 

3. Economic Collateral (Staking)
DePIN relies on the idea that it should be more expensive to break the rules than to follow them.

    Staking: To join a network, providers often have to "lock up" a certain amount of the network's tokens.
    Slashing: If the network's automated auditing tools or community governance find that a node is facilitating illegal activity (like hosting a botnet), the smart contract can automatically seize their locked tokens. 

4. Community Governance and Whitelisting
Since there is no central authority, the community often votes on "Allowed Lists" of software or providers.

    DAO Voting: Token holders can vote to ban specific wallet addresses or node operators if they are linked to illegal activities.
    Whitelisting: Many projects start with a "whitelisted" set of trusted providers who have passed basic identity or security checks before the network goes fully open to the public. 

5. Instance-Level Moderation
In some decentralized compute models, moderation happens at the provider level rather than the network level.