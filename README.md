# Smart Contract Lottery

Players

- Lottery starts by accepting ETH transactions from any wallet.
- This will only allow you to send a fixed amount of 0.1 ETH
- If players send ETH directly to the contract address they will be registerd in the lottery
- A player can send more transaction to increase there likelyhood of winning

Manager

- There is a manager, this is the account that deploys and controls the contract
- If there are at least 3 players, the manager can pick a random winner
- Only the manager can see th contract balanace and randomly select the winner

End Game

- The contract will transfer the entire balance to the winners address 
- Game will finally reset for the next round
