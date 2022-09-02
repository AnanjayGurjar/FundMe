# FundMe
A basic etherium based Smart contract which is capable to receive public funding.
The contract is capable of: 
* Receive funds from any address
* Store the address and amount funded of the donaters
* Set a minimum usd amount which need to be donated and revert the call if condiion is not fulfilled
* Withdraw the funds to the account of the contract owner
* Handling the condition when contract is sent eth without calling the funding function
