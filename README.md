# 📚 8-Week Intensive Solidity Bootcamp - From Zero to Advanced
### Using RareSkills Free Resources

> **Duration**: 8 Weeks  
> **Time Commitment**: 20-25 hours/week  
> **Cost**: FREE  
> **Outcome**: Production-ready Solidity developer

## 📋 Table of Contents
- [Week 1: Foundations & Environment Setup](#week-1-foundations--environment-setup)
- [Week 2: Data Structures & Token Standards](#week-2-data-structures--token-standards)
- [Week 3: Advanced Solidity & DeFi Primitives](#week-3-advanced-solidity--defi-primitives)
- [Week 4: Uniswap V2 & Protocol Architecture](#week-4-uniswap-v2--protocol-architecture)
- [Week 5: Proxy Patterns & Upgradability](#week-5-proxy-patterns--upgradability)
- [Week 6: Advanced DeFi - Compound V3](#week-6-advanced-defi---compound-v3)
- [Week 7: Security, Gas Optimization & Testing](#week-7-security-gas-optimization--testing)
- [Week 8: Advanced Topics & Final Projects](#week-8-advanced-topics--final-projects)

---

## 🚀 Pre-Bootcamp Setup

### Required Tools Installation
1. **Node.js & npm**: [Download here](https://nodejs.org/)
2. **Git**: [Download here](https://git-scm.com/downloads)
3. **VS Code**: [Download here](https://code.visualstudio.com/)
4. **VS Code Solidity Extension**: [Install](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity)

### Foundry Installation
```bash
curl -L https://foundry.paradigm.xyz | bash
foundryup
```

### Clone Exercise Repository
```bash
git clone https://github.com/RareSkills/Solidity-Exercises.git
cd Solidity-Exercises
forge install
```

---

## 📅 Week 1: Foundations & Environment Setup
**Goal**: Master Solidity basics and development environment  
**Time**: 20-25 hours

### Day 1-2: Development Environment & Basic Types

#### 📖 Study Materials
1. [Development Environment Setup](https://rareskills.io/learn-solidity/remix-solidity)
2. [Fixed Size Datatypes](https://rareskills.io/learn-solidity/solidity-types)
3. [Foundry Setup](https://rareskills.io/learn-solidity/foundry-environment)
4. [Arithmetic Operations](https://rareskills.io/learn-solidity/arithmetic)

#### 💻 Assignments
- [ ] Complete [Add Exercise](https://github.com/RareSkills/Solidity-Exercises/tree/main/Add)
- [ ] Complete [Divide Exercise](https://github.com/RareSkills/Solidity-Exercises/tree/main/Divide)
- [ ] Complete [SumArray Exercise](https://github.com/RareSkills/Solidity-Exercises/tree/main/SumArray)

### Day 3-4: Control Flow & Functions

#### 📖 Study Materials
1. [If Statements](https://rareskills.io/learn-solidity/if-statements)
2. [For Loops](https://rareskills.io/learn-solidity/for-loops)
3. [Arrays Introduction](https://rareskills.io/learn-solidity/arrays)
4. [Nested Arrays](https://rareskills.io/learn-solidity/nested-arrays)

#### 💻 Assignments
- [ ] Complete [IsSorted Exercise](https://github.com/RareSkills/Solidity-Exercises/tree/main/IsSorted)
- [ ] Complete [BasicBank Exercise](https://github.com/RareSkills/Solidity-Exercises/tree/main/BasicBank)
- [ ] Complete [FizzBuzz Exercise](https://github.com/RareSkills/Solidity-Exercises/tree/main/FizzBuzz)

### Day 5-7: Storage & Mappings

#### 📖 Study Materials
1. [Storage Variables](https://rareskills.io/learn-solidity/storage-variables)
2. [Arrays in Storage](https://rareskills.io/learn-solidity/arrays-in-storage)
3. [Mappings](https://rareskills.io/learn-solidity/mapping)
4. [Nested Mappings](https://rareskills.io/learn-solidity/nested-mapping)

#### 💻 Assignments
- [ ] Complete [Fibonacci Exercise](https://github.com/RareSkills/Solidity-Exercises/tree/main/Fibonacci)
- [ ] Complete [FilterOddNumbers Exercise](https://github.com/RareSkills/Solidity-Exercises/tree/main/FilterOddNumbers)
- [ ] Complete [Mean Exercise](https://github.com/RareSkills/Solidity-Exercises/tree/main/Mean)

#### 🎯 Week 1 Project
Build a simple voting contract with:
- Proposal creation
- Vote tracking using mappings
- Winner determination

---

## 📅 Week 2: Data Structures & Token Standards
**Goal**: Master core Solidity patterns and build tokens  
**Time**: 20-25 hours

### Day 1-3: Core Concepts & ERC20

#### 📖 Study Materials
1. [msg.sender and address(this)](https://rareskills.io/learn-solidity/msg-sender-address-this)
2. [Constructor](https://rareskills.io/learn-solidity/constructor)
3. [Require Statements](https://rareskills.io/learn-solidity/require)
4. [ERC-20 Tokens](https://rareskills.io/learn-solidity/erc20-tutorial)

#### 💻 Assignments
- [ ] Complete [WhoCalledMe Exercise](https://github.com/RareSkills/Solidity-Exercises/tree/main/WhoCalledMe)
- [ ] Complete [CrossContract Exercise](https://github.com/RareSkills/Solidity-Exercises/tree/main/CrossContract)
- [ ] Build ERC20 token from scratch (no OpenZeppelin)

### Day 4-5: Advanced Data & Contract Interaction

#### 📖 Study Materials
1. [Tuples](https://rareskills.io/learn-solidity/tuples)
2. [ABI Encoding](https://rareskills.io/learn-solidity/abi)
3. [Contracts Calling Contracts](https://rareskills.io/learn-solidity/cross-contract-call)
4. [Token Exchange Project](https://rareskills.io/learn-solidity/mini-project)

#### 💻 Assignments
- [ ] Complete Token Exchange Mini Project
- [ ] Complete [TicTacToe Exercise](https://github.com/RareSkills/Solidity-Exercises/tree/main/TicTacToe)

### Day 6-7: Ethereum Specifics & Events

#### 📖 Study Materials
1. [Payable Functions](https://rareskills.io/learn-solidity/payable-functions)
2. [Receive Function](https://rareskills.io/learn-solidity/receive)
3. [Block.timestamp and block.number](https://rareskills.io/learn-solidity/block-timestamp-block-number)
4. [Emitting Events](https://rareskills.io/learn-solidity/events)
5. [Events Deep Dive](https://rareskills.io/post/ethereum-events)

#### 💻 Assignments
- [ ] Complete [TimelockEscrow Exercise](https://github.com/RareSkills/Solidity-Exercises/tree/main/TimelockEscrow)
- [ ] Complete [OneWeekLockup Exercise](https://github.com/RareSkills/Solidity-Exercises/tree/main/OneWeekLockup)

#### 🎯 Week 2 Project
Build a multi-signature wallet with:
- Multiple owner management
- Transaction proposals
- Event logging
- Time-locked withdrawals

---

## 📅 Week 3: Advanced Solidity & DeFi Primitives
**Goal**: Master inheritance, NFTs, and DeFi building blocks  
**Time**: 20-25 hours

### Day 1-2: Object-Oriented Solidity

#### 📖 Study Materials
1. [Inheritance](https://rareskills.io/learn-solidity/inheritance)
2. [Modifiers](https://rareskills.io/learn-solidity/modifiers)
3. [Immutable Variables](https://rareskills.io/learn-solidity/immutable-variables)
4. [Constants](https://rareskills.io/learn-solidity/constants)
5. [OpenZeppelin Ownable2Step](https://rareskills.io/post/openzeppelin-ownable2step)

#### 💻 Assignments
- [ ] Complete [Inheritance Exercise](https://github.com/RareSkills/Solidity-Exercises/tree/main/Inheritance)
- [ ] Implement access control patterns

### Day 3-4: NFTs & Advanced Tokens

#### 📖 Study Materials
1. [ERC-721 Tutorial](https://rareskills.io/learn-solidity/erc721-opensea)
2. [Deploy NFT with Foundry](https://rareskills.io/learn-solidity/deploy-nft-foundry)
3. [ERC-721 Security & Design](https://rareskills.io/post/erc721)
4. [ERC-721 Enumerable](https://rareskills.io/post/erc-721-enumerable)
5. [ERC-1155](https://rareskills.io/post/erc-1155)
6. [ERC-4626 Vault Standard](https://rareskills.io/post/erc4626)

#### 💻 Assignments
- [ ] Deploy NFT collection to testnet
- [ ] Build ERC-721 with enumeration
- [ ] Create ERC-1155 multi-token contract

### Day 5-7: DeFi Primitives

#### 📖 Study Materials
1. [Staking Algorithm (MasterChef/Synthetix)](https://rareskills.io/post/staking-algorithm)
2. [Fixed Point Arithmetic](https://rareskills.io/post/solidity-fixed-point)
3. [Flashloans (ERC-3156)](https://rareskills.io/post/erc-3156)
4. [Chainlink Price Feeds](https://rareskills.io/post/chainlink-price-feed-contract)
5. [DeFi Interest Rates](https://rareskills.io/post/aave-interest-rate-model)

#### 💻 Assignments
- [ ] Complete [ReducingPayout Exercise](https://github.com/RareSkills/Solidity-Exercises/tree/main/ReducingPayout)
- [ ] Build staking contract with rewards
- [ ] Implement flashloan receiver

#### 🎯 Week 3 Project
Build a simple lending protocol with:
- Deposit/withdraw functionality
- Interest calculation
- Collateralization ratio
- Basic liquidation

---

## 📅 Week 4: Uniswap V2 & Protocol Architecture
**Goal**: Deep understanding of AMM and DEX architecture  
**Time**: 20-25 hours

### Day 1-3: Uniswap V2 Core

#### 📖 Study Materials
1. [Uniswap V2 Architecture](https://rareskills.io/post/uniswap-v2-tutorial)
2. [Price Impact of Swap](https://rareskills.io/post/uniswap-v2-price-impact)
3. [Swap Function Explained](https://rareskills.io/post/uniswap-v2-swap-function)
4. [Mint and Burn Functions](https://rareskills.io/post/uniswap-v2-mint-and-burn)

#### 💻 Assignments
- [ ] Implement constant product formula
- [ ] Build liquidity pool contract
- [ ] Create swap functionality

### Day 4-5: Uniswap V2 Advanced

#### 📖 Study Materials
1. [Protocol MintFee](https://rareskills.io/post/uniswap-v2-mintfee)
2. [TWAP Oracle](https://rareskills.io/post/twap-uniswap-v2)
3. [UniswapV2 Library](https://rareskills.io/post/uniswap-v2-library)
4. [Routers](https://rareskills.io/post/uniswap-v2-router)

#### 💻 Assignments
- [ ] Implement price oracle
- [ ] Build router contract
- [ ] Add fee mechanism

### Day 6-7: Build Your Own DEX

#### 📖 Study Materials
1. [Building Uniswap V2 Clone](https://rareskills.io/post/build-your-own-uniswap)

#### 🎯 Week 4 Project
Complete Uniswap V2 clone with:
- Factory contract
- Pair contracts
- Router implementation
- LP token management
- Deploy to testnet

---

## 📅 Week 5: Proxy Patterns & Upgradability
**Goal**: Master smart contract upgradability patterns  
**Time**: 20-25 hours

### Day 1-3: Storage & Low-Level Calls

#### 📖 Study Materials
1. [EVM Storage Layout](https://rareskills.io/post/evm-solidity-storage-layout)
2. [Storage Slots Deep Dive](https://rareskills.io/post/evm-solidity-storage-layout)
3. [ABI Encoding Deep Dive](https://rareskills.io/post/abi-encoding)
4. [Low-Level Call vs High-Level Call](https://rareskills.io/post/low-level-call-solidity)
5. [Delegatecall Detailed Guide](https://rareskills.io/post/delegatecall)

#### 💻 Assignments
- [ ] Practice storage slot manipulation
- [ ] Implement delegatecall patterns
- [ ] Build minimal proxy

### Day 4-5: Proxy Standards

#### 📖 Study Materials
1. [ERC-1967 Standard](https://rareskills.io/post/erc1967)
2. [ERC-7201 Namespaced Storage](https://rareskills.io/post/erc-7201)
3. [Transparent Upgradeable Proxy](https://rareskills.io/post/transparent-upgradeable-proxy)
4. [Beacon Proxies](https://rareskills.io/post/beacon-proxy)

#### 💻 Assignments
- [ ] Implement transparent proxy
- [ ] Build beacon proxy system
- [ ] Practice storage collision prevention

### Day 6-7: Clone Patterns & Governance

#### 📖 Study Materials
1. [Clones (EIP-1167)](https://rareskills.io/post/eip-1167-minimal-proxy-standard-with-initialization-clone-pattern)
2. [Metaproxy Clones](https://rareskills.io/post/erc-3448-metaproxy-clone)
3. [ERC-20 Snapshots](https://rareskills.io/post/erc20-snapshot)
4. [ERC-20 Votes](https://rareskills.io/post/erc20-votes-erc5805-and-erc6372)
5. [Solidity Governance](https://rareskills.io/post/governance-contract-solidity)

#### 💻 Assignments
- [ ] Deploy clone factory
- [ ] Build voting token
- [ ] Create basic DAO

#### 🎯 Week 5 Project
Build upgradeable protocol with:
- Proxy pattern implementation
- Admin controls
- Storage management
- Governance voting

---

## 📅 Week 6: Advanced DeFi - Compound V3
**Goal**: Understand complex lending protocol architecture  
**Time**: 20-25 hours

### Day 1-3: Compound V3 Core

#### 📖 Study Materials
1. [Compound V3 Architecture](https://rareskills.io/post/compound-v3-contracts-tutorial)
2. [Interest Per Second](https://rareskills.io/post/compound-finance-interest-rate-model)
3. [Principal vs Present Value](https://rareskills.io/post/defi-interest-rate-indexes)

#### 💻 Assignments
- [ ] Implement interest rate model
- [ ] Build principal tracking system
- [ ] Create index-based accounting

### Day 4-5: Lending Mechanics

#### 📖 Study Materials
1. [cUSDC V3 (Comet)](https://rareskills.io/post/cusdc-v3-compound)
2. [Collateral & Liquidations](https://rareskills.io/post/compound-finance-liquidation)
3. [Compound V3 Rewards](https://rareskills.io/post/compound-v3-rewards)

#### 💻 Assignments
- [ ] Build collateral system
- [ ] Implement liquidation bot
- [ ] Create reward distribution

### Day 6-7: Advanced Features

#### 📖 Study Materials
1. [Bulkers in Compound V3](https://rareskills.io/post/compound-v3-bulker)
2. Review all Compound contracts

#### 🎯 Week 6 Project
Build lending protocol with:
- Multi-asset support
- Dynamic interest rates
- Liquidation mechanism
- Oracle integration

---

## 📅 Week 7: Security, Gas Optimization & Testing
**Goal**: Write secure and efficient smart contracts  
**Time**: 20-25 hours

### Day 1-2: Security Fundamentals

#### 📖 Study Materials
1. [Function Selector](https://rareskills.io/post/function-selector)
2. [Detecting Smart Contracts](https://rareskills.io/post/solidity-code-length)
3. [Where to Find Reentrancy](https://rareskills.io/post/where-to-find-solidity-reentrancy-attacks)
4. [Merkle Tree Second Preimage](https://rareskills.io/post/merkle-tree-second-preimage-attack)
5. [Random Number Generation](https://rareskills.io/post/generate-a-random-number-with-solidity-on-the-blockchain)

#### 💻 Assignments
- [ ] Complete [Solidity Riddles](https://github.com/RareSkills/solidity-riddles) (at least 10)
- [ ] Audit your previous projects
- [ ] Implement reentrancy guards

### Day 3-4: Gas Optimization

#### 📖 Study Materials
1. [Ultimate Gas Optimization Guide](https://rareskills.io/post/gas-optimization)
2. [EIP-2930 Access Lists](https://rareskills.io/post/eip-2930-optional-access-list-ethereum)
3. [Smart Contract Creation Cost](https://rareskills.io/post/smart-contract-creation-cost)
4. [EIP-150 63/64 Rule](https://rareskills.io/post/eip-150-and-the-63-64-rule-for-gas)
5. [Uint256 Max Value](https://rareskills.io/post/uint-max-value-solidity)
6. [Signed Integers](https://rareskills.io/post/signed-int-solidity)

#### 💻 Assignments
- [ ] Complete [Gas Puzzles](https://github.com/RareSkills/gas-puzzles)
- [ ] Optimize previous projects
- [ ] Benchmark gas costs

### Day 5-7: Testing Strategies

#### 📖 Study Materials
1. [Unit Testing](https://rareskills.io/learn-solidity/unit-testing)
2. [Testing Internal Functions](https://rareskills.io/post/solidity-test-internal-function)
3. [Invariant Testing](https://rareskills.io/post/invariant-testing-solidity)
4. [Mutation Testing](https://rareskills.io/post/solidity-mutation-testing)
5. [Try/Catch Patterns](https://rareskills.io/post/solidity-try-catch)

#### 💻 Assignments
- [ ] Write comprehensive test suites
- [ ] Implement invariant tests
- [ ] Practice fuzzing

#### 🎯 Week 7 Project
Security audit challenge:
- Audit provided vulnerable contracts
- Write exploit scripts
- Document findings
- Propose fixes

---

## 📅 Week 8: Advanced Topics & Final Projects
**Goal**: Master advanced concepts and build portfolio projects  
**Time**: 25-30 hours

### Day 1-3: Advanced Cryptography & Privacy

#### 📖 Study Materials
1. [How Tornado Cash Works](https://rareskills.io/post/how-does-tornado-cash-work)
2. [RSA Signatures in Solidity](https://rareskills.io/post/solidity-rsa-signatures-for-aidrops-and-presales-beating-ecdsa-and-merkle-trees-in-gas-efficiency)
3. [Precompiled Contracts](https://rareskills.io/post/solidity-precompiles)
4. [Smart Contract Metadata](https://rareskills.io/post/solidity-metadata)

#### 💻 Assignments
- [ ] Implement Merkle tree airdrop
- [ ] Build commit-reveal scheme
- [ ] Create privacy features

### Day 4-5: Additional Topics

#### 📖 Study Materials
1. [Professional Style Guide](https://rareskills.io/post/solidity-style-guide)
2. [Common Mistakes to Avoid](https://rareskills.io/post/solidity-beginner-mistakes)
3. [Strings in Solidity](https://rareskills.io/learn-solidity/strings)
4. [Structs](https://rareskills.io/learn-solidity/struct)
5. [Ethereum Units](https://rareskills.io/learn-solidity/ethereum-units)
6. [Staticcall EIP-214](https://rareskills.io/post/solidity-staticcall)
7. [Solidity gasleft()](https://rareskills.io/post/solidity-gasleft)
8. [ERC-1363](https://rareskills.io/post/erc-1363)
9. [Nodelegatecall](https://rareskills.io/post/nodelegatecall)

#### 💻 Assignments
- [ ] Complete remaining [Solidity Riddles](https://github.com/RareSkills/solidity-riddles)
- [ ] Optimize all previous projects

### Day 6-7: Final Portfolio Project

#### 🎯 Choose ONE Major Project:

**Option A: Full DeFi Protocol**
Build a production-ready DeFi protocol with:
- Lending/borrowing
- Liquidity provision
- Governance token
- Upgradability
- Full test coverage

**Option B: Advanced AMM**
Create advanced AMM with:
- Multiple pool types
- Dynamic fees
- Concentrated liquidity
- Oracle integration
- Analytics dashboard

**Option C: DAO Infrastructure**
Build complete DAO with:
- Treasury management
- Proposal system
- Delegation
- Time-locks
- Multi-sig integration

---

## 🛠️ Additional Resources

### GitHub Repositories
- [Main Tutorial](https://rareskills.io/learn-solidity)
- [Solidity Exercises](https://github.com/RareSkills/Solidity-Exercises)
- [Solidity Riddles](https://github.com/RareSkills/solidity-riddles)
- [Gas Puzzles](https://github.com/RareSkills/gas-puzzles)

### Tools & References
- [Remix IDE](https://remix.ethereum.org/)
- [Etherscan](https://etherscan.io/)
- [Tenderly](https://tenderly.co/)
- [Foundry Book](https://book.getfoundry.sh/)
- [Solidity Documentation](https://docs.soliditylang.org/)
- [OpenZeppelin Contracts](https://github.com/OpenZeppelin/openzeppelin-contracts)

### Practice Platforms
- [Ethernaut](https://ethernaut.openzeppelin.com/)
- [Damn Vulnerable DeFi](https://www.damnvulnerabledefi.xyz/)
- [Capture the Ether](https://capturetheether.com/)

### Communities
- [Ethereum StackExchange](https://ethereum.stackexchange.com/)
- [r/ethdev](https://www.reddit.com/r/ethdev/)
- [Ethereum Research](https://ethresear.ch/)

---

## 📊 Progress Tracking

Create a progress tracking system:

```markdown
## Week 1 Progress
- [ ] Day 1-2 Materials (____/4 articles)
- [ ] Day 1-2 Exercises (____/3 complete)
- [ ] Day 3-4 Materials (____/4 articles)
- [ ] Day 3-4 Exercises (____/3 complete)
- [ ] Day 5-7 Materials (____/4 articles)
- [ ] Day 5-7 Exercises (____/3 complete)
- [ ] Week 1 Project Complete
```

---

## 🎯 Success Metrics

By the end of 8 weeks, you should:
- ✅ Complete 50+ coding exercises
- ✅ Build 8+ projects
- ✅ Read 100+ technical articles
- ✅ Deploy 5+ contracts to testnet
- ✅ Have portfolio of 3-5 production-ready projects
- ✅ Understand gas optimization techniques
- ✅ Master security best practices
- ✅ Be ready for Solidity developer roles

---

## 💡 Study Tips

1. **Time Management**
   - Dedicate 3-4 hours daily
   - Weekend sessions for projects
   - Take breaks every 90 minutes

2. **Learning Strategy**
   - Read article → Code along → Exercise → Project
   - Document learnings in personal notes
   - Explain concepts to others (rubber duck debugging)

3. **Debugging Approach**
   - Use Foundry's debugging tools
   - console.log in Hardhat
   - Tenderly for transaction debugging

4. **Code Quality**
   - Follow Solidity style guide
   - Write tests for everything
   - Gas optimize after functionality works

5. **Portfolio Building**
   - Deploy all projects to testnet
   - Document with comprehensive READMEs
   - Include tests and deployment scripts

---

## 🚨 Important Notes

- **This is intensive**: 20-25 hours/week is demanding. Adjust if needed.
- **Quality over speed**: Better to understand deeply than rush through.
- **Practice daily**: Consistency is key in programming.
- **Join communities**: Don't learn in isolation.
- **Build in public**: Share your progress on social media.

---

## 📝 License

This curriculum aggregates free resources from [RareSkills](https://rareskills.io/). All credit for the content goes to the RareSkills team.

---

## 🤝 Contributing

Found a broken link or want to suggest improvements? Please create an issue or pull request!

---

**Last Updated**: November 2024  
**Maintained by**: Chidera

⭐ Star this repo if you found it helpful!
