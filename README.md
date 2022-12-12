Sharevenue is a library/API used to process Solana wallets (or transactions) and determine what fees were paid for the acquisition of an NFT to both creators (royalties) and marketplace.

The API was developed as part of the 2022 Creator Monetization Hackathon, Future Of Royalties by Magic Eden.

Using Vistier, developers and communities:

have a means of identifying holders that respected royalties, thus allowing for a reward structure
have a tool of tracking paid royalties
The API is easily incorporated in any system and does not require any storage mechanism when deployed loically. It relies solely on processing transactions and, with enough committed resources, can be surprisingly fast.

A high level presentation of the project is available here: Solana Vistier API

This project/repository has several components.

libvistier: API for querying royalty, TX and wallet information
flask server: a server integrating Vistier API
docker image: a simple docker image on the above flask server, image can be found here
discord bot: a POC discord bot for highlight one beneficial use case of Vistier API. More on this here
Currently, the API supports Magic Eden transactions, however it is easily extendable to other markets.

