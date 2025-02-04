---
id: torusUserGuide
title: Using the Torus Wallet
slug: dapps/torusUserGuide
---
import useBaseUrl from '@docusaurus/useBaseUrl'
import styles from '../src/css/custom.css'

The Torus Wallet is a great option for new-comers to crypto. Using web3 technology it allows you to create an Ethereum Wallet that's linked to your identity via your chosen social media platform. With the Torus Wallet you can send and receive cryptocurrencies, and  buy crypto with fiat currency using Torus' 'wallet top-up' option.


### Sign-In
Using the Giveth.io Application, it's very easy to get started. On the homepage click `sign-in` and you will be a given a choice of which platform you want to use to confirm your identity (i.e. email, twitter, discord, facebook, etc.). After choosing your platform, approve the 'Permission' pop-up and that's it! Torus  automatically generates an Ethereum Wallet Address for you which you can view by selecting the `My Wallet` option from the drop down menu in the top right of the Giveth.io homepage.

<img alt="Finding your Torus Wallet" src={useBaseUrl('img/content/givethio/myWalletTorus.png')} />


You can access your Torus wallet direcly from the [Torus website](https://app.tor.us/) by signing in using the same social media that you used on Giveth.io. From the Torus page, you'll see lots of important information, including your wallet balance, your Ethereum address and other useful settings.

*If you aren't sure what an Ethereum Wallet or Ethereum Address is, this is a good time to take 10 minutes and **learn about some basic fundamentals relating to Ethereum** and cryptocurrency in general. We recommend reading the some of the great ethereum.org documentation, particularily on [Wallets](https://ethereum.org/en/wallets/) and [What is Ethereum](https://ethereum.org/en/what-is-ethereum/).*

### Managing Your Wallet

From the [Torus page](https://app.tor.us/) you can check your wallet balance across a wide range of different Ethereum networks. You can also see your public address and copy it to your clipboard in the top right area of the page.

<img alt="Torus Account Homepage" src={useBaseUrl('img/content/givethio/torusAccountpage.png')} />

Presently, Giveth projects can receive donations either on xDai network or Mainnet. By default, Torus will show you your Mainnet wallet balance. If you received donations on xDai you can check your balance by going to `Settings` and  selecting `xDai Network` from the `Network` drop down menu. If you naviagte back to `Home`, you should see your xDai wallet balance.

#### Finding your Tokens
If you received a donation to your project but it doesn't show up in your Torus Wallet, you likely have to specify which token Torus should look for. This is done by adding the Token Address. Check your project's donations page on Giveth.io to see in which token(s) you've received donations.

<img alt="Checking your Project Donations" src={useBaseUrl('img/content/givethio/projectDonations.png')} />

You can look up the token on several different crypto analytics sites, [CoinGecko](https://www.coingecko.com/en) or [CoinMarketCap](https://coinmarketcap.com/) are reputable sites. Search for your token by its name or ticker symbol, then copy the 'Contract Address' from the token's information page. Here is an example for UNI:


<!-- <img alt="CoinGecko Contract Address" src={useBaseUrl('img/content/givethio/tokenAddresscoingecko.png')} /> -->



Paste the string of characters into the 'Add Token' pop-up window from your Torus Account. Clicking `Next` should auto-fill the rest of the information. Your token should now show up and you can view and manage it from you wallet, just like Ethereum.

<img alt="Adding Tokens in Torus" height="500" class="leftfloat" width="auto" src={useBaseUrl('img/content/givethio/addTokenTorus.png')} />



#### More Functions
If you want to buy crypto using fiat currency, you can do so using the `Top Up` option. We have written a small guide to help you out with the fiat on-ramping process **(link doc internally).**

To send crypto you own to another wallet use `Transfer`. You will need Ethereum(ETH) in your wallet to be able to 'pay the gas' necessary for your transaction. More on gas [here](https://ethereum.org/en/developers/docs/gas/).

### Other Wallets
As mentioned, Torus Wallet is great for beginners. Using familiar social media platforms for managing your identity is a great way to get started. However, if you decide to get serious about crypto there is a vast array of other wallets out there. Some wallets are easier to integrate with other chains, offer more privacy or allow for more advanced interactions. Some wallets exist as web3 extensions like Torus, others are a physical device, like a hardware wallet, that you need to connect to your computer to access and manage your crypto. If you decide to go wallet shopping you can find a list of the most popular ones [here](https://ethereum.org/en/wallets/find-wallet/).
