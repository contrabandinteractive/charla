# Charla

## Inspiration

The goal of Charla is to take what Twitter started, and leverage the power of blockchain to ensure that everyone has a voice and cannot be silenced. Charla is a proof-of-concept intended to show how a social media platform can exist on the CoinEx Smart Chain. The end result is social media where users truly own their thoughts, opinions, and ideas - all with the benefit of avoiding bots, bad actors, and censorship.

It is currently deployed to the Testnet. 

## What it does

This initial proof-of-concept allows a user to connect to the dApp with a MetaMask wallet. For demo purposes, it's important that the user's MetaMask be configured to work with the CSC Testnet.

To interact with Charla, you must have a wallet funded with tCET. These tokens provide the fuel to this SocialFi experience.

Once connected, the user can write a **"Cha"** which can be thought of as similar to a Tweet, but living on the blockchain. Each interaction requires the user to pay a small fee to verify authenticity and contribute to the network. The user can also delete his or her **Cha** in exchange for paying a small fee as well. This demo allows anyone to write a **Cha** that will then be displayed on the homepage feed.

Charla appears similar to Twitter, but with key differences:

- You own your thoughts and ideas. Every **Cha** that you write is your possession that lives forever on the blockchain.
- Because each **Cha** requires a small fee to post, this removes the incentive for bots and spam account to exist.
- The service cannot be shutdown by a central authority; it is essentially a decentralized improvement upon Twitter.


## How we built it

Charla's frontend is built using React. I also used Hardhat to test, compile and deploy the smart contract necessary to run Charla.

## Challenges we ran into

The most challenging part of this was coming up with a solid idea that I believed in, and what I would think that the judges would appreciate and believe in as well. I spent careful consideration on formulating an idea that I believe will have major impact and contribute to the network. It was also my first time writing a litepaper, so that took some serious time and dedication as well.

## Accomplishments that we're proud of

I feel that I have accomplished developing an app that builds upon traditional social networking features (such as posting a "tweet" or status update), and offers a way for a user to actually "own" their content. Charla is different than Twitter in that the end user owns their content and ideas and cannot be shut down by a central authority.

## What we learned

I learned a lot about the benefits of using CoinEx Smart Chain - which includes faster and cheaper transactions. I really liked that I could use my experience working with Ethereum tools and Solidity and easily put it to work while building on CSC.

## What's next for Charla

I'd like to expand on this proof-of-concept and make all the features you see listed on the left sidebar work, such as user messaging, profiles, lists, etc. There's still much to be done, but I felt that the work here demonstrated the core feature which is providing a way to create posts and interact with the smart contract that powers the dApp.

## Smart contract

The "charla server" folder holds files necessary to deploy the smart contract.

## Client folder

The "charla client" folder is a React frontend that can be used to interact with the smart contract.
