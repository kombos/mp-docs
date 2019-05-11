---
layout: page
title: DirectPlay
permalink: /directplay
nav_order: 3
---
# DirectPlay

_**Note:** The below examples are illustrated for Ethereum Blockchain. The same equivalent mechanism can be used for other blockchains also. Also, DirectPlay is an option that is enabled by the admin, hence if DirectPlay transactions are reverting, that would be because it has been disabled by admin._

As part of the decentralized nature of this App, this game can be played without even visiting the website/ DApp site. One can directly send a certain amount of crypto directly from one’s Ethereum wallet (eg. MyEtherWallet, MyCrypto, Blockchain.info wallet etc.) to the contract address, with gas limit set as **123456**, and Gas Price between **3Gwei to 20GWei**, and the smart contract will automatically purchase tokens for the player and auto-confirm his/her participation. The **Multiprizer** Contracts are deployed in the following addresses:  

`Ethereum Mainnet: 0x4E0C7a80dBf4aCdD6F020c3dD796Ef5b97D26Ed0`

`Ethereum Ropsten (testnet): 0x44cd9Cf21c589ac9D92a18782771485aF02250F9`


The amount of ethers to send as total token value has to be exactly the total value of token(s) to purchase. The token value chart for three default gameBoards is shown in the table below. 

|    Tokens to Buy    |    Total Value in Ethers for BountyBox (GameID: 102)    |    Tokens to Buy    |    Total Value in Ethers for TokenArmy (GameID: 103)    |    Tokens to Buy    |    Total Value in Ethers for WhaleTank (GameID: 105)    |
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

## Examples of DirectPlay Purchases (Ethereum Mainnet)

*	If you want to purchase 2 tokens of Game Board called Bounty Box whose game ID is 102, the token value is 0.01 ether per token, and the total amount to send will be 0.02 ethers (0.01 * 2). Then you set the following parameters in your Ethereum wallet and send the ether amount: 

| Transaction   Parameter | Parameter Value                              |
|-------------------------|----------------------------------------------|
| From:                   | < Your Wallet Address >                        |
| To:                     | 0x4E0C7a80dBf4aCdD6F020c3dD796Ef5b97D26Ed0                                   |
| Exact amount to send:   | 0.02 ethers                                  |
| Gas Limit:              | 123456                                       |
| Gas Price:              | 3Gwei to 20GWei (depending on your priority) |

*	If you want to purchase 27 tokens of Game Board called Token Army whose game ID is 103, the token value is 0.055 ether per token, and the total amount to send will be 1.485 ethers (0.055 * 27). Then you set the following parameters in your Ethereum wallet and send the ether amount:

| Transaction   Parameter | Parameter Value                              |
|-------------------------|----------------------------------------------|
| From:                   | < Your Wallet Address >                        |
| To:                     | 0x4E0C7a80dBf4aCdD6F020c3dD796Ef5b97D26Ed0                                   |
| Exact amount to send:   | 1.486 ethers                                  |
| Gas Limit:              | 123456                                       |
| Gas Price:              | 3Gwei to 20GWei (depending on your priority) |

*	If you want to purchase 1 token of Game Board called Whale Tank whose game ID is 105, the token value is 1.0 ether per token, and the total amount to send will be 1 ether (1.0 * 1). Then you set the following parameters in your Ethereum wallet and send the ether amount: 

| Transaction   Parameter | Parameter Value                              |
|-------------------------|----------------------------------------------|
| From:                   | < Your Wallet Address >                        |
| To:                     | 0x4E0C7a80dBf4aCdD6F020c3dD796Ef5b97D26Ed0                                   |
| Exact amount to send:   | 1 ether                                      |
| Gas Limit:              | 123456                                       |
| Gas Price:              | 3Gwei to 20GWei (depending on your priority) |

Please note that Gas Limit mentioned (123456) may not be fully consumed and hence, the remaining gas will be automatically refunded to players. Also, any invalid ether value sent is refunded back to the player automatically, along with remaining gas. 

## Withdraw Winnings using DirectPlay

You can even withdraw your winnings using DirectPlay. This, firstly, requires a scenario where your winnings have not been automatically transferred to your Ethereum address due to some hypothetical and improbable circumstance. Hence, in case your winning amount (if any) is pending in the withdraw records of the contract, this can be withdrawn by sending a small token value **(0.00023456 eth OR 234560000000000 wei)** to the Multiprizer Contract Address. The Gas Limit has to be set as **65432**, or an amount greater than that. The Gas Price can be any value **between 3Gwei and 20GWei**, as per your priority of transaction. Thus, you set the following parameters in your Ethereum wallet and send the ether amount:

| Transaction   Parameter | Parameter Value                              |
|-------------------------|----------------------------------------------|
| From:                   | < Your Wallet Address >                        |
| To:                     | 0x4E0C7a80dBf4aCdD6F020c3dD796Ef5b97D26Ed0                                   |
| Exact amount to send:   | 0.00023456 ether                                      |
| Gas Limit:              | 65432                                        |
| Gas Price:              | 3Gwei to 20GWei (depending on your priority) |


Please note that DirectPlay is not applicable for reverting tokens and hence for that, you will have to visit the game site. Also, if you don’t have any pending amounts in the withdraw record, the transaction will be reverted and the remaining gas refunded after consuming certain gas to check the records. Hence only use the DirectPlay Withdraw feature if you are sure there is pending winning amount that you need to claim. In case there is pending winning amount to withdraw, sending this transaction will automatically initiate transfer of amount (pending withdraw amount plus the amount you sent in the DirectPlay transfer, i.e 0.00023456) from the Multiprizer Contract to your account. Also, the transaction may take less than 65432 gas, in which case, the remaining gas will be refunded back to you. 

---
[Play Multiprizer](https://multiprizer.io)
