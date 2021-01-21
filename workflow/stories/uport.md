## Utility Case Study

| Story Name | Case Study Type |
| --- | --- |
| uPort/Ethereum | Actual|

### Background Context
Unlike most active utility projects, the team at uPort believes in permissionless ledgers. The thinking is that since Issuers of credentials need to follow laws from the areas they operate in anyways, the DIDs created on the public chain shouldn’t add double governance. The DIDs created may not be accepted by law, however the belief is LAW OVER CODE. The ecosystem solution would define their own governance - it doesn’t need to sit within the stack.

### Stakeholders / Persona
* Mathieu Glaude, CEO at Northern Block
* Rouven Heck, Digital ID Lead at ConsenSys

### User Stories
The companies and institutions mentioned above have identified permissionless blockchains as an alternative to the SaturnV utility model

## Utility Foundry Workflow

![swimlanes](https://github.com/trustoverip/utility-foundry-wg/blob/master/workflow/img/workflow-swimlanes.png)

### 1. Learn
* The Identity team at ConsenSys identified Ethereum as an immutable ledger to store information in relation to decentralized identifiers
* Ethereum’s ethos of providing full sovereignty and control to app builders led the thinking around leaving users to define the governance model - it was decided that the governance doesn’t need to be at the utility layer, as legal/compliance/business requirements could be managed traditionally just like it is today.
* It was determined that users should also be able to choose ledgers, avoiding ledger-lock.


### 2. Convene

* ConsenSys invested in digital identity, through a project called uPort.
* The uPort team are members and Co-founders of the Decentralized Identity Foundation/
* No need for stewards as the network is already up and running.
* Even if the technology was to disappear, anyone can still keep the state root, put it up on a new server, and move to another solution. It’s not a risk to maintain immutability.
* They felt that the permission;less method was stronger - inside a concostrium, if incentives run out for the participants, there is no reason to keep operating it.


### 3. Define
NA

### 4. Create

* No need for any legal entity to manage governance of underlying utility.
* Anyone can write to the Ethereum blockchain as long as they pay the required gas fees acceptable by miners on the network.

uPort has contributed the following open source libraries:

* https://github.com/decentralized-identity/did-jwt
* https://github.com/decentralized-identity/did-jwt-vc
* https://github.com/decentralized-identity/did-resolver
* https://github.com/decentralized-identity/ethr-did-resolver
* https://github.com/decentralized-identity/web-did-resolver

### 5. Implement
* Recent implementations have seen projects move more off-chain and limit the amount of information stored on-chain.
* There are 5-10 DID methods that use Ethereum.

### 6. Maintain
NA

### 7. Additional Considerations

As of October 2020,
* uPort still operates within ConsenSys
* The team has created a DID Agent framework, which has similarities to the Aries agent. It is compatible with Aries and they offer a mobile SDK for this.
* There are two existing DID methods, and they’re about to implement the equivalent of Sidetree for Ethereum.
* The team is looking into scalable methods for revocations.




