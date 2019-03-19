# [hack4climate](hack4climate.com) pecha kucha 
On 15 Mar 2019, Yale-NUS College hosted a hack4climate.live [pecha kucha](https://en.wikipedia.org/wiki/PechaKucha) night focusing on social impact projects in the blockchain space. This is a rapid-fire style of knowledge sharing, where each presenter has 15 slides and goes through them at the rate of 20 seconds per slide. It made for a streamlined presentation of each project's 'headlines'; but to really digest what we learned, we decided to spend some time on deeper research. 

These projects were diverse in both approach and domain; in this case, what they had in common was the use of a blockchain in some way to promote coordination towards social goods, including climate action, renewable energy, and community action and corporate social responsibility. 

From these presentations, a few common strategies which characterised "blockchain for social impact" emerged:
- **disintermediation**: automated settlement and disbursement of payments, allowing for 
- **granular transactions** which lower barriers to entry for smaller players; 
- **transparency**: publicly verifiable recording of information from third parties; and
- **cryptoeconomics**: tokenisation and mechanism design to incentivise cooperative behaviour.

Many of these projects also depended on [reliable and accurate oracles](https://medium.com/@jesus_notchrist/blockchain-oracles-af3b216bed6b) to verify claims being made about quantitative real-world data (e.g. IoT sensors). Thus, they cannot be said to be trustless: though there is no way for the oracle to alter former claims, it is also impossible for a remote third party, without firsthand access to the sensor, to verify or dispute their claims.

As with any technology, efficacy is highly contextual and determined by use case. I personally find this diagram (from [this paper](https://eprint.iacr.org/2017/375.pdf)) useful for filtering out the hype:

![](https://i.imgur.com/67fKAtC.png)

I leave it to the reader to build on and/or challenge each use case presented here, and in general. 



## [Commit-Me](commit-me.com): pledges for climate action
commit-me.com allows institutions and sub-state actors to publicly make a commitment to climate action, and receive crowdfunding for that commitment through a smart contract. It aims to hold institutions publicly accountable to their promises. 

![](https://i.imgur.com/7wPqKH4.png)

Currently, they have piloted at Oxford University and are planning to build out the platform at production, onboarding more institutional partners and alpha users. They are also exploring the mechanism design space (see https://github.com/YaleOpenLab/hack4climate for some prompts that were explored during the hack4climate.live hackathon).

## [RadicalxChange Singapore](radxchangesg.github.io)
![](https://i.imgur.com/gz1B1jP.jpg)
Swarnima from RadicalxChange Singapore gave an overview of some ideas and projects surrounding the RadicalxChange movement, including:
- Harberger taxes for property markets
- quadratic voting
- immigration sponsorship markets
- antitrust
- data as labour

She also extended an open invitation to our [upcoming meetup](https://www.meetup.com/RadicalxChange-Singapore/events/259425910/) on 18 Apr 2019. 

## [Electrify](https://electrify.asia/): p2p energy trading
Electrify provides a payment settlement layer for p2p energy trading on a city-wide grid. Allowing distributed energy resource (DER) owners (e.g. households who install solar PVs on their rooftops) to directly sell to consumers opens up a free market, where competition can drive prices below the regulated tariff at certain times of day. 

![](https://i.imgur.com/YCAIO3J.png)

They concluded their [Singapore platform alpha](https://electrify.asia/2019/03/15/get-to-know-synergy-alpha/) in Feb 2019. Their upcoming beta aims to onboard 50 participants (mix of consumers and prosumers).

## Blockchains 4 Liquid Markets for Forest Carbon 
(Detlef Sprinz, Potsdam Institute for Climate Impact Research)

This project proposes using smart contracts to grow the forest carbon offset liquidity pool,  opening it up to smaller buyers. Smart contracts are used to link "demand-side" carbon offsets, in a transparent, manner, to specific pieces of land and real-world information like:
- external verification status;
- time stamp of measurements (e.g. forest-cover, carbon contents);
- avoidance of monocultures;

This solution is reliant to a certain extent on accurate and trusted oracles, although it also places their claims under public scrutiny. 

## [Blockchain for Climate Action Tracking](https://medium.com/on-blockchain-and-climate-accounting/the-blockchain-and-climate-intersection-a-primer-3a75f0150b5a) (Yale Open Lab, Tsai CITY) 
B-CAT proposes integrating a protocol layer to existing systems for decentralised record-keeping and automated contracts.

![](https://i.imgur.com/J7uKMOV.png)

They reason about these ledgers in terms of physical, aggregate layer ("planetary ledger"), and the more human, granular layer ("world ledger"). Their tech stack includes: 
- Secure internet-connected sensors (i.e Internet-of-Things technology or IoT for short).
- Oracles equipped with machine learning to verify data prior to its link with the blockchain.
- Open source code, data and architecture — in user-friendly accessible wiki platforms for easy audit-abilty by the global community.
- Intuitive end-user interfaces and data visualization of the ledger’s state at any point in time.

 
## [HourVillage](https://hourvillage.com/): a social marketplace for skills and services

![](https://i.imgur.com/lKgiOMu.png)


Hourvillage is a marketplace for skills and services, using time as a unit of account, not money. For instance, one hour of skateboarding lessons could be exchanged for, say, one hour of front-end development, if both parties agree to it. This assumes that all skills are equally valuable per unit time -- or, put another way, it challenges users to take into account the value of social interaction and giving. 

Their B2B platform, Timefly, connects employees to charitable organisations for Corporate Social Responsibility (CSR) programmes. 

Their launch is planned for summer 2019. 

(Ying Tong)
