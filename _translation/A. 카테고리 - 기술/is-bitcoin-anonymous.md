# IS BITCOIN ANONYMOUS?
*  [BITCOIN MAGAZINE](https://bitcoinmagazine.com/authors/bitcoin-magazine) AUG 17, 2020

Bitcoin is not entirely anonymous. In reality, it is /pseudonymous/ because each user has a public address that theoretically could be traced back to an IP address or exchange account (and by proxy, an actual identity) through proper network analysis.

So instead, a better question is, /to what extent/ is Bitcoin anonymous?

It is anonymous in the sense that the components of Bitcoin, such as addresses, private and public keys, and transactions, are all read in text strings, such as a public address, that in no way directly link to anyone’s personal identity. (If an address is used on an exchange that implements KYC — Know Your Customer — then that address may be easily linked to a real-world identity.)

General understanding of blockchain technology by the public was not prevalent in Bitcoin’s early days. It was commonly thought that Bitcoin was a safe haven for criminals and terrorists because it was untraceable and entirely anonymous. As blockchain technology became more understood by organizations and the public alike, it became more apparent that Bitcoin’s massive public ledger was actually a gold mine of information for authorities instead; any bitcoin transactions that have ever taken place are forever inscribed in an immutable ledger.

Every bitcoin transaction is publicly broadcasted on the Bitcoin blockchain. Because all transactions are permanent and public, a massive map is being created as time goes on that allows simple analytical tools to paint a picture of where bitcoins are going. Bitcoin addresses are “anonymous,” but if an address can somehow be linked to a real-world identity, Bitcoin offers no privacy. There are a number of ways to connect addresses to real-world identities, most notably via KYC/AML (Know Your Customer/Anti-Money Laundering) policies at exchanges and blockchain analysis (eg., address clustering).

There are  [a number of privacy-enhancing tools available](https://bitcoinmagazine.com/articles/bitcoin-privacycoin-tech-making-bitcoin-more-private)  for Bitcoin users as well, but most aren’t perfect. Unless you really know what you’re doing, it’s best to assume you have little privacy.

### WHAT ARE BITCOIN MIXERS?
Bitcoin mixers are solutions (software or services) that let users mix their coins with other users, in order to preserve their privacy.

While Bitcoin addresses are “pseudonymous” — meaning, they don’t, in themselves, reveal the identity of their owner — they can often still be linked to real-world identities. For example, if you withdraw bitcoin from an exchange where you’ve identified yourself, the exchange knows that the withdrawal address is yours. There are also more advanced techniques — such as blockchain analysis — to tie Bitcoin addresses to real-world identities.

The next time coins move from these addresses, users risk revealing all sorts of personal information. Depending on how they spend the coins, they could reveal how many coins they own (even on other addresses), what they spend their money on, and more.

By mixing their coins, users can obscure the ties between their Bitcoin addresses and real-world identities. This allows them to use Bitcoin more privately.

### HOW DO BITCOIN MIXERS WORK?
A number of mixing strategies have been proposed and developed over the years. These range from  [fully centralized solutions](https://bitcoinmagazine.com/articles/shuffling-coins-to-protect-privacy-and-fungibility-a-new-take-on-traditional-mixing-1465934826)  where all users trust a mixer, to  [solutions](https://bitcoinmagazine.com/articles/shuffling-coins-to-protect-privacy-and-fungibility-a-new-take-on-traditional-mixing-1465934826)  where users don’t need to trust anyone, to  [solutions](https://bitcoinmagazine.com/articles/shuffling-coins-to-protect-privacy-and-fungibility-a-new-take-on-traditional-mixing-1465934826)  that resemble Lightning Network-style payment channels, to even using privacy coins like Monero as an  [intermediary step](https://bitcoinmagazine.com/articles/how-bitcoin-users-reclaim-their-privacy-through-its-anonymous-sibling-monero-1472761633)  in the mixing process.

Instead of exploring all (potential) options, let’s stick to two of the most popular solutions available today.

*CENTRALIZED MIXERS*

Centralized mixers are services that accept bitcoin payments and send different coins in return. If many people use a particular mixing service, it becomes increasingly difficult for an outsider to tie any of the “incoming” coins to any of the “outgoing” coins. This breaks the transaction trail, offering privacy to the users.

Centralized mixers leave two big problems unsolved, however. One, users need to trust their privacy with the mixer. Since the mixer knows exactly which user sent and received which coins, the mixer could re-establish the trail of ownership. If the mixer is willing to share this data with interested parties (perhaps because they have to by law or in return for payment), the user would lose his privacy after all. And two — perhaps even worse — the mixer could refuse to make the return payment, basically stealing the user’s coins.

*CHAUMIAN COINJOIN MIXERS*

More modern mixers have solved both of these problems. Chaumian CoinJoin mixers, for example, let a large group of users cooperate in making one large payment to themselves. Basically, if a hundred users all send exactly 0.1 BTC to a new address they control, and then merge these 100 transactions into one big transaction, everyone gets 0.1 bitcoin back, but no one can see where they got it from.

On top of that, Chaumian CoinJoin mixers can be designed in such a way that not even the entity that “merges” the transaction can figure out which coins went where. Nor could it steal any coins: Users wouldn’t sign the merged transaction if they didn’t get their 0.1 BTC back.

### WHAT ARE SOME POPULAR MIXERS?

An example of a popular centralized mixer is  [smartmix.io](https://smartmix.io/) . However, /Bitcoin Magazine/does not endorse, let alone recommend using any centralized mixers, including smartmix.io, because of the unsolved problems mentioned above.
 [Wasabi Wallet](https://www.wasabiwallet.io/)  is a popular bitcoin wallet that has a Chaumian CoinJoin mixer built in. And while Wasabi Wallet’s infrastructure is technically centralized, it is cleverly designed so the operator cannot deanonymize users nor steal any funds. It also offers a user-friendly interface to help users distinguish between mixed coins and non-mixed coins.

Similar to Wasabi Wallet, the  [Samourai](https://samouraiwallet.com/)  wallet also offers a Chaumian CoinJoin mixing service, called Whirlpool. While Wasabi Wallet is currently only available on desktop, Samourai is also available on mobile. However, to really use Samourai Wallet in a privacy-friendly manner (where users’ privacy is protected even from the Samourai Wallet team), users do need to connect their wallet to their own full Bitcoin node.

An alternative option to mixing coins is using  [JoinMarket](https://joinmarket.me/) . JoinMarket allows users to merge transactions into bigger transactions through (regular) CoinJoin, which also helps obfuscate their trail of coins and protects their privacy. An interesting benefit of JoinMarket is that participants in such merges are financially incentivized to offer their coins to be mixed: Users that want to mix their coins would pay a small amount of fee to be able to do so.

### WHY WOULD YOU MIX YOUR COINS?

You would mix your coins to protect your privacy, and there are many reasons to protect your privacy. In short, you might not necessarily want the world to know where you spend your money, what you earn or how much bitcoin you own.

Take the more concrete example of someone who just got a raise. They may not want their landlord to find out, as this landlord might see it as a good opportunity to increase the rent. A closeted-homosexual may want to pay for gay pornnography without anyone knowing, especially in a regime where being gay is treated like a crime. A dissident pseudonymous journalist may want to get paid for his articles without the regime in his country finding out who he is. A teenage girl from a conservative family might want to purchase contraception without her parents finding out. A Democrat in a Republican town may want to donate money to his favored politician without drawing the ire of his neighbours. A wealthy bitcoiner may not want to reveal his holdings as it would make him a target for kidnapping, extortion or worse. And so on.

Really, there are quite literally countless reasons why people may want privacy. In fact, even if you do not care about your own privacy at all, you may want to altruistically mix your coins to increase the anonymity set of people who do.

### IS COIN MIXING JUST FOR CRIMINALS?

As pointed out above, no, coin mixing and other forms of privacy are not just for criminals. In fact, privacy is a human right established in the  [Universal Declaration of Human Rights](https://www.un.org/en/universal-declaration-human-rights/index.html)  (article 12).

Of course, criminals do benefit from all sorts of privacy as well, including privacy gained from mixing their coins. Criminals enjoy many of the freedoms that the rest of us do; that’s the price we pay to live in a free society. (And even in regimes without many such freedoms, criminals tend to continue to operate … and “criminals” may, in these places, be people that speak the truth or hold a certain belief.)

Indeed, the perception that mixers are mainly used by criminals appears to be false. According to [ research](https://bitcoinmagazine.com/articles/chainalysis-most-mixed-bitcoin-not-used-for-illicit-purposes)  by blockchain analytics firm Chainalysis, for example, mixers are mostly used by regular Bitcoin users that simply want privacy. Coins that have been used for illicit purposes represent a minority of all mixed coins.

### CAN BITCOIN MIXERS BE BANNED?

Whether or not bitcoin mixers can be banned is really a legal question — not a technical question. It will, therefore, differ from jurisdiction to jurisdiction. There are  [examples](https://bitcoinmagazine.com/articles/dutch-authorities-shut-down-bestmixer)  of mixers that have been banned, as authorities claimed that the service was being used to launder money.

The most popular mixing services are currently centralized (either trusted or untrusted), which does mean they could be shut down relatively easily by authorities. So far, however, many mixing services continue to operate unencumbered.

If centralized mixing services do face bans and shutdowns, decentralized mixing services might take their place. These would be harder to take down.

### DO MIXED COINS RUN THE RISK OF BEING LABELLED AS ‘TAINTED’?

Depending on how coins are mixed, it can be possible to recognize mixed coins as “tainted.” Mixers like the one used by Wasabi Wallet leave a clear trail of mixing. So while the premix history of the coins would be obscured, the mixing itself would not be.

At the time of writing this article, no mixed coins have been labeled as tainted and refused by bitcoin exchanges or merchants, however.

### WHAT IS BLOCKCHAIN ANALYSIS?

The Bitcoin blockchain is an open and transparent ledger. This means that every payment is publicly visible to anyone. As such, it’s easy to see how coins move from address to address. (This is not completely, technically the best way to phrase it, but it’s close enough for the purposes of this introductory guide.)

*Further Reading:  * [What Is a Blockchain?](https://bitcoinmagazine.com/guides/what-blockchain) 

On top of having an open and transparent ledger, the way Bitcoin transactions are constructed often reveals information about users. Most notably, a transaction that has several “inputs” (chunks of coin) suggests that all of these inputs belong to the same user. This allows for address clustering, but there are many other such privacy leaks. (See the  [Bitcoin Privacy wiki](https://en.bitcoin.it/wiki/Privacy)  for more examples.)

As the name suggests, blockchain analysis is the act of using such privacy leaks to analyze the blockchain.

