---
description: A step-by-step tutorial on how to stake LP tokens to generate rewards
---

# Liquidity Mining

There are four main steps that need to be completed in order to participate in the SOON token liquidity mining incentives. These are:

1. Bridge SOON tokens from the Shimmer L1 to the Shimmer EVM
2. Bridge an equal dollar value of either wBTC or ETH from Ethereum Mainnet or IOTA from the IOTA Mainnet to the Shimmer EVM
3. Use SOON tokens and one of the other three tokens to provide liquidity on Iotabee and receive LP tokens
4. Stake those LP tokens to receive additional SOON token rewards



:warning: **Bridging IOTA to the Shimmer EVM is not currently available** :warning:

:warning: **Only wBTC and ETH from the Ethereum Mainnet will be active on launch day** :warning:



### Step 1: Bridge SOON tokens

Before you can do anything on the Shimmer EVM, you need to make sure you have enough SMR on the chain to pay gas costs. For this tutorial we'll be bridging over 10 SMR, but since the gas costs are so low on the Shimmer EVM, this is probably overkill.

To do this, log into Firefly and go to send a token:

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

* For the amount, input 10 SMR.
* Destination network: ShimmerEVM
* Recipient: Input the EVM address that you want to use on the Shimmer EVM (starts with 0x)
* Click "Next" and then process the transaction.

If you go into your MetaMask wallet, you can see the 10 SMR:

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

Now that you have SMR on the Shimmer EVM chain, you can now bridge your SOON tokens from the Shimmer L1 to the Shimmer EVM chain.

To do this we'll be using the IOTAMPC bridge on Iotabee: [https://iotabee.com/bridge](https://iotabee.com/bridge)

Here's what the bridging transaction should look like:

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

* From: Choose SOON Shimmer Mainnet and enter the amount of SOON tokens you'd like to bridge to the Shimmer EVM
* To: Choose sSOON ShimmerEVM Mainnet and the amount of SOON tokens that will be bridged over will auto-populate
* Target wallet: Input the EVM address that you want to use on the Shimmer EVM (starts with 0x and in most cases will be the same as the address you entered for bridging over SMR)
* Click the "Bridge" button

Just like that you now have both SMR and sSOON tokens on the Shimmer EVM.

### Step 2: Bridge wBTC, ETH, or IOTA tokens

Now you need to bridge over either wBTC or ETH from the Ethereum Mainnet (IOTA tutorial will be available once the capability is active).

For this tutorial I will be bridging over wBTC.

Assuming you already own wBTC on the Ethereum Mainnet, all you need to do is visit the IOTAMPC bridge page again: [https://iotabee.com/bridge](https://iotabee.com/bridge)

The difference this time is that you'll need to change your MetaMask network from the Shimmer EVM to the Ethereum Mainnet:

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

Go back to the bridge page. This is what your bridging transaction should look like:

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

* From: Choose WBTC Ethereum Mainnet and enter the amount of wBTC tokens you'd like to bridge to the Shimmer EVM
* To: Choose sBTC ShimmerEVM Mainnet and the amount of wBTC tokens that will be bridged over will auto-populate
* Target wallet: Input the EVM address that you want to use on the Shimmer EVM (starts with 0x and in most cases will be the same as the address you entered for bridging over SMR)
* Click the "Bridge" button

You now have some wBTC tokens on the Shimmer EVM chain.

### Step 3: Create LP tokens

Before staking, you must first add liquidity. Go to: [https://iotabee.com/farm](https://iotabee.com/farm), make sure your wallet's network is set to the Shimmer EVM, and scroll down until you find the pool that you'd like to provide liquidity for.

Click the "Add liquidity" button:

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

Type in the amount of sBTC you'd like to provide for liquidity and the amount of sSOON you need will auto-populate:

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

After you click the "Add" button and confirm all your transaction in your wallet you'll officially have LP tokens that you can stake.

### Step 4: Stake LP tokens

Go back to the farming page, find your token pair, and click the "Stake" button:

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

All of your LP tokens will auto-populate in the LP Token section. All you need to do is choose how long you'd like to lock up your LP tokens (longer lock means higher rewards) and click the "Stake" button:

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

Congratulations! You now have your LP tokens staked and are eligible for the SOON token liquidity mining rewards!
