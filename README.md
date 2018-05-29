# tiny-blockchain-in-JavaScript
This project a starter of Implementing a basic blockchain, Implementing proof-of-work, Transactions &amp; mining rewards

<img src="https://www.draglet.com/wp-content/uploads/2017/02/Private-Blockchain-1.png">

## Blockchain Structure

Blockchains are built through a combination of linked lists and merkle trees. The linked list structure allows for the chain to continually build on top of itself and is where the name blockchain derives from. A blockchain is literally a chain of blocks linked to one another through the linked list structure. One thing to note however, is that instead of holding a traditional pointer to refer to the previous block, it uses the hash of the previous block to refer to it.
