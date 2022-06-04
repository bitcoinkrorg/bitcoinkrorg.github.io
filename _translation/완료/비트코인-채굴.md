# bitcoin mining

One of the fundamental questions many people have about Bitcoin revolves around the origin of the coins themselves. Questions about its value, security and history all eventually lead to a pair of questions: Where do bitcoin come from and what is bitcoin mining?
### “PROOF OF WORK”
If you’ve heard of Bitcoin, there’s a chance you may have also seen the phrase “ [proof of work](https://bitcoinmagazine.com/articles/genesis-files-hashcash-or-how-adam-back-designed-bitcoins-motor-block) ” thrown around. This process is at the heart of Bitcoin’s ability to work as intended and is what allows the decentralized network of computers running Bitcoin to stay in sync with each other. In fact, this invention is what really separates Bitcoin from any prior attempts at creating digital money.


While traditional money is created through (central) banks, bitcoin are “mined” by Bitcoin miners: network participants that are competing to be the one computer that is allowed to record all of the recent transactions. If your computer can win this competition, then you’ll get to award yourself some bitcoin as a reward for your efforts.

### “THE LOTTERY”
Finding a block most closely resembles a type of lottery. The best way to win this lottery is to guess as many times as possible before someone else comes up with the lucky number (we call this number a “nonce” and miners are attempting to “guess” a nonce that is less than or equal to a particular target).
Every bitcoin transaction waiting to be completed will first be sent into the “mempool,” a holding area for pending transactions on the Bitcoin network. Miners will take the pending transactions that are waiting to be recorded and combine them to create a “block” of transactions.
In order to win the lottery, a miner will need to take their block of transactions, information from the latest confirmed block, and add in a random lucky number that satisfies some conditions faster than any other miner on the network. They include the information from the latest confirmed block in order to create a chain (“blockchain”) of blocks.

It normally should take trillions of guesses in order to guess the correct lucky number; the entire process is intended to take about ten minutes from start to finish, but depends on the number of guesses that miners are making. Finding this lucky number is difficult: you’re forced to simply guess as many times as you can, as fast as you can.
Because of this “lottery,” there are two significant outcomes:
* For one, proof of work prevents miners from creating bitcoin out of thin air: they must burn real computing energy with each guess in order to have the chance to earn bitcoin. Electricity to power the miners is not free, therefore creating a true financial cost to mining bitcoin.
* Second, proof of work ossifies Bitcoin’s history. If an attacker were to try and change a transaction that happened in the past, that attacker would have to redo all of the work that has been done since to catch up and establish the longest chain. This is practically impossible and is why miners are said to “secure” the Bitcoin network.
Anyone can become a Bitcoin miner to try and earn these coins. However, mining has become increasingly industrialized over the years and is nowadays mostly done by dedicated professionals with specialized hardware, cheap electricity and big data centers.

### WHAT IS THE MINING REWARD?
In exchange for securing the network, and as the “lottery price” that serves as an incentive for burning this energy, each new block includes a special transaction we call the “coinbase transaction.” It’s this transaction that awards the miner with new bitcoin, which is how bitcoin first come into circulation.


At Bitcoin’s launch, each new block awarded the miner with 50 bitcoin, and  [this amount halves](https://bitcoinmagazine.com/guides/what-is-the-halvening)  every four years: Currently each block includes 6.25 new bitcoin. This is known as the “block subsidy.”
Additionally, miners get to keep any fees that were attached to the transactions they included in their blocks. Because the number of transactions per block is limited, all Bitcoin transactions include a fee as an incentive for the miners to prioritize their transaction. The larger the transaction fee, the higher the likelihood of your transaction being picked up from the mempool by miners and processed more quickly.
These transaction fees, along with the block subsidy, are generally known as the “mining reward.”Thus, mining is the mechanism used to introduce new bitcoin into the system and to set the history of transactions in a way that is computationally impractical to modify, and miners are incentivized by the block reward, made up of both that new block of bitcoin introduced and fees paid by those conducting transactions.

### WHAT IS BITCOIN MINING DIFFICULTY?
Bitcoin miners pick up transactions in the mempool and hash them. Their goal is to “guess” a hash that is lower than or equal to the network target.
Bitcoin mining network difficulty is the measure of how hard it will be for miners to find a hash. Network difficulty is equal to the inverse of network target: network target = 1 / network difficulty. The lower the network target, the harder it is to find a valid block (because it is calculated as the inverse of network difficulty).


By design, the Bitcoin network seeks to maintain consistent block times of 10 minutes. The mining difficulty is programmatically adjusted every 2,016 blocks (approximately every two weeks) so that it’s as likely as possible that a miner will successfully add a block to the blockchain once every 10 minutes.
The  [difficulty is adjusted](https://bitcoinmagazine.com/articles/bitcoin-hash-rate-hits-all-time-high-behind-price-rise-private-pools-in-china)  based on how many miners (and, therefore, how much hash power) are active on the network — as more miners participate, mining becomes more difficult so that this 10 minute interval is maintained.

### WHAT ARE BITCOIN MINERS?
Bitcoin miners are the network participants that chronologically order transactions by including them in the Bitcoin blocks they find. The equipment bitcoin miners use to perform this task is known as  [bitcoin mining hardware](https://bitcoinmagazine.com/bitcoin-mining/bitcoin-mining-hardware) , with individual devices also referred to as bitcoin miners (like the organizations that leverage them) or mining rigs.
These hardware devices are specialized computers designed and manufactured to most efficiently solve the computationally difficult problem that is the key to finding (mining) the next block of bitcoin.
Anyone can become a miner as long as you have the correct hardware and software.
### BITCOIN MINING HARDWARE
Bitcoin mining hardware consists of devices specially designed to mine bitcoin most effectively. These computers “guess” the correct hash as quickly and efficiently as possible and are run by Application Specific Integrated Circuits or ASICs that are designed to operate for that one function. While the earliest mining was conducted by standard computer CPUs, mining operators were incentivized to achieve more hash power and did so partly through the creation of customized machines, first with graphics processing units (GPUs) and, later, with ASICs.


*We’ve covered    in more depth as its own guide where we break down a few different types of computers and their hashpower.* [bitcoin mining hardware](https://bitcoinmagazine.com/bitcoin-mining/bitcoin-mining-hardware) 

### BITCOIN MINING POOLS
In one sense, mining is a competition to solve an algorithmic puzzle first, with the chances of success determined by the proportion of mining power contributed to the network. If you are able to contribute a large portion of the total hash power, you have a better chance of solving the puzzle first and receiving the connected bitcoin reward. If you are unable to contribute a large portion of the hash power, you are less likely to mine a block successfully.
To increase their chances of successfully mining blocks and collecting rewards, miners who are only able to contribute relatively small amounts of hash power to the network have banned together in groups called  [mining pools](https://bitcoinmagazine.com/bitcoin-mining/what-are-bitcoin-mining-pools) .
These are decentralized groups organized and operated by third parties to coordinate hash power from miners around the world and then share any resulting bitcoin in proportion to the hashpower contributed to the pool. Mining pools also run full Bitcoin nodes on behalf of the individual miners.
*For more coverage on   , visit our standalone guide on pools.* [mining pools](https://bitcoinmagazine.com/bitcoin-mining/what-are-bitcoin-mining-pools) 

### CLOUD MINING
Cloud mining allows you to mine bitcoin without having to invest in any hardware, giving you access to the hash power from someone else’s mining hardware via the cloud. Companies that offer cloud mining contracts allow customers to buy hash rate from the mining hardware the company is operating.

Buyers typically need to pay upfront for the contract and an ongoing maintenance fee. In return, users generate revenue on the hash power they paid for — the higher the purchased hash rate, the more bitcoin you are likely to receive (as revenue). Buyers need to assess the likelihood that the revenue generated from the hash power is larger than the cost of buying and maintaining the contract.
In general, those who offer cloud mining services tend to charge purely based on the amount of hash power being accessed or on a monthly or yearly contract basis. Cloud mining models include leased hashing power, hosted mining and virtual host mining.
Generally, customers need only open an account with a cloud mining company and select the exact terms of their contract. However, this means that it can be difficult to verify that you are receiving exactly what you’ve paid for. There have been many scams and unfairly priced contracts in the industry, so buyers should do their own research before purchasing a contract.

### HOW TO MINE BITCOIN
You may be determined to mine bitcoin regardless of the many factors surrounding its profitability. As stated above, mining is an integral practice to the network and there are few ways to participate in Bitcoin as directly as mining it yourself.

Here are some tips on what you’ll need to get started:
*1.* *A Bitcoin Wallet*
As noted above, any bitcoin earned from mining will need to be sent somewhere. That’s where a  [bitcoin wallet](https://bitcoinmagazine.com/guides/what-are-bitcoin-wallets)  comes in. Basically, if you want to be directly involved in Bitcoin, you need a wallet.
*1.* *Bitcoin Mining Node*
Bitcoin mining has become an industry in itself, with a market of specialized devices known as ASICs (application-specific integrated circuits made specifically to optimize for the highest hash rate at the lowest energy costs. While it’s technically possible to attempt mining on your home computer or other device, it isn’t possible to successfully mine this way and you’ll lose money on energy costs along the way.
Even with a handful of  [ASIC mining rigs](https://bitcoinmagazine.com/articles/want-to-learn-about-bitcoin-try-conference-driven-development) , an individual will need to connect with a mining pool to profitably mine bitcoin.
*1.* *Bitcoin Mining Software*
Bitcoin mining software is the bridge between your mining hardware and the Bitcoin network. It would also be the means by which you connect your miner to a mining pool and get rewarded for your hash rate. Furthermore, it will guide any payments to your Bitcoin address.

### BITCOIN MINING SOFTWARE
While the hardware conducts the mining process, the software is also integral to the Bitcoin network and for miners. This is the bridge between the mining hardware’s efforts and the Bitcoin network at large.
This software can monitor the incoming and outgoing data from a miner, report statistics about the performance of the hardware and connect individual miners to a mining pool.

### BITCOIN WALLETS AND MINING SOFTWARE
Bitcoin wallets are integral to the use of mining software and capturing the bitcoin rewards that miners hope to collect. As this software connects miners to the Bitcoin network, it is also the conduit by which they receive their bitcoin and so this software must be connected with a bitcoin wallet.
Bitcoin mining software will pay out mining rewards to a miner’s Bitcoin address, which can be obtained by creating or downloading a bitcoin wallet.

### THE BEST BITCOIN MINING SOFTWARE
There are many bitcoin mining software products out there and the best fit for any given miner or mining operation will depend on their specific needs. Popular options for individual miners include Hive OS, Minerstat, ethOS Mining OS, Simple Miner and Hashr8 OS.

Most large mining farms operate their own in-house solutions.

### IS BITCOIN MINING PROFITABLE?
Because bitcoin mining is essentially a competition, the question of profitability is largely about achieving a competitive advantage. For many large operations, that advantage is achieved by running a relatively huge number of mining rigs at the lowest possible power costs.
Those with the most up-to-date and powerful mining hardware also have an advantage, though it’s possible to be competitive with older equipment if your electricity costs are relatively low. Smaller scale mining operations can find success by optimizing for their power costs.
*If you’re just getting started, think twice before you start mining and take a look at our   .* [mining profitability guide](https://bitcoinmagazine.com/bitcoin-mining/is-bitcoin-mining-profitable) 

### IS BITCOIN MINING CENTRALIZED?
There is nothing inherent within Bitcoin that means mining should be a centralized process — anyone, anywhere with a device capable of connecting to the Bitcoin network and hashing mempool transactions can participate in mining for bitcoin. But mining has become such a lucrative industry and mining hardware has become so specialized that  [a relatively small number of operations](https://bitcoinmagazine.com/articles/op-ed-challenge-mining-centralization-unveils-bitcoins-elegant-design)  contribute the bulk majority of the network’s hash power.
Concerns around Bitcoin mining centralization  [have been circulating since at least 2014](https://bitcoinmagazine.com/articles/opinion-on-mining-1403298609) .

Economies of scale have led to the concentration of mining power among those who can operate the most efficient miners at the lowest cost of energy. As of this writing, most of the Bitcoin network’s mining hash power comes from China, though significant mining operations are  [located across the world](https://bitcoinmagazine.com/articles/bitcoin-mining-in-north-america-a-new-gold-rush-in-the-new-world) .

### HOW MUCH ELECTRICITY DOES BITCOIN MINING USE?
As you have probably gathered by now, mining is an energy-intensive process that, in a reductive sense, turns computing power into bitcoin (while verifying transactions on the world’s most robust blockchain in the process). One of the primary considerations for miners is the tradeoff between their energy costs and potential bitcoin rewards.
But it’s  [difficult to estimate](https://bitcoinmagazine.com/articles/cost-sound-money-new-tool-tracks-bitcoins-energy-consumption)  exactly how much energy around the world is being consumed by miners at any given time. Bitcoin’s transparency allows anyone to see  [the amount of hash power](https://mempool.space/graphs)  being applied to the network, usually measured in the number of terahashes per second that the network is performing as part of the mining process.
You can then estimate how much power the network is using to perform these hashes, based on the energy-to-hashrate efficiency of the mining hardware in use — but not all miners are operating with the same efficiency and an exact calculation is virtually impossible.

As of 2018,  [written testimony](https://www.energy.senate.gov/public/index.cfm/files/serve?File_id=8A1CECD1-157C-45D4-A1AB-B894E913737D)  by a computer scientist from Princeton University, presented to the U.S. Senate, estimated that bitcoin mining accounts for slightly under 1 percent of the world’s energy consumption (more than the states of Ohio or New York consume) at 5 gigawatts. The  [University of Cambridge](https://www.cbeci.org/)  operates a live Bitcoin network energy estimator.

### IS BITCOIN MINING BAD FOR THE ENVIRONMENT?
Bitcoin’s energy consumption is not merely for the sake of computers solving arbitrary math problems. It is a critical component of proof of work, the consensus mechanism that keeps bitcoin from being created out of thin air and solidifies Bitcoin’s transaction history
.In some sense, Bitcoin’s energy consumption can be thought of as the world’s most direct and efficient conversion of  [raw power into value](https://bitcoinmagazine.com/articles/op-ed-bitcoin-uses-a-lot-of-energy-so-where-are-the-energy-companies) .
By creating such a direct line between energy use and value creation, Bitcoin has created a natural incentive for energy efficiency. Bitcoin miners are directly motivated to apply energy in efficient ways (thus saving on power costs and maximizing their bitcoin profits) and many leverage renewables to do so. Some estimates have found that  [as much as 74 percent](https://bitcoinmagazine.com/articles/study-74-percent-of-bitcoin-mining-powered-with-renewable-energy)  of the Bitcoin mining network leverages renewable energy like hydro and solar power.
In many cases, mining contributes to the development of better energy infrastructure, leading to a reduction of carbon emissions. An example of this is Bitcoin mining units that are installed next to oil wells.

In the process of pumping oil, these wells also produce excess gas. It is usually not enough gas to justify building a pipeline to get to market. So the oil wells vent some of it (into the air) and  [burn or flare the rest of it](https://bitcoinmagazine.com/articles/oil-field-alchemy-how-bitcoin-can-turn-waste-emissions-proof-work) . Instead of burning this excess gas, oil wells can leverage bitcoin mining to turn it into value in a more environmentally- friendly manner.
In addition, there are companies that are setting up Bitcoin mining facilities next to electricity grids to act as stabilizers. If installed next to an electricity grid, a Bitcoin mining facility acts as an inverse battery. It enables stable demand pressure on the power grid and can curtail instantly during supply shocks. This makes electricity grids more efficient, which lowers future development costs, especially in the renewable energy sector (solves intermittency + congestion issues).
Bitcoin’s unique approach to value creation could incentivize a more sustainable approach to energy use around the world.

### IS BITCOIN MINING LEGAL?
 [Bitcoin mining is legal](https://bitcoinmagazine.com/bitcoin-mining/is-bitcoin-mining-legal)  in most countries. From a legal standpoint, many countries treat bitcoin as an asset or property, rather than a currency, and have established some regulatory frameworks with that status in mind. Most countries do not have formal laws established around bitcoin mining, making the practice legal by default.

However, bitcoin mining, as well as the general use of bitcoin, is formally illegal in a few countries. Some governments have banned the practice because it represents a threat to their national currencies.
This legal landscape is ever-evolving, so anyone interested in bitcoin mining should consult with legal counsel familiar with their specific jurisdiction and circumstances.
*Because the    changes so frequently, we are beginning to keep track of each country in a separate guide.* [legal status of Bitcoin](https://bitcoinmagazine.com/bitcoin-mining/is-bitcoin-mining-legal) 

### HOW TO MINE BITCOIN ON MY PHONE?
The mining difficulty is now so high that it is not possible to mine bitcoin with a smartphone. Back in 2014, you could even have a  [USB miner](https://bitcoinmagazine.com/articles/the-newest-fastest-usb-bitcoin-miner-of-the-world-hello-hexfury-1395738010) !
A platform that indicates you can mine bitcoin on your phone or low power devices is likely suggesting you can mine an alternative cryptocurrency and be paid in bitcoin for your contributed computing power, but it cannot mine bitcoin directly.
To mine competitively today, you need to know what you’re doing, you must be willing to invest significant resources and time, and — last but not least — have access to cheap electricity.
