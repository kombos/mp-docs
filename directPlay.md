---
layout: page
title: DirectPlay
permalink: /directplay
nav_order: 3
---
# DirectPlay

As part of the decentralized nature of this App, this game can be played without even visiting the website/ DApp site. One can directly send a certain amount of crypto directly from one’s Ethereum wallet (eg. MyEtherWallet, MyCrypto, Blockchain.info wallet etc.) to the contract address (0xblahblah) with gas limit set as 123456 and the smart contract will automatically purchase tokens for the player and auto-confirm his/her participation. The amount of crypo to send has to be exactly the total value of token(s) to purchase. The token value chart for the four default gameBoards is shown in the table below. 

|    Tokens to Buy    |    Token Value for BountyBox (Game ID: 102)   in Ethers    |    Tokens to Buy    |    Token Value for TokenArmy (Game ID: 103)   in Ethers    |    Tokens to Buy    |    Token Value for WhaleTank (Game ID: 105)   in Ethers    |
|---------------------|------------------------------------------------------------|---------------------|------------------------------------------------------------|---------------------|------------------------------------------------------------|
|    1                |    0.01                                                    |    1                |    0.055                                                   |    1                |    1                                                       |
|    2                |    0.02                                                    |    2                |    0.11                                                    |                     |                                                            |
|    3                |    0.03                                                    |    3                |    0.165                                                   |                     |                                                            |
|    4                |    0.04                                                    |    4                |    0.22                                                    |                     |                                                            |
|    5                |    0.05                                                    |    5                |    0.275                                                   |                     |                                                            |
|    6                |    0.06                                                    |    6                |    0.33                                                    |                     |                                                            |
|    7                |    0.07                                                    |    7                |    0.385                                                   |                     |                                                            |
|    8                |    0.08                                                    |    8                |    0.44                                                    |                     |                                                            |
|    9                |    0.09                                                    |    9                |    0.495                                                   |                     |                                                            |
|    10               |    0.1                                                     |    10               |    0.55                                                    |                     |                                                            |
|                     |                                                            |    11               |    0.605                                                   |                     |                                                            |
|                     |                                                            |    12               |    0.66                                                    |                     |                                                            |
|                     |                                                            |    13               |    0.715                                                   |                     |                                                            |
|                     |                                                            |    14               |    0.77                                                    |                     |                                                            |
|                     |                                                            |    15               |    0.825                                                   |                     |                                                            |
|                     |                                                            |    16               |    0.88                                                    |                     |                                                            |
|                     |                                                            |    17               |    0.935                                                   |                     |                                                            |
|                     |                                                            |    18               |    0.99                                                    |                     |                                                            |
|                     |                                                            |    19               |    1.045                                                   |                     |                                                            |
|                     |                                                            |    20               |    1.1                                                     |                     |                                                            |
|                     |                                                            |    21               |    1.155                                                   |                     |                                                            |
|                     |                                                            |    22               |    1.21                                                    |                     |                                                            |
|                     |                                                            |    23               |    1.265                                                   |                     |                                                            |
|                     |                                                            |    24               |    1.32                                                    |                     |                                                            |
|                     |                                                            |    25               |    1.375                                                   |                     |                                                            |
|                     |                                                            |    26               |    1.43                                                    |                     |                                                            |
|                     |                                                            |    27               |    1.485                                                   |                     |                                                            |
|                     |                                                            |    28               |    1.54                                                    |                     |                                                            |
|                     |                                                            |    29               |    1.595                                                   |                     |                                                            |
|                     |                                                            |    30               |    1.65                                                    |                     |                                                            |

## Examples of DirectPlay Purchases

*	If you want to purchase 2 tokens of Game Board called Bounty Box whose game ID is 102, the token value is 0.01 ether per token, and the total amount to send will be 0.02 ethers (0.01 * 2). Then you set the following parameters in your Ethereum wallet and send the ether amount: 

| Transaction   Parameter | Parameter Value                              |
|-------------------------|----------------------------------------------|
| From:                   | < Your Wallet Address >                        |
| To:                     | 0xA9655E83C54716c242650441F9AebCd8358cff7c                                   |
| Exact amount to send:   | 0.02 ethers                                  |
| Gas Limit:              | 123456                                       |
| Gas Price:              | 5GWei to 20GWei (depending on your priority) |

*	If you want to purchase 27 tokens of Game Board called Token Army whose game ID is 103, the token value is 0.055 ether per token, and the total amount to send will be 1.486 ethers (0.055 * 27). Then you set the following parameters in your Ethereum wallet and send the ether amount:

| Transaction   Parameter | Parameter Value                              |
|-------------------------|----------------------------------------------|
| From:                   | < Your Wallet Address >                        |
| To:                     | 0xA9655E83C54716c242650441F9AebCd8358cff7c                                   |
| Exact amount to send:   | 1.486 ethers                                  |
| Gas Limit:              | 123456                                       |
| Gas Price:              | 5GWei to 20GWei (depending on your priority) |

*	If you want to purchase 1 token of Game Board called Whale Tank whose game ID is 105, the token value is 1.0 ether per token, and the total amount to send will be 1 ethers (1.0 * 1). Then you set the following parameters in your Ethereum wallet and send the ether amount: 

| Transaction   Parameter | Parameter Value                              |
|-------------------------|----------------------------------------------|
| From:                   | < Your Wallet Address >                        |
| To:                     | 0xA9655E83C54716c242650441F9AebCd8358cff7c                                   |
| Exact amount to send:   | 1 ether                                      |
| Gas Limit:              | 123456                                       |
| Gas Price:              | 5GWei to 20GWei (depending on your priority) |

Please note that Gas Limit mentioned (123456) may not be fully consumed and hence, the remaining gas will be automatically refunded to players. Also, any invalid ether value sent is refunded back to the player automatically, along with remaining gas. 



---
[Play Multiprizer](https://ropsten.multiprizer.io)
