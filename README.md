# OBJKTIV: 🌮 Tezos 🌮 NFT Viewer
⚠️ Heads Up! This is an early release, alpha version. As such, this dApp is not fully bug tested. ⚠️

## About
This is the results of a few nights of tinkering around for fun. The OBJKTIV dApp allows you to view hic et nunc and fxhash Tezos NFTs.

The alpha version includes wallet sync'ing, anonymous wallet viewing, gallery creation, popout objkt viewer w/ bg color selector, and day/night mode.

All settings are stored via local storage, so settings will not carry over between devices. Settings export will come shortly.

The goal is to stand OBJKTIV up as a fully decentralized application, though centralized indexers are used as a dependency in its current incarnation. With this in mind, most views, galleries, objkts, etc can be shared via URL. The goal is that basically everything that dictates your viewing experience is encoded in the URL, which means it is 100% shareable.

## FAQ
### Is this application safe?
The only interaction with your wallet that takes place is an address request. No transactions, contract origination, minting, selling, trading, etc occurs in any way.

Your security is always in your hands alone. Do not trust anything on the internet!

### How can I report bugs/issues?
Please report any OBJKTIV related issues using the Google form below.

https://forms.gle/qb99XiCbvHgqseds6

### How can I request features?
Please provide any OBJKTIV feature requests using the Google form below.

https://forms.gle/FDZHQAe9K7sXpqxh8

### Why do some images not load?
This application makes ZERO attempts at hiding the true nature/state of IPFS and its role in non-fungible tokens functionality. That being said, no CDNs will ever be used, and no special loading, parsing, or manipluation takes place while loading IPFS resources.

If you are seeing missing images or slow load times this means your IPFS resource needs more pinning support or that the gateway you are using is under stress or suffering outages.

It is always recommended that if you appreciate an NFT, whether you own it or not, you should should pin it using a local IPFS node or at least a free tier plan with an IPFS node provider.

It's up to all of us to support artists by not only buying artwork but also supporting the distributed hosting network that keeps it alive for you to enjoy!

### How can I contribute?
A proper open source repository will shortly follow the publication of this alpha version.

The code, in its current state, is not worthy of contribution and is, to say the least, sub standard. This was a silly side project that has taken on some small amount of life. As such, it will need a refactor post-alpha before pull requests are accepted.

--

Bye! 🤗