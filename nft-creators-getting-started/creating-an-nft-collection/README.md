# Creating an NFT Collection

An artist should be able to focus all their energy into their art. They shouldn’t have to worry about the intricacies of setting up their own NFT launchpad. With the new NFT Builder, artists no longer need to worry about things like IPFS, creating their own smart contracts, setting up a dedicated website, etc. We simplify the entire process, plus you have the added benefit of your work being available within the Soonaverse and the 10,000+ and growing Soonaverse community waiting to engage with your artwork.

The NFT Builder will initially allow artists to choose and upload three different types of NFT collections: Classic NFTs, Generated NFTs, and SFTs.

_**Classic NFTs**_ are the most straightforward in that you upload your images, they’re all visible right away, and people can browse through your collection and purchase what they like. Simply upload and sell!

_**Generated NFTs**_ add a little mystery into the mix. The buyer won’t know what their NFT looks like until they mint it. The owner of the collection has the ability to put in a placeholder image for the entire collection to give the buyer an idea of what the NFT may look like, but their mint will still be a surprise. This is the most common type of NFT (it’s what IOTABOTs did).

_**SFTs**_ (Semi-Fungible Tokens) are a hybrid between the two approaches above. The collection creator can create a classic NFT, but they have the option to multiply them. For example, they can upload 10 images, but each image will have a quantity of 100. This is a relatively new term in the space, but a good real world example of this approach would be baseball or football trading cards.

![](<../../.gitbook/assets/image (10).png>)

By default, **all** initial sales and royalties will go to the space that created the collection, plus the creator has the ability to point royalties to another space. This means that an artist can help a space raise funds via an NFT sale and receive a royalty on both the initial sale and all future secondary market sales for their work. This royalty percentage is fully customizable and under the control of the creator. No additional fees from the platform are involved, unlike other platforms like OpenSea which tax both the creator and buyers.

Another powerful feature we were able to include, since NFTs are fully integrated into the Soonaverse platform, is the ability to apply **discounts** for the members of your Space based on the amount of XP they’ve earned! _Rewarding engaged community members and potentially increasing your membership through promotional offers._

Finally, the last piece to the puzzle was integrating the **Firefly** and **TanglePay** wallets in order to validate addresses that will be receiving funds from NFT sales. There’s a new section in all spaces called “Your wallet” with a button to “Verify wallet.” Before a space can create a collection, they must have a validated space wallet. This validation process is fully automated and involves sending a small amount of IOTA to an address to verify that the space owner has control of the keys, and then that amount is automatically sent back. After that, the space is eligible to create NFT collections and receive royalties.

![](<../../.gitbook/assets/image (22).png>)

_Please note that at this time, once an address is validated for a space, it cannot be changed. We did this for security reasons, so a rogue guardian can’t change the address without anyone knowing until it’s too late. We’ll introduce a feature in the future that enables guardians to vote on changing the validated address._
