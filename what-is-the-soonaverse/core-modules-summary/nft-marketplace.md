# NFT Marketplace

Our NFT Marketplace utilizes a stable, consistent, private architecture, which blends centralized and decentralized technologies to deliver NFT based funding and trading on the existing IOTA mainnet. As always, our goal is to establish a clear and well-defined path to decentralization, either through Shimmernet or Assembly once these groundbreaking networks become available.

We have delivered three new and essential pieces to make Soonaverse Spaces more useful and successful for our members:

1. **NFT Builder** — Guardians and other artist can create NFTs and make them available for sale (both photos and videos will be supported).
2. **NFT Marketplace** — Browse existing NFTs to purchase immediately, or make offers for others that aren’t listed for sale.
3. **Mint** — Seamlessly migrate your NFTs to IOTA once the tokenization framework is deployed.

### NFT Builder

An artist should be able to focus all their energy into their art. They shouldn’t have to worry about the intricacies of setting up their own NFT launchpad. With the new NFT Builder, artists no longer need to worry about things like IPFS, creating their own smart contracts, setting up a dedicated website, etc. We simplify the entire process, plus you have the added benefit of your work being available within the Soonaverse and the 10,000+ and growing Soonaverse community waiting to engage with your artwork.

The NFT Builder will initially allow artists to choose and upload three different types of NFT collections: Classic NFTs, Generated NFTs, and SFTs.

_**Classic NFTs**_ are the most straightforward in that you upload your images, they’re all visible right away, and people can browse through your collection and purchase what they like. Simply upload and sell!

_**Generated NFTs**_ add a little mystery into the mix. The buyer won’t know what their NFT looks like until they mint it. The owner of the collection has the ability to put in a placeholder image for the entire collection to give the buyer an idea of what the NFT may look like, but their mint will still be a surprise. This is the most common type of NFT (it’s what IOTABOTs did).

_**SFTs**_ (Semi-Fungible Tokens) are a hybrid between the two approaches above. The collection creator can create a classic NFT, but they have the option to multiply them. For example, they can upload 10 images, but each image will have a quantity of 100. This is a relatively new term in the space, but a good real world example of this approach would be baseball or football trading cards.

![](<../../.gitbook/assets/image (25) (1) (1) (1) (1) (1).png>)

By default, **all** initial sales and royalties will go to the space that created the collection, but the creator has the ability to point royalties to another space. This means that an artist can help a space raise funds via an NFT sale and receive a royalty on both the initial sale and all future secondary market sales for their work. This royalty percentage is fully customizable and under the control of the creator. No additional fees from the platform are involved, unlike other platforms like OpenSea which tax both the creator and buyers.

Another powerful feature we were able to include, since NFTs are fully integrated into the Soonaverse platform, is the ability to apply **discounts** for the members of your Space based on the amount of XP they’ve earned! _Rewarding engaged community members and potentially increasing your membership through promotional offers._

Finally, the last piece to the puzzle was integrating the **Firefly** and **TanglePay** wallets in order to validate addresses that will be receiving funds from NFT sales. There’s a new section in all spaces called “Your wallet” with a button to “Verify wallet.” Before a space can create a collection, they must have a validated space wallet. This validation process is fully automated and involves sending a small amount of IOTA to an address to verify that the space owner has control of the keys, and then that amount is automatically sent back. After that, the space is eligible to create NFT collections and receive royalties.

![](<../../.gitbook/assets/image (8) (1).png>)

_Please note that at this time, once an address is validated for a space, it cannot be changed. We did this for security reasons, so a rogue guardian can’t change the address without anyone knowing until it’s too late. We’ll introduce a feature in the future that enables guardians to vote on changing the validated address._

### NFT Marketplace

This is where things start to get interesting in the IOTA Community. We now have a place to create a market for our NFTs. There will be a page for Soonaverse members to browse all available NFTs within the platform. It will provide basic filtering options and ordering.

From the discover screen you’ll be able to click on any collection that you might be interested in and view specifics. There’s a section for the collection to write about their purpose and what makes their collection unique and special. After a little light reading, you can then click into each individual NFT.

![](<../../.gitbook/assets/image (29) (1) (1) (1).png>)

![](<../../.gitbook/assets/image (22) (1) (1) (1) (1).png>)

When you’re looking at the actual NFT, you’ll be able to see all of the system info (address, IPFS info), properties, and stats that the creator inputted. Additionally, you’ll be able to view a full timeline history with a link to a Tangle Explorer to see all of the transactions related to the NFT on chain.

If an NFT is listed for sale, then any member within the Soonaverse will be able to click the “Buy now” and purchase it for the specified price. If an NFT you really want isn’t listed for sale, then you have the option to make an offer. All offers will be held in a time locked escrow account (maximum 7 days) and can only be unlocked by the seller accepting/denying the offer or the time lock period ending.

**The best part about all of this is that all payments and offers are done over the Tangle using IOTA as the currency. Your IOTA will no longer need to remain idle after staking ends.**

Of course, what’s the point of buying NFTs if you can’t show them off? Once an NFT has been purchased, it will show up in the member’s profile:

![](<../../.gitbook/assets/image (28) (1) (1).png>)

Visitors viewing your profile will be able to purchase your NFTs if you’ve listed them for sale or they can put in offers for NFTs you haven’t listed for sale. Your Soonaverse profile now becomes an art gallery for the world to see. In a future release we may even implement a dedicated webpage or web3 component that you can embed on various platforms and sites. Similar to how you embed tweets from twitter into your profile or where your NFTs are shown on a wall or a background of your choosing.

### Mint

One of the most important parts of this entire system is our “**mint to mainnet**” function. What exactly does this mean? It means that any NFT on the Soonaverse will be able to use the platform’s mint feature to choose which network they want to migrate to. You can choose to either port over to Shimmer or the IOTA mainnet once the tokenization frameworks go live.

Now NFTs projects don’t need to worry about the technical complexity of migration. If they minted their collection on the Soonaverse we will have everything ready for them when the time comes.

This isn’t just limited to collections that were natively minted on the Soonaverse. This goes for all NFT projects that have already been minted. All a collection owner needs to do is migrate their project to the Soonaverse before the mainnets go live with tokenization. After their collection is available on the Soonaverse, they will be able to leverage the Soonaverse mint feature and take all of the worry about migrating to either IOTA or Shimmer.
