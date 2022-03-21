# Creating an NFT Collection

An artist should be able to focus all their energy into their art. They shouldn’t have to worry about the intricacies of setting up their own NFT launchpad. With the new NFT Builder, artists no longer need to worry about things like IPFS, creating their own smart contracts, setting up a dedicated website, etc. We simplify the entire process, plus you have the added benefit of your work being available within the Soonaverse and the 10,000+ and growing Soonaverse community waiting to engage with your artwork.

**Available file types for NFTs:** jpg, jpeg, png, webp, and mp4. The limit for each file is 100 MB.



{% embed url="https://www.youtube.com/watch?t=1s&v=nbhIDBWOKOU" %}
A brief walkthrough of how to create an NFT collection
{% endembed %}



#### **Here's an in-depth tutorial on how to create an NFT collection on the Soonaverse:**

The NFT Builder will initially allow artists to choose and upload three different types of NFT collections: Classic NFTs, Generated NFTs, and SFTs.

![](<../../.gitbook/assets/image (27) (1) (1) (1).png>)

_**Classic NFTs**_ are the most straightforward in that you upload your images, they’re all visible right away, and people can browse through your collection and purchase what they like. Simply upload and sell!

_**Generated NFTs**_ add a little mystery into the mix. The buyer won’t know what their NFT looks like until they mint it. The owner of the collection has the ability to put in a placeholder image for the entire collection to give the buyer an idea of what the NFT may look like, but their mint will still be a surprise. This is the most common type of NFT (it’s what IOTABOTs did).

_**SFTs**_ (Semi-Fungible Tokens) are a hybrid between the two approaches above. The collection creator can upload multiple of the same images. Each image doesn't need to be unique in an SFT collection. For example, they can upload 10 unique images, but each image will have a quantity of 100. This is a relatively new term in the space, but a good real world example of this approach would be baseball or football trading cards.



NFTs in the Soonaverse are grouped into collections. The collection controls some overall settings, and within that collection, you'll load NFTs:

![](<../../.gitbook/assets/image (25) (1) (1).png>)

The first step to creating an NFT collection on the Soonaverse is to create a profile and a space. You can do that by following the instructions in the SPACE OWNERS - GETTING STARTED section of this documentation:

![](<../../.gitbook/assets/image (16) (1).png>)

Once you have your space created, you can verify the IOTA Wallet for your space (follow these instructions, except instead of your profile, click the "Verify wallet" button in your space): [Verifying your IOTA Wallet](../../all-users-getting-started/verifying-your-iota-wallet.md)

After you've verified your IOTA wallet, you'll need to participate in the "Create a Collection Badge" award in the SoonLabs space (this is our current solution for spam protection until the SOON token is launched): [https://soonaverse.com/award/0x3ccb9fe9d6f429981522fb1927a2259149a4a192/overview](https://soonaverse.com/award/0x3ccb9fe9d6f429981522fb1927a2259149a4a192/overview)

![](<../../.gitbook/assets/image (6).png>)

Once you've done that you'll see that there's now a button in your space that allows you to create NFT collections. All you need to do to add a new collection to your space is to click the "+ New Collection" button:

![](<../../.gitbook/assets/image (29) (1) (1) (1).png>)

On the "Create new collection" page, you'll need to fill out the following fields:

* _**Name**_ - This is title of your collection that will show up on the main pages.
* _**Description**_ - A description of your collection (supports markdown language)
* _**Collection Type**_ - Please refer to the 3 types of collections that were mentioned above and choose the one most applicable to you.
* _**Price**_ - For Generated and SFT collection types, this will be the price of every NFT in your collection. If you choose a Classic collection type then this price will be the default, but you can manually change the price of each NFT in your collection.
* _**Date**_ - This will be date and time that your sale goes live (it is automatically in your local time).
* _**Royalties - Percentage fee**_ - The royalty % that will be applied on the initial mint of the NFTs and all secondary sales. _Please note that the IOTA address receiving royalties must always have a minimum balance of 1 Mi due to the dust protection mechanism of the IOTA protocol._
* _**Royalties goes to a different space**_ - By default, **all** initial sales and royalties will go to the space that created the collection, but the creator has the ability to point royalties to another space. If you had an artist complete work for you and you'd like the royalties to go to their space, then check this box and choose their space. In the instance of a 5% royalty fee. 95% of all sales would go to the space that created the collection while 5% would go to the artist's space. _Please note that the artist must verify the IOTA wallet in their space before they'll show up in the dropdown list._
* _**Banner**_ - Upload a banner photo (‪dimensions are 2,350 x 1,080).
* _**Placeholder**_ - When you choose "GENERATED" or "SFT" for Collection type, you get a new section that pops up called “Placeholder”. You can upload an image, GIF(webp), or video(mp4) as a placeholder image since you will only have one singular "Buy now" box once your sale goes live. _Please note that for video(mp4), the user will need to press the play button._
* _**Category**_ - A specific type of category can be chosen (Collectible, PFP, Photography, Animation, 3D, etc.)
* _**Links**_ - A place for you to link your website, Twitter handle, and Discord account.
* _**Collection Setup**_ - Choose who has access to buy your collection.
  * _Open Sale_ - Everyone has access to purchase NFTs in the collection.
  * _Space Guardians Only_ - Only guardians of your space have access to purchase NFTs in the collection.
  * _Space Members Only_ - Only members of your space have access to purchase NFTs in the collection.
  * _Space Members with Badge Only_ - Only members of your space with a specific badge from participating in one of your awards have access to purchase NFTs in the collection.
  * _At least one NFT from Collections_ - Only people who hold at least one NFT from each of the selected collections cam purchase NFTs in the collection.
* _**Collection Options**_ - Click the "One NFT per Member Only" button if you want to limit each member to only purchasing one NFT. THIS IS GREAT FOR AIRDROPS. If you choose the "At least one NFT from Collections" option in the Collection Setup section, then you'd choose the specific collections here.
  * _One main caveat here: We currently don’t automatically show the NFT collections that the purchaser needs, so it’s important for you, the collection creator, to add these details in your description!_
  * _Also, please note that a member would need to own an NFT for EACH collection that you select, not just a single collection._
* _**Member discounts**_ - Here you can apply discounts on the purchase price of your NFTs. Use XP > -1 if you don't require members purchasing to have any XP from your space (I would recommend click the "One NFT per Member Only" button if you go this route, so one member doesn't mint every NFT. Please note, 1Mi will always be required to purchase the NFT due to the IOTA protocol's dust protection mechanism.

![](<../../.gitbook/assets/image (29) (1).png>)

_Check out the example image above: You'll see that all members who own an NFT in both the "Awesome DAO stuff" and "Soonabots Collection" collections (even if they aren't members of your space) will be able to mint one of these NFTs for free (1 Mi). This is basically an airdrop to everybody who holds those collections._

Once you've completed all the fields, you click the "Create collection" button at the bottom, sign the transaction in MetaMask, and then the collection is created. After that you can begin creating your NFTs by clicking the "+ Create NFT" button:

![](<../../.gitbook/assets/image (32) (1).png>)

To see how each individual collection type is uploaded, check out the following pages:

* [Classic](classic/)
* [Generated](generated.md)
* [SFT](sft.md)
