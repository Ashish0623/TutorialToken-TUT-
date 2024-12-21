## Project Title
**TutorialToken (TUT)**

## Project Description
TutorialToken is a custom Ethereum-based ERC-20 token designed to reward content creators for sharing high-quality tutorials. It aims to incentivize knowledge sharing and support the growing community of learners and educators within the blockchain ecosystem.

## Contract Address
0xF044d6482ce4d30955825fb4734f789f644e7369

## Project Vision
Our vision is to create a decentralized ecosystem where content creators are rewarded for their contributions to the community. By using blockchain technology, TutorialToken provides a transparent, immutable, and fair system for distributing rewards and supporting educators in sharing valuable knowledge.

## Key Features

1. **ERC-20 Compliance**
   - Fully compliant with the ERC-20 standard, ensuring compatibility with Ethereum wallets and decentralized applications (DApps).

2. **Reward Mechanism**
   - Allows the contract owner to reward content creators for sharing tutorials. Rewards are tracked with events for transparency.

3. **Ownership Control**
   - Only the owner of the contract can distribute rewards, ensuring a controlled and fair reward process.

4. **Basic Token Operations**
   - Supports common token functionalities such as:
     - Transfer of tokens between users.
     - Approve and transfer tokens on behalf of others.

5. **Event Logging**
   - Logs significant actions, including transfers, approvals, and rewards, for easy tracking and auditing.

## Deployment
To deploy this contract, provide an initial token supply as a constructor argument. Once deployed, the deploying address becomes the owner, holding the total supply of tokens.

## Usage
### Token Transfers
- Use the `transfer` function to send tokens to another address.
- Use the `approve` and `transferFrom` functions to allow spending on behalf of another user.

### Rewarding Creators
- The owner can reward content creators by calling the `rewardCreator` function, specifying the creator's address, a tutorial URL, and the reward amount.

---



