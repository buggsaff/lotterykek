# Lottery
### Luck plays a big role!

`Working` <br>
This project involves two individuals, the leader and participants [may be greater than or equal to three]. A magical lottery function will select the winner from among the participants once each participant enters a certain amount of ether, which in this case I have set to 1 ether. and will be in possession of all the ethers that the leader had obtained from participants. The remaining participants will have my sympathies. Try again!

`Details` <br>
- I used the keccak256() method with abi.encodePacked and certain parameters like difficulty, timestamp, and participant count to randomly select the winner.
- Keep in mind that none of the participants have the authority to check the balance; only the Leader will have that ability.
- Deployed on Rinkeby Testnet  [View on block explorer](https://rinkeby.etherscan.io/tx/0x892563fe52ee760da4ae38140522d9ec8bfbeddba3f0df51fd9a98b27771cc4e)
- Tested with 3 participants named monka1, monka2, monka3(Winner) haha!
[click here to stalk monka3](https://rinkeby.etherscan.io/tx/0xc964bfc0da77e83fa3cd4b47a01cb5d0815fc2ce8166f3457b2f3d0ff3730cb8)
