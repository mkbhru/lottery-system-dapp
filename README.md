Manager - who manages the lottery system 
participants - >= 3, they buy the lottery tickets using the smart contract
lottery only activates if total participants >= 3

- participants must have a wallet
- a participant can transfer ether more than one time but the transferred ether must be two ether
- As the participant will transfer the ether its address will be registered
- manager will have full control over the lottery.

- The contract will be reset once a round is completed.

It is just collecting ethers for a lottery from three(or more accounts) at the 
contract address and then selecting a random account as a winner and sending
all contract ethers to that account address.

1. I have created 4 accounts for manager and three participants respectively
   ![image](https://github.com/mkbhru/lottery-system-dapp/assets/74449664/0e0147d9-bfef-4b45-8003-b5283957d757)

2. Manager deploys the contract to the sepoliaEth testnet
   ![image](https://github.com/mkbhru/lottery-system-dapp/assets/74449664/99ef4759-e619-498c-a1da-c2ad342d0699)

3. After participants have done there txns. manager will execute the selectWinner() which will automatically transfer all contract ethers to a random participant.
