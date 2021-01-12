# Open Grant Proposal

> This document is referenced in the terms and conditions and therefore needs to contain all the required information. Don't remove any of the mandatory parts presented in bold letters or as headlines! See the [Open Grants Program Process](https://github.com/w3f/Open-Grants-Program/blob/master/README_2.md) on how to submit a proposal.

* **Project Name:** SubDEX
* **Team Name:** subdarkdex
* **Payment Address:** 36RukKN8Qa1QTjsQqCfZ5CzrvAKVg2vro8

## Project Overview :page_facing_up: 

SubDEX is a decentralized cross-chain exchange based on AMM (automated market maker) protocol. 

### Overview

SubDEX team just finished the [first milestone](https://github.com/subdarkdex/Open-Grants-Program/blob/master/applications/subdex.md).
The team is ready to move on to push the project forward. We are going to upgrade the underlying substrate framework to the latest stable version, and add more features to the chain and UI.     
We are also starting to build SubDEX community by posting articles about SubDEX more regularly.

### Project Details 
We expect the teams to already have a solid idea about the project's expected final state.

Therefore, we ask the teams to submit (where relevant):
* Mockups/designs of any UI components
* API specifications of the core functionality
* An overview of the technology stack to be used
* Documentation of core components, protocols, architecture etc. to be deployed
* PoC/MVP or other relevant prior work or research on the topic

### Ecosystem Fit 
Are there any other projects similar to yours? If so, how is your project different?

## Team :busts_in_silhouette:

### Team members
- Arsen Kondratiev
- Belsy Yuen
- Fei Yang
- Herry He
- Stasi Kondaurova

### Contact
* **Contact Name:** Fei Yang
* **Contact Email:** subdex@protonmail.com

### Legal Structure 

Individuals

### Team's experience
TODO update
- Arsen Kondratiev is a software engineer, particularly interested in the blockchain domain. During the last year was mostly focused on substrate runtime development at [Joystream](https://github.com/Joystream/joystream/tree/content_directory_second_try) and Liqum projects. Earlier, worked on infrastructure backends for DAPPs, based on TRON and EOS blockchain platforms.
- Belsy Yuen is a software engineer who focused on working with the substrate framework in the last year. Prior to that, she has worked as a full stack engineer for other blockchain projects on Ethereum, Hyperledger Burrow / Fabric. [LinkedIn profile](https://www.linkedin.com/in/belsy/)
- Fei Yang has been a full stack software engineer for over 10 years and he got involved in blockchain development in May 2017. He worked in centralised exchanges such as [Bitfinex](https://www.bitfinex.com/) and [SDCE](https://sdce.com.au) and believes DEX is the future.
- Herry He is a 6-year e-commerce entrepreneurial veteran as well as an enthusiast of blockchain. After a lecture by Brian from Acala in 2019, where she was shocked by Substrate technology, she decided to devote herself into the tide of Polkadot.
- Stasi Kondaurova is a software engineer, technology-agnostic who prefers working on DApps for developing Blockchains like Tezos or TON. But also has expertise with more sustainable blockchains: Ethereum, Stellar, EOS, UTXO-based blockchains, currently works on [Quipuswap](https://medium.com/madfish-solutions/how-to-use-quipuswap-on-carthagenet-44c7ebfb97b) (DEX on Tezos), has a hobby to draw [mock-ups](https://www.figma.com/proto/bdS7KgUPIoUtWybrYewVHD/Cepheus?node-id=45%3A0&scaling=min-zoom) and write [articles](https://medium.com/madfish-solutions/sol2ligo-in-action-migrating-solidity-smart-contract-to-ligo-sol2ligo-update-3-961ddbd9715c).

### Team Code Repos
* https://github.com/subdardex

### Team LinkedIn Profiles
* https://www.linkedin.com/in/arsen-kondratiev-031801172/
* https://www.linkedin.com/in/belsy/
* https://www.linkedin.com/in/fyang1024/
* TODO  
* https://www.linkedin.com/in/kstasi/

## Development Roadmap :nut_and_bolt: 

This section should break out the development roadmap into a number of milestones. Since the milestones will appear in the grant contract, it helps to describe the functionality we should expect, plus how we can check that such functionality exists in the product. Whenever milestones are delivered, we refer to the contract to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions it should be clear how the project is related to Substrate and/or Polkadot. We recommend that the scope of the work can fit within a 3 month period and that teams structure their roadmap as 1 month = 1 milestone. 

For each milestone:
* Please be sure to include a specification of your software. Treat it as a contract - the level of detail must be enough to later verify that the software meets the specification.
To assist you in defining it, we created a document with examples for some grant categories [here](../src/grant_guidelines_per_category.md).
* Please include total amount of funding requested per milestone.
* Please note that we require documentation (e.g. tutorials, API specifications, architecture details) in each milestone. This ensures that the code can be widely used by the community.
* Please provide a test suite, comprising unit and integration tests, along with a guide on how to run these.
* Please commit to providing a dockerfiles for the delivery of your project. 
* Please indicate the milestone duration, as well as number of Full-Time Employees working on each milestone, and include the number of days along with their cost per day.
* Deliverables 0a-0d are mandatory and should not be removed, unless you explicitly specify a reason within the PR's `Additional Notes` section (e.g. Milestone X is research oriented and as such there is no code to test)

### Overview
* **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
* **Full-time equivalent (FTE):**  Workload of an employed person ([see](https://en.wikipedia.org/wiki/Full-time_equivalent)) (e.g. 2 FTE)
* **Total Costs:** Amount of Payment in BTC or DAI for the whole project. The total amount of funding needs to be below $30k for initial grants and $100k for follow-up grants at the time of submission. (e.g. 0.80 BTC)

### Milestone 2 — Implement Substrate Modules 
* **Estimated Duration:** 1 month
* **FTE:**  1
* **Costs:** 0.75 BTC

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes. Once the node is up, it will be possible to send test transactions that will show how the new functionality works. |
| 0c. | Testing Guide | The code will have unit-test coverage (min. 70%) to ensure functionality and robustness. In the guide we will describe how to run these tests | 
| 0d. | Article/Tutorial | We will write an article or tutorial that explains the work done as part of the grant. 
| 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be coded for the first milestone) |  
| 2. | Substrate module: Y | We will create a Substrate module that will... |  
| 3. | Substrate module: Z | We will create a Substrate module that will... |  
| 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |  
| 5. | Docker | We will provide a dockerfile to demonstrate the full functionality of our chain |

## Future Plans
Please include the team's long-term plans and intentions.

## Additional Information :heavy_plus_sign: 
Any additional information that you think is relevant to this application that hasn't already been included.

Possible additional information to include:
* What work has been done so far?
* Are there are any teams who have already contributed (financially) to the project?
* Have you applied for other grants so far?
