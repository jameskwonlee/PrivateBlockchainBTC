# private_blockchain
A template for a private blockchain bearing unique data, using Bitcoin Core

updated: 08/26/2019

Designed by James Kwon Lee

Tools used: 
JavaScript, Express, Bitcoin Core

Description:
User can input his or her Bitcoin address to make a submission of a name and a message into the Bitcoin network blockchain. 
The message is encoded via hex to ascii when stored into the blockchain, but can be later decoded to view. 

Security features:
The user has 5-minutes upon signing his/her wallet to submit a block with the desired name and message. After 5-minutes, the wallet signature will be rendered invalid. 
