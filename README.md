# MEMEX.EXCHANGE CONTRACTS
ERC20.sol indicates the Token Contract.
Total Supply of 10,000,000 MEMEX tokens created
1,000,000 MEMEX tokens to be transferred to team wallet - See line 221. (indicating team wallet address)

Memex.sol indicates the Crowdsale Contract
This will be used for the Crowdsale (private sale and Presale)
20% of tokens purchased will initially be released to the buyer(10% sent dirrectly+10% claimable right away), with a vesting period - 10% unlock each month. 
This can be called from the function from the private sale contract.
You may view each functions of the contracts once deployed under write contract.

The crowdsale contract is timelocked. 
This means that the crowdsale will open at the time indicated by the owner and closed by the time indicated by the owner.
The Crowdsale contract includes and is exclusive for those who participated in the whitelist for each crowdsale (private and presale)
ONLY whitelisted addresses will be able to participate in the sales theyve applied for respectively.
Any purchases made by other adresses not on the whitelists will automatically be denied and rejected and the smart contract will transfer the amount purchased back to the one who transferred.
Memex is not responsible for gas fees lost due to the above. 

Purchases can only be made when the private sale contract is open and when closed no buyer will be able to purchase.
if a buyer purchases before the opening time or after the closing time, the contract will reject such transfer and the balance transferred will be sent back to the person who transferred. 
Memex is not responsible for gas fees lost due to the above. 

Once the crowdsale begins, the tokens designated by MEMEX for each sale will be transferred from the delpoyer to the crowdsale contract at the time of the sale. 
Once the Amount designated at sale of MEMEX is sold, any other balances will be rejected. 
Memex is not responsible for gas fees lost due to the above. 

Once the MEMEX tokens designated at each sale is sold out, the sale will be closed. 
MEMEX tokens will be transferred upon listing. Only 20% will be released followed by vesting period at a monthly rate of 10% unlock each month.
This applies to Private Sale buyers
This also applies to pre-sale buyers
This also applies to Team tokens respectively. 

End.
