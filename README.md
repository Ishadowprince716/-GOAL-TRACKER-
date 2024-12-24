# Tokenized Goal Tracker DApp 🎯

A decentralized application that helps users set, track, and achieve their goals while earning tokens as rewards. Built with Solidity and Web3 technology.

## Vision 🚀

The Tokenized Goal Tracker aims to revolutionize personal development by combining goal-setting with blockchain technology. Our vision is to create a transparent, incentivized system where:

- Users are motivated to achieve their goals through token rewards
- Goal completion is verified and immutably recorded on the blockchain
- Community engagement drives accountability and success
- Token rewards create tangible value for personal achievement

## Features ✨

### Current Implementation
- Create personalized goals with descriptions and deadlines
- Set custom token rewards for each goal
- Track goal progress in real-time
- Mark goals as completed
- Verification system through contract owner
- ERC20 token (GTT) integration for rewards
- User-friendly web interface
- MetaMask wallet integration

### Smart Contract Details
- **Contract Address**: 0xE346d0b8a6aB5cefc596905e62d8D72bAcC20B12
- **Network**: Edu-Chain
- **Token Symbol**: GTT (Goal Tracker Token)
- **Initial Supply**: 1,000,000 GTT

## Technical Stack 🛠

### Backend
- Solidity ^0.8.0
- OpenZeppelin Contracts
  - ERC20
  - Ownable

### Frontend
- HTML5
- CSS3
- JavaScript
- Web3.js
- MetaMask Integration

## Future Scope 🔮

### Phase 1: Enhanced Goal Management
- [ ] Goal categories and tags
- [ ] Goal templates for common objectives
- [ ] Milestone tracking within goals
- [ ] Progress visualization and analytics
- [ ] Goal sharing and social features

### Phase 2: Community Features
- [ ] Public goal feed
- [ ] User profiles and achievement badges
- [ ] Goal mentorship system
- [ ] Community verification mechanism
- [ ] Social interaction features (comments, likes, support)

### Phase 3: Token Utility Expansion
- [ ] Token staking for goal commitment
- [ ] Achievement NFTs
- [ ] Marketplace for goal-related services
- [ ] Token governance system
- [ ] Integration with other DeFi protocols

### Phase 4: Advanced Features
- [ ] AI-powered goal recommendations
- [ ] Automated goal verification systems
- [ ] Mobile application
- [ ] Cross-chain integration
- [ ] Real-world reward partnerships

## Installation & Setup 🔧

1. Clone the repository
```bash
git clone [repository-url]
```

2. Install dependencies
```bash
npm install
```

3. Configure environment variables
```bash
cp .env.example .env
# Edit .env with your configuration
```

4. Deploy the smart contract
```bash
npx hardhat run scripts/deploy.js --network [your-network]
```

5. Update contract address in frontend
```javascript
const contractAddress = "YOUR_DEPLOYED_CONTRACT_ADDRESS";
```

6. Launch the frontend
```bash
npm start
```

## Usage 📝

1. Connect your MetaMask wallet
2. Create a new goal with description, deadline, and reward
3. Track your progress through the dashboard
4. Mark goals as completed when achieved
5. Receive GTT tokens upon goal verification
