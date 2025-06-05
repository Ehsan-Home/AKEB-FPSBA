# AKEB
This is a dApp (decentralized app) based on blockchain for first-price, privacy-preserving, sealed-bid auction, in which reduces the cost by 50%, comparing to other privacy-preserving solutions. 

## Explanation
The transparent, decentralized, and immutable properties of public blockchains make them  appealing for applications that could benefit from these properties, including e-auctions. However, the usage of blockchains for such applications is hindered by concerns related to privacy and performance. We introduce a hybrid solution for e-auctions, leveraging the advantages of both centralized processing and the immutable registration offered by a public blockchain. In this approach, bids are processed by the auctioneer, while the masked bids are recorded on the blockchain. Consequently, the identity of the winner and their bid value is publicly accessible, while the remaining bid values remain confidential, known only to the bidder and the auctioneer and verifiable against the public results of the auction. These bids remain sealed unless the bidder chooses to disclose them during a dispute event. In this paper, we explain the proposed solution and present empirical analysis of its performance drawing on the outcomes of our preliminary experiments. We elaborate achieving promised privacy while showing **50\%** improvement over blockchain-based verifiable sealed-bid auction involving fewer than 15 bidders.

**Note:** The organization containing all of the source code is available at: [Link](https://github.com/AKEB-asyemmtric-key-each-bidder)

## Tech Stack
- Front-end: React, JavaScript, Ant-design, NPM, Create-react-app
- Back-end: Django, RESTful API, Python
- Blockchain: Ethereum, Solidity
- Version Control: Git - GitHub
- Deployment: Docker
- Testing:
    - Blockchain: Truffle
    - Front-end: Mocha

 ## Results
 - Preserving bidders privacy.
 - 50% cost reduction

## Logo
[Blockchain icons created by Parzival’ 1997 - Flaticon](https://www.flaticon.com/free-icons/blockchain)

**Note:** All rights reserved. This project may not be reproduced in whole or in part, by photocopy or other means, without the permission of the author

## Links:
- [Source code](https://github.com/AKEB-asyemmtric-key-each-bidder)
- [Technical report](https://dspace.library.uvic.ca/handle/1828/14292)

@ Ehsan Ghasaei, 2023, University of Victoria (UVIC)


