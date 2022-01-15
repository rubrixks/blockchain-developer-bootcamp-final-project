#The Game

**Concept:**

Im sorry to whoever is reviewing this final project, for I have made you lose The Game.
If you do not know the rules, or if this is your first time hearing of this, here is the wikipedia link for reference.
https://en.wikipedia.org/wiki/The_Game_(mind_game)


This project is focusing on the meme'ers of the internet, but there is no intention of over promising.
The use case is simple. If anyone in the world thinks of The Game, instead of posting their L on reddit or twitter,
the individual can mint the Lost NFT for .0001 Ether.
Why blockchain technology? This is now the best way to record and announce to the world that someone has lost The Game for generations to come.
It would be difficult to search through social medias and other sites to determine how many people have lost. 
By having a decentralized immutable ledger, anyone in the world can see and count what addresses have lost The Game.

**Work Flow:**

	1.Users will visit the website and be first be shown a description of what The Game is, and why this was made. 
	2.The website will detect a wallet, and ask to connect the wallet to the website.
	3.If the user is the creator of the contract, they can begin the game and mint 10 Losses. If the user is not the creator, they can mint as many losses as they wish
	4.Either user must send the amount requested to mint the Losses onto their wallet.
	5.Users can then check how many people have lost The Game and how many losses their account has.

**Directory Structure:**

	Backend
        -build folder: contains json files of the The Game contract
        -contracts folder: contains the migrations and TheGame solidity files
        -migrations folder: contains the migrations files needed from js
        -test folder: contains the tests needed in a js file
        -truffle-config.js
	Frontend
        -dapp.js
        -index.html
	Text_Documentation
        -avoiding_common_attacks.md
        -deployed_address.txt
        -design_pattern_decisions.md
	.gitignore
	README.md

**Install Dependencies:**

	metamask: https://metamask.io/
	openzepplin: https://docs.openzeppelin.com/contracts/4.x/
	truffle suite: https://trufflesuite.com/docs/truffle/getting-started/installation

**Accessing Project:**


Locally:
To run this project locally make sure to install the dependencies mentioned above. Once installed clone this project onto your machine. 

1.Through the terminal use 'git clone https://github.com/rubrixks/blockchain-developer-bootcamp-final-project.git'


2.Open this file with your preferred text editor and populate your ENV and .gitignore file like so:

        Within .gitignore file:
        Type .env

        Within .env file:
        Type MNEMONIC = *insert mnemonic of your wallet here*;
        Type INFURA_URL = *insert the infura URL of your preferred testnet here*;


3.Once this step 2 is complete, run truffle develop within the terminal in your text editor to test the project. 


Alternative:

Visit this link to interact with the application on a google browser: https://rubrixks.github.io


**Run Unit Tests:**

To run unit test the user may clone the repository and interact with it with the truffle suite. Make sure to have installed all previous mentioned dependencies.

    1.Through the terminal use 'git clone https://github.com/rubrixks/blockchain-developer-bootcamp-final-project.git'
    1. Find your file within your machine and open this project in your text editor
    3.Within your text editor open your terminal and cd into blockchain-developer-bootcamp-final-project.
    4.Inside the terminal use this command 'cd Backend' to jump into the Backend folder.
    5.Once inside the Backend folder run 'truffle test'. All 6 tests should pass.


**Ethereum Address:**
rubrixks.eth

0x3058B13c47A5c6472181A82A4C1Ce7150D5f638F

**Screencast Link:**
Visit this link to view a demo of the application from the viewpoint of the creator of the application:
https://youtu.be/mnf5ryN5N_k

**For the Grader:**

Please leave any comments on how to improve this project. I would like to deploy this project onto mainnet through a L2 this year. Here is where I believe I need suggestions and comments:

1.How to increase Losses when transferring NFTs

 I would like to have the amount of Losses increase if an NFT is transfered to another wallet, but I was not sure how to add that functionality.

2.Price for NFT

 I am debating if this NFT should be free or charge a small amount( <.0001 ETH). The reason for charging is I can imagine a scenario where someone will try to mint an absurd amount of NFTs bc the limit is so large to make everyone lose The Game. 

 3.Add an Events when minting or transfering Losses

 I did not know how to distinguish a loss from an NFT being minted and if someone were to transfer their nft to a friend.

Any comments will be of great help. Thank you!

