## EXAMPLE

Now that we are familiar with the theory, let me present the landscape we can build using tsome tools I described, as well as some tools that already are the part of the industry. 

Let’s imagine a DEX with four token pools. Each pool is a small local DAO. They decide on such questions as liquidity cap, liquidity insurances, pool commissions. The DEX is a DAO itself. It inherites the governing power from pool DAOs. It means that if you contribute liquidity to a pool, you also receive governance power in the DEX DAO, allowing you to vote on fees, smart contract upgrades, grant programs, and other key decisions. This concept — governance power derived from DEX activity - could already be implemented today on Uniswap v4 using hooks.

<img width="1422" height="590" alt="image" src="https://github.com/user-attachments/assets/73770671-116f-4dc7-a3cb-7a51c6e14373" />

Connections 1, 2, 3, and 4 represent the transfer of voting power from the pools to the DEX. It is important to note that these connections are governed by the DEX not by pool DAOs: if the community decides, it can vote to exclude certain pools from the system. For example, if a pool becomes malicious, the DEX community (i.e., the other pools) can vote to remove it.

As a result we have a system where smaller communities have independent power on their local level (pools) + they have power share in greater structure (DEX).

Now let’s introduce a launchpad. Its governance token derives voting power from any tokens launched on it. Tokens C and P were launched there — the launchpad listens to them and receives voting power from them. By holding or swapping the launchpad’s native token, you gain voting power over its future changes.

<img width="1422" height="622" alt="image" src="https://github.com/user-attachments/assets/cb89ae6e-f672-4a89-997b-b60ab071f924" />

Next, we have the Chain DAO - the highest-level governing entity that defines the future of a particular L2 solution. It is this very decentrilized entiity that controls the main vector of the chain.

<img width="1422" height="711" alt="image" src="https://github.com/user-attachments/assets/0a412394-8a9f-4cf6-8dc7-341ee89b1209" />

In our case, such a DAO is designed to import voting power from the most vital projects in its ecosystem. 

At this stage, we assume there are two such projects: DEX and Launchpad. Remember that at their level they inherit power from pools. So as a result, if you actively provide liquidity on chain-vital contracts, you receive the power to vote for the very core changes of the whole network.

An important principle here is that the receiver of the power controls the formulas. The Chain DAO can sever connections with any project at any time. So if we had a third project that seemed to be promising but turned out to be just a scam, then the Chain DAO can simply cut off the voting power inheritance from it. It lets the majority of chain users decide the vector the network is heading in.

Additionally, there is no obstacle to having mutual power inheritance. If a pool wants to inherit voting power from the DEX, it can do so. For example, connection 9 could be established by a pool DAO that decides to eliminate commissions for frequent DEX users. It can serve as a great promotion tool when a smaller community gives out voting power to major structure users.

The risk here is the infinite loop of power inheritance, which is solved by limiting the number of inheritance levels. At the moment, it seems optimal to limit the depth of inheritance to three levels.

Now let’s expand to broader ecosystem add-ons. Imagine there are non-DAO protocols that significantly shape the chain’s DeFi landscape.

<img width="1423" height="705" alt="image" src="https://github.com/user-attachments/assets/1152738c-288c-4189-a364-998e7e226227" />

The Chain DAO can grant voting power to users who actively participate in these DeFi protocols.

As the DAO grows, a new wave of public goods protocols emerges. A Quadratic Crowdfunding Protocol is among the first to support Liquid DAOs: you can vote for projects only if you actively participate in the chain’s DeFi ecosystem. Whether this is a good solution is debatable — but the protocol has the right to define and change its own rules.

<img width="1422" height="814" alt="image" src="https://github.com/user-attachments/assets/3f3112d5-3909-47d2-869f-7b0aa08ca0fc" />

Next comes the Public Goods Engine — a concept for distributing additional donations to public goods projects. But who decides where the money goes? The idea is to let those already engaged in the ecosystem make that decision.

Recognizing this trend, the Chain DAO integrates the Public Goods Engine as a vital ecosystem project. As a result, all public goods participants gain voting power within the Chain DAO.

<img width="1422" height="814" alt="image" src="https://github.com/user-attachments/assets/fadf7333-5d63-495b-9d38-ec2f29c1d625" />

Is this the final level of the system?

Not quite.

Using bridges, a new L2 chain could decide to inherit voting power from the Chain DAO, as well as from a token pool it actively promotes. This becomes a strategy for attracting users: offering small benefits to all active participants, and larger voting power bonuses to carefully selected partners.

<img width="1422" height="814" alt="image" src="https://github.com/user-attachments/assets/563407d5-78cd-44c2-b2d6-61660daef8d1" />

The final question is the cost of gas. Will all these voting power transfers be cheap enough to justify integration?

A few years ago, when minting an NFT could cost $50–60, the answer would likely have been no.

Today, with extremely low L2 fees, the answer is probably yes. Many projects may accept slightly higher gas costs in exchange for on-chain partnerships, meaningful governance systems, and richer ecosystem interactions.
