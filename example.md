## EXAMPLE

Here you can find the very-very detailed step-by-step example how such a system can look like in some abstract EVM network ecosystem. Do not consider it as a plan or architecture proposal, consider it as a dreamful example with some references to liquid_dao_whiteppaper. 

### Liquidity-based DAOs for DEX. 

Now that we are familiar with the theory, let me present the landscape we can build using tsome tools I described, as well as some tools that already are the part of the industry. 

The network core DeFi protocol is always DEX. Let’s imagine a DEX with four token pools. Each pool is a small local DAO. It works the next way: once the proposal is made, the liquidity provided in the pool accounted as voitng power. Liquidty providers decide on such questions as liquidity cap, liquidity insurances, pool commissions. You can think of such a system without any liquidity DAO mechanics. (explore Uniswap v4 hooks to play with such add-ons).

Also the DEX is a DAO itself. And here liquidity DAO core mechanic plays a role. DEX DAO inherites the governing power from all four pool DAOs. It means that if you contribute liquidity to a pool, you also receive governance power in the DEX DAO, allowing you to vote on fees, smart contract upgrades, grant programs, and other key decisions. 

----
<img width="1413" height="583" alt="image" src="https://github.com/user-attachments/assets/dd543a86-8d83-4c0f-ab40-7f07432e3150" />

----

**Connections 1, 2, 3, and 4** represent the transfer of voting power from the pool DAOs to the DEX DAO. It is important to note that these connections are governed by the DEX and not by pool DAOs: 
1. formulas of the enheritance can be changed by DEX DAO. For example, DEX DAO can vote to add some modifier on power enheritance from specific pool. It makes sence to support pools with low liquidity in such way. 
2. the наличие of enheritance is also up to DEX DAO. For example, the malisous pools can be excluded from being influencial on DEX DAO (if the quourm is reached on it, of course).

It is vital that the inheritance descion making was up to power reciever, and never vice versa. 

### The Launchpad DAO.

We have made a small ecosystem for swapping tokens. Now let's move to launching them. Launchpad can have its own DAO as well as DEX have. The Launchpad DAO voters will decide on protocol upgrades, comissions, etc.

The luanchpad governance power is split across those who support liquidity in pairs with tokens launched via this launchpad. No doubts such a system can help launched token to be much more connected to the launchpad community. 

----

<img width="1413" height="615" alt="image" src="https://github.com/user-attachments/assets/ca12e875-5c2d-4f41-827c-aaf9e762b5bd" />

----

Tokens C and P were launched via our launchpad, so **connections 5 and 6** represents the voting power enheritance from the particluar pools. 

As we see, not only it make the communities much more tighted but for side investor the slight difference appears while choosing a pool to provide liquidity for. The difference is small but on some level it starts the competition between pool DAOs with whom they partner, with whom they have such connections, and it all works FOR DAOs in global. DAO adopbtion becomes not a side quest but a cometition advantage.

### The Network DAO.

Next, we have the Chain DAO - the highest-level governing entity that defines the future of a particular netowrk solution. It is this very decentrilized entiity that controls the main vector of the chain. Quite a common DAO for ethereum L2, does not it?

In our case, such a DAO is designed to import voting power from the most vital projects in its ecosystem. That's how it easiliy hand power out to defintely most active network communities. 

----

<img width="1413" height="704" alt="image" src="https://github.com/user-attachments/assets/7962ca95-c6ce-4ca4-abcb-c868d3aaaf17" />

----

**Connections 7 and 8** are all about it. At this stage, we assume there are two core projects: DEX and Launchpad. Remember that at their level they inherit power from pools. So as a result, if you actively provide liquidity on chain-vital contracts, you receive the power to vote for the very core changes of the whole network.

### Mutual enheritance.


Now when we already have three levels of governance, let's move on to a bit more complex plays. 

It's worth saying there is no obstacle to having mutual power inheritance. If a pool wants to inherit voting power from the DEX, it can do so. For example, **connection 9** could be established by a pool DAO that decides to eliminate commissions for frequent DEX users. It can serve as a great promotion tool when a smaller community gives out voting power to major structure users.

The risk here is the infinite loop of power inheritance, which is solved by limiting the number of inheritance levels. At the moment, it seems optimal to limit the depth of inheritance to three levels.

### Inherite power from non-DAO protocols. 

Also it is worth mentioning that DAOs are fine to look for other sources of voting power. So let’s take a view to broader chain ecosystem. Imagine there are non-DAO protocols that significantly shape the chain’s DeFi landscape: staking and borrowing protocols. 

----

<img width="1413" height="697" alt="image" src="https://github.com/user-attachments/assets/ae6fa430-fd96-430c-94c1-93ccac1479d8" />

----

The Chain DAO can grant voting power to users who actively participate in these DeFi protocols - now **connection 11** exist. The only step to it is to integrate in this protocols some mechanisms similar to Uniswap v4 hooks, but remember that they can be oversimplified if they need to serve needs only of liquid DAO mechanisms. 

Also you might notice **connection 10**. Here I want to illustrate that there is no strict hierarchy system in liquid DAOs, so as well as chain can enherit voting power from its DeFi protocols, other DAOs can do it as well, even smallest one - like Pool DAO in this example. 

### The public goods DAO.

Let's make our ecosystem even broader. As the chain grows, a new wave of public goods protocols emerges. Not all of them neccessarly are the part of DAO landscape from the very beginning. A Quadratic Crowdfunding Protocol is the first and by now is the only one to support Liquid DAO mechanism. 

----

<img width="1413" height="806" alt="image" src="https://github.com/user-attachments/assets/2003ae4c-db50-4692-b1c5-b80097955381" />

----

**Connection 12** stops you from participating in funding public goods unless you actively participate in the chain’s DeFi ecosystem. Whether this is a good solution is debatable - but the protocol has the right to define and change its own rules.

Next comes the Public Goods Engine — a concept for distributing additional donations to public goods projects. But who decides where the money goes? The idea is to let those already engaged in the ecosystem make that decision.

Recognizing this trend, the Chain DAO integrates the Public Goods Engine as a vital ecosystem project. As a result, all public goods participants gain voting power within the Chain DAO.

----

<img width="1413" height="806" alt="image" src="https://github.com/user-attachments/assets/50e0a1ca-1dda-43f4-96a7-2aed9794c6e8" />

----

### The cross-chain power enheritance.

Is this the final level of the system?

Not quite.

Using bridges, a new L2 chain could decide to inherit voting power from the Chain DAO, as well as from a token pool it actively promotes. This becomes a strategy for attracting users: offering small benefits to all active participants, and larger voting power bonuses to carefully selected partners.

----

<img width="1413" height="806" alt="image" src="https://github.com/user-attachments/assets/101a0940-d0d2-4dcf-a1cd-64fd9677d7df" />

----

### The main risk.

The final question is the cost of gas. Will all these voting power transfers be cheap enough to justify integration?

A few years ago, when minting an NFT could cost $50–60, the answer would likely have been no.

Today, with extremely low L2 fees, the answer is probably yes. Many projects may accept slightly higher gas costs in exchange for on-chain partnerships, meaningful governance systems, and richer ecosystem interactions.
