---
Aliases: The Lightning Network Sucks
title: THE LIGHTNING NETWORK SUCKS
authors: 
year: 2022
publisher: 
DOI: 
URL: https://www.youtube.com/watch?v=J8mMknZPOTA
---

![](https://www.youtube.com/watch?v=J8mMknZPOTA)

# Abstract
The note titled "THE LIGHTNING NETWORK SUCKS" criticizes the Lightning Network, a Layer 2 protocol built on top of Bitcoin. The note highlights three critical flaws of Bitcoin: high and unpredictable fees, performance and scalability issues, and price volatility. It argues that the Lightning Network fails to address these issues and instead introduces new problems. The note discusses the complexities of routing payments through other users' channels, the need for third-party custodial wallets, and the potential for centralization and security vulnerabilities. It concludes that the Lightning Network resembles an attempt to recreate banks, but may be accomplished without Bitcoin.

# Transcript by [[whisper]]
The [[Lightning Network]] sucks.

[[Bitcoin]] has three critical flaws that prevent it from being used as currency.
1.  High and unpredictable fees. For small transactions like buying coffee, the fees are a deal breaker.
2.  Performance and scalability. It takes too long to confirm a transaction and Bitcoin can't process more than 7 transactions per second.
3. Price volatility: You can't use something so volatile as a unit of account to price goods and services in Bitcoin. 

Rather than trying to fix the problems with Bitcoin, the community has decided to simply ignore them and create a different set of problems with the Lightning Network. The first thing to note about the Lightning Network is that it doesn't even attempt to address price volatility because regardless of what technical obstacles are addressed with fees and performance, the price of Bitcoin is not backed or anchored to anything real and thus swings wildly based on the mood of the market.

Don't ignore that important detail, even though I won't mention it again. The Lightning Network is a Layer 2 protocol that sits on top of Bitcoin and offers off-chain services. That means it's trying to solve the problems of Bitcoin's blockchain by simply not using it, or any blockchain for that matter.

After all, the best way to fix a blockchain is to replace it with something that isn't a blockchain.
Lightning is just a bunch of new wallets and channels between them that get funded with Bitcoin.
But when Bitcoin moves around between them, it does not move anything in the blockchain on Layer 1
until or unless a channel is closed. Just like we send a packet of data over the internet containing a text message or something, we can send a packet of data over Lightning that contains Bitcoin.

## The Most Important Detail
The most important detail to remember is that nobody can set up a channel with everybody on the network,
so payments are routed through other people's channels. This creates all kinds of complications and is what I'll spend most of this video discussing.

But before I do, I want to point something out from 50,000 feet. The Lightning Network doesn't even really need to use Bitcoin necessarily. You can trade other non-Bitcoin digital assets using these channels.
And just as a crypto exchange is a platform that can be used to trade many things,
the Lightning Network is also just a platform that could have been built on top of any storage layer.
Any database could act as the Layer 1, not just the Bitcoin blockchain.

## Bitcoin is not the unique storage layer
There isn't anything about Bitcoin that makes it uniquely capable of being the Lightning storage layer.
In fact, if the Lightning Network ever works properly, there may only rarely ever be a need to close channels and commit transactions to the blockchain anyway. It seems people just like having the option of permanently committing their transactions, even if they rarely do. But let's get back on track.

Remember, the point of Bitcoin is self-custody of a digital unit of value that can be transferred through a trustless, permissionless, decentralized network. Let's go through these goals one by one and see how the Lightning Network stacks up. As with all things crypto, onboarding new users can be a bit annoying.
It's a different wallet off-chain.

But more importantly, as mentioned previously, nobody can possibly be expected to open new channels with everybody they intend to transact with and keep those channels funded. Especially because if you're not online 24-7, you may miss incoming payments. So it's almost guaranteed that just about all users, individuals, and companies will be forced to use some kind of third-party custodial wallet that is both better connected to the broader network and online all the time.

That reintroduces all the counterparty and censorship risks Bitcoin was trying to address. 

There is no cold storage.
Routing is an unsolved problem when you could have bad actors setting up channels with the intent to disrupt the network. How do you deal with a node that attempts to steal funds in transit? The funds are wrapped in layers of encrypted data, like an onion, so in theory each node doesn't know the details of the transaction or its final destination.

But even if there are details kept from each individual node, they could still become a choke point on the network and use that power to be a gatekeeper of sorts. People like to say Lightning works exactly like the Internet and the Internet works, therefore Lightning will work.

## Permissionless?
But the Internet is made up of service providers who cooperate with each other, which is just another way of saying they trust each other. And we already see this behavior starting to emerge on the Lightning network as well. Larger nodes simply won't accept incoming channel requests unless the counterparty has a reputation of being a good actor because they know the stakes. Both parties must agree to set up a channel.

That's the opposite of permissionless. But more importantly, the implication of that requirement is the ability to open a channel also means each party could have the ability to close a channel, which creates a whole new distinct category of attack involving the bad actor closing a channel with a broadcast to the blockchain of a past channel state, not the final channel state.

Imagine a scenario in which you receive funds in your Lightning wallet, then the person who sent the funds closes the channel and reverses the transaction on the actual Bitcoin blockchain. It's such a big problem that an entire category of new security tool called a watchtower has been invented to monitor for such fraud, albeit retroactively, and after it's too late to do anything about it other than try to seek revenge with a new punitive transaction to steal the money back.

## Centralization
While one could argue Bitcoin gets better, i.e. more secure, the more decentralized it becomes, the exact opposite is true for Lightning. The more channels your Bitcoin must traverse to reach its destination,
the more likely it will be to fail because it runs into insufficiently funded channels or simply can't find a route in time.

The amount of Bitcoin you transfer must be less than the amount commit to each channel along its path, or the transaction will fail. The best way to reduce the number of path routing errors is to reduce the number of paths and centralize.

A few years ago, almost half the Lightning transactions of any non-trivial amount would fail. Today, successful transactions have reached the high 90s, but to get that number closer to 100% and compete with traditional banks, even greater centralization will almost certainly be required,
and the more centralized a network becomes, the more attractive a target each node becomes for hackers, and the more susceptible the network becomes to denial of service attacks. Fees are a combination of routing charges for data moving between nodes, and Bitcoin's usual transaction fees for opening and closing channels. While it's not clear how profitable these nodes will be, one thing that is clear is the inability to determine the routing path in advance makes the fees unpredictable at the time of payment. 

Channel funding is private, so you can't know how much it will cost or whether it will even work for the amount you intend to transfer at the time the payment is made. Imagine trying to sell coffee, but the actual final amount to be collected is unknowable and may never even arrive.

Some people argue Lightning has better privacy than regular Bitcoin transactions because the transactions are not commit to a publicly accessible blockchain, but this whole setup opens these centralized Lightning nodes to all kinds of legal liability.

How is any of this different than a regular bank?

Why wouldn't Know Your Customer and anti-money laundering regulations not apply to each and every node on the network? Government institutions like the Federal Reserve aren't regulating dollars, they are regulating financial institutions. If you perform the functions of a financial institution, you are a financial institution, regardless of the currency you use. You can't set up a bank in New York and claim regulations don't apply to you because you only trade in Mexican pesos. Why should Bitcoin be treated any different?

## So, how did Lightning do?
High and unpredictable fees. Fees are lower, but still unpredictable.
Performance and scalability. Transactions are faster if they work at all.
Price volatility unchanged.

Bottom line, the Lightning network isn't a terrible idea. It's clever.

If it was trying to move something other than money, it might even be useful. But for better or worse, money serves a unique function in society and is treated very differently than other types of bits you might want to send through the internet. And banks already work pretty well. This really just looks like an attempt to recreate banks, but worse, without any of the benefits of Bitcoin.

Let me know in the comments if you think I got something wrong. If you found this content helpful, please consider liking the video and subscribing to my channel. It really does help get this channel more exposure and keep me motivated to produce more content.
