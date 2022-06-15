# TokenSaleContract

there is two main functions buyTokens() & airdrop()

## buyToken()
it takes the address which the tokens will send to, the referral address if there any if not it takes the null address.

the ethers are send from the buyers to the wallet you specify at the time of deploy, make sure the wallet have enough tokens & The tokens is approved for the contracts to sell it.

if there a referral address it will take a percentage of the ether & Tokens You specify it by a function called setRefRate() it takes three parameters the ether percentage , the token percentage & the percentage Dominator.

the referral must have tokens in his wallet to take the ethers & tokens


## airdrop()
it takes the address which the tokens will send to, the referral address if there any if not it takes the null address.

the airdrop Process just once.

you can change the state of any address to take the airdrop again, like if you want the members to share the project via social media and what else.

there is airdrop fees worthed 0.005 Ether you can change it

if there a referral address it will take a percentage of the fees & Tokens You specify it by a function called setRefRate() it takes three parameters the ether percentage , the token percentage & the percentage Dominator.

the referral must have tokens in his wallet to take the ethers & tokens.
