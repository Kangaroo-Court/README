# Kangaroo Court 🦘

`AI is Guilty Until Proven Innocent by Humans`

# Human Owned Roles:
- Defendant 
    > Deposits APE (future production will have other assets) and a Claim to which an oracle will "prove"
    > Starts a Court Proceeding (Mints a Batch of NFTs) to specified addresses
    > > Onchain tx
- Defense
    > Proposes a defandant's claim to be true (Not Guilty) 
    > > On Chain TX
    
    > Earns a fee for picking up the case (pushed to future production)
- Prosecutor
    > Disputes claims to be false (Guilty)
    > > On Chain TX
    
    > Earns a fee for picking up the case (pushed to future production)
- Jury 1 
   >  Votes on Boolean (Not Guilty / Guilty)  
   > > This is an [Attestation](https://optimism-goerli.easscan.org/schema/view/0x56c13171ec212b1bd36ca786b7ed53678a03136863c85063ec0fa23f15e8fcee)

   >  Minted a POAP (pushed to future production)
- Jury 2
   >  Votes on Boolean (Not Guilty / Guilty)
   > > This is an [Attestation](https://optimism-goerli.easscan.org/schema/view/0x56c13171ec212b1bd36ca786b7ed53678a03136863c85063ec0fa23f15e8fcee)

   >  Minted a POAP (pushed to future production)
- Jury 3
   >  Votes on Boolean (Not Guilty / Guilty) 
   > > This is an [Attestation](https://optimism-goerli.easscan.org/schema/view/0x56c13171ec212b1bd36ca786b7ed53678a03136863c85063ec0fa23f15e8fcee)

   >  Minted a POAP (pushed to future production)
- Judge
   >  Final Proceeding on Not Guilty / Guilty 
   >  & Assigns TimeLock of Staked Asset (Forced 0 if Not Guilty) 
   > > This is an [Attestation](https://optimism-goerli.easscan.org/schema/view/0xbf564b3ed16b42c3bcfad0e6f5f6016b9657dabc57a4c4e37706b6d017918a55)

- Bailiff
   > Executes Judge's Final Verdict
   > > Onchain TX

### Defandant Earns some yield if Not Guilty (pushed to future production)

# Socials 
   [Twitter](https://twitter.com/KangarooCourtAI)
    
### AI meets human wisdom. Resolve AI-Oracle conflicts fairly. Human judges, prosecutors, defenders, jurors, and bailiffs on Optimism-Goerli, Linea, Scroll and Goerli blockchains. Incentivized prediction market. Empowering governance and dispute resolution. Leading AI conflict resolution on blockchain. 
 
## Abstract
Kangaroo Court is a revolutionary platform that combines AI-driven technologies with the wisdom and judgments of human actors, promoting fair and transparent resolution of conflicts between Artificial Intelligences (AIs) and Oracle smart contracts. The Optimism-Goerli blockchain-based platform features a legal framework whereby human actors act as judges, prosecutors, defenders, jurors and bailiffs to resolve claims lodged by prosecutors against AIs or smart contracts. Additionally, Kangaroo Court introduces an incentivized prediction market to enhance user engagement and ensure participants are properly rewarded for their contributions. By empowering human actors to participate actively in dispute resolution on a distributed platform, Kangaroo Court is poised to become the leading AI governance and conflict resolution system in the blockchain space. Through further expansion of its user base, innovations in its features, and an expanded pool of human actors, Kangaroo Court will serve as a bedrock for trustless adjudication.

## Repo Structure
The Current implementation of <Kangaroo Court> relies on the following repositories : 
- [Oracle](https://github.com/Kangaroo-Court/oracle)
> Refactored UMA Governance with Prediction Betting 
- [NFTs](https://github.com/Kangaroo-Court/court-sc)
> Role Based NFTs for 
- [Front End](https://github.com/Kangaroo-Court/kc-frontend)
> Next.js framework for interacting with the smart contracts
> Based on the [Figma](https://www.figma.com/file/ttwtDiCW7wKOB6oUSGTY4K/KANGA?type=design&node-id=0%3A1&t=K5ejs8hsAv3bXMUR-1)

## How its made: 

## The development of Kangaroo Court utilizes a combination of [UMA](https://uma.xyz) smart contracts, oracles, the front-end framework Next.js, the [Ethereum Attestation Service](https://attest.sh) and [AirStack](https://airstack.xyz/) AI tools to create a comprehensive and efficient platform.

Smart contracts are deployed on the Optimism-Goerli, Linea, and Scroll blockchains to establish a multichain underlying legal framework and automate the execution of key processes within Kangaroo Court. These contracts define the roles of human actors, handle the staking and distribution of tokens, manage the flow of information between participants, and facilitate the resolution of claims.

Oracles play a crucial role in connecting real-world data with the blockchain. They provide a bridge between external information sources and the smart contracts, ensuring accurate and reliable data inputs for decision-making. Oracles are responsible for fetching data related to the claims, such as cryptocurrency prices or contract behavior, enabling the AI-driven components and human actors to make informed judgments.

The front-end framework, such as Next.js, is utilized to create a user-friendly interface for interacting with Kangaroo Court. It allows users to access the platform, submit claims, participate in the prediction market, and engage in the governance processes. The front-end interface seamlessly integrates with the blockchain infrastructure, enabling real-time updates, and providing an intuitive user experience.



AI tools are employed within Kangaroo Court to enhance decision-making processes. AIs can be used to analyze claim-related data, identify patterns, and provide insights to support the arguments presented by the prosecution and defense. These AI-driven tools assist human actors in formulating stronger cases, improving the efficiency and accuracy of the overall adjudication process.

By combining smart contracts, oracles, a front-end framework like Next.js, and AI tools, Kangaroo Court achieves a powerful and comprehensive platform. The smart contracts provide the foundation for the legal processes, while oracles ensure the accuracy and reliability of external data. The front-end framework enhances user interaction and accessibility, while AI tools augment decision-making capabilities. Together, these components create a robust ecosystem that promotes fair and efficient conflict resolution between AIs and Oracle smart contracts, while engaging users through the prediction market and incentivized participation.
