# Generated

Generated NFTs add a little mystery into the mix. The buyer won’t know what their NFT looks like until they mint it. The owner of the collection has the ability to put in a placeholder image for the entire collection to give the buyer an idea of what the NFT may look like, but their mint will still be a surprise. This is the most common type of NFT.

#### **Here's an in-depth tutorial on how to add multiple NFTs to a Generated Collection:**

On the "Create NFT" screen, you'll want to click the "Multiple" tab. This is where you can add multiple NFTs:

![](<../../.gitbook/assets/image (25) (1).png>)

The first thing you need to do is upload all of your NFTs. You can do this by dragging and dropping the files into in the "Upload multiple images" box or you can click on the "Upload multiple images" box and select the files in your file explorer.

Once you've successfully uploaded your files (this can take several minutes depending on how many and how large your files are), click the "Generate CSV" button:

![](<../../.gitbook/assets/image (31) (1).png>)

After you generate and download the CSV, open it in your preferred viewer. For this tutorial I'll be using Microsoft Excel. You'll notice when you open up the spreadsheet that the file names aren't in any type of order. Feel free to sort them how you please before inputting data. It won't affect anything when you go to reupload.

![](<../../.gitbook/assets/image (35) (1).png>)

Fill in all of the cells applicable to you:

_Special notes:_

1. _**You don't need to worry about randomization. The platform will automatically take care of it.**_
2. _The generated CSV automatically defaults to 5 properties and 5 stats, but you can add more by inserting new columns and using the same verbiage (i.e. “prop.label6, prop.value6)._
3. _Use ISO 8601 standard for the date field (_[_https://en.wikipedia.org/wiki/ISO\_8601_](https://en.wikipedia.org/wiki/ISO\_8601)_)_
   * _For example, for April 10th, 2022 at 5:30am UTC, you'd use:_ 2022-04-10T05:30:00Z
4. Do not change any column header names in the spreadsheet. They need to be as provided in the CSV example you exported.

![](<../../.gitbook/assets/image (22).png>)

After you've added all your information, save the CSV to your computer, and upload it:

![](<../../.gitbook/assets/image (28) (1).png>)

For the next step we recommend you click the eye icon next to a few of your NFTs to spot check how the upload went. Check the image, properties, stats, etc.

Once you're comfortable with what's been uploaded, you can click the "Publish NFTs" button and sign the MetaMask transaction:

![](<../../.gitbook/assets/image (24).png>)

After you've created all your NFTs, all you need to do is click the "Publish Collection" button (**Check out how only one NFT with your placeholder image and a "Buy now" button is visible. Every time someone clicks the "Buy now" button, a random NFT from your collection will be selected and sold to them**):

![](<../../.gitbook/assets/image (26) (1).png>)

_Please note that there's currently a 1 day waiting period from publishing the collection to the availability date of the collection. This is a safeguard to allow the community time to evaluate the project before it goes live. Additionally, it gives the system time to upload everything to IPFS._
