# Blockchain & Crypto Model Context Protocol Servers

This repository highlights Model Context Protocol (MCP) servers specifically designed for interacting with **blockchain technologies, cryptocurrencies, and Web3 ecosystems**. These servers leverage the [Model Context Protocol](https://modelcontextprotocol.io/) (MCP) to provide Large Language Models (LLMs) with secure, controlled access to on-chain data, transaction capabilities, smart contract interactions, and other crypto-specific tools.

The servers listed demonstrate how MCP can bridge the gap between LLMs and the decentralized world, enabling powerful new applications in areas like DeFi analysis, NFT management, on-chain automation, and crypto data retrieval. Each MCP server is implemented with either the [Typescript MCP SDK](https://github.com/modelcontextprotocol/typescript-sdk) or [Python MCP SDK](https://github.com/modelcontextprotocol/python-sdk).

> Note: Lists in this README are maintained in alphabetical order.

## 🤝 Third-Party Servers

### 🎖️ Official Integrations

Official integrations are maintained by companies building production-ready MCP servers for their platforms, focusing on blockchain and crypto functionalities.

- <img height="12" width="12" src="https://www.bankless.com/favicon.ico" alt="Bankless Logo" /> **[Bankless Onchain](https://github.com/bankless/onchain-mcp)** - Query Onchain data, like ERC20 tokens, transaction history, smart contract state.
- <img height="12" width="12" src="https://bicscan.io/favicon.png" alt="BICScan Logo" /> **[BICScan](https://github.com/ahnlabio/bicscan-mcp)** - Risk score / asset holdings of EVM blockchain address (EOA, CA, ENS) and even domain names.
- <img height="12" width="12" src="https://neo4j.com/favicon.ico" alt="Neo4j Logo" /> **[Neo4j](https://github.com/neo4j-contrib/mcp-neo4j/)** - Neo4j graph database server (schema + read/write-cypher) and separate graph database backed memory (often used for blockchain analysis).
- <img height="12" width="12" src="https://thirdweb.com/favicon.ico" alt="Thirdweb Logo" /> **[Thirdweb](https://github.com/thirdweb-dev/ai/tree/main/python/thirdweb-mcp)** - Read/write to over 2k blockchains, enabling data querying, contract analysis/deployment, and transaction execution, powered by [Thirdweb](https://thirdweb.com/)

### 🌎 Community Servers

A growing set of community-developed servers demonstrating various applications of MCP within the crypto and blockchain space.

> **Note:** Community servers are **untested** and should be used at **your own risk**. They are not affiliated with or endorsed by Anthropic.

- **[Algorand](https://github.com/GoPlausible/algorand-mcp)** - A comprehensive MCP server for tooling interactions (40+) and resource accessibility (60+) plus many useful prompts for interacting with the Algorand blockchain.
- **[Base Free USDC Transfer](https://github.com/magnetai/mcp-free-usdc-transfer)** - Send USDC on [Base](https://base.org) for free using Claude AI! Built with [Coinbase CDP](https://docs.cdp.coinbase.com/mpc-wallet/docs/welcome)'s MPC wallet tech.
- **[Bsc-mcp](https://github.com/TermiX-official/bsc-mcp)** The first MCP server that serves as the bridge between AI and BNB Chain, enabling AI agents to execute complex on-chain operations through seamless integration with the BNB Chain, including transfer, swap, launch, security check on any token and even more.
- **[coin_api_mcp](https://github.com/longmans/coin_api_mcp)** - Provides access to [coinmarketcap](https://coinmarketcap.com/) cryptocurrency data.
- **[crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp)**  -  Providing real-time and historical Crypto Fear & Greed Index data.
- **[cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server)** - Providing latest cryptocurrency news to AI agents, powered by CryptoPanic.
- **[Dappier](https://github.com/DappierAI/dappier-mcp)** - Connect LLMs to real-time, rights-cleared, proprietary data from trusted sources. Access specialized models for Real-Time Web Search, News, Sports, Financial Data, Crypto, and premium publisher content. Explore data models at [marketplace.dappier.com](https://marketplace.dappier.com/marketplace).
- <img height="12" width="12" src="https://www.dexpaprika.com/favicon.ico" alt="DexPaprika Logo" /> **[DexPaprika](https://github.com/dexpaprika/mcp-server-dexpaprika)** - Access real-time data for over 5 million tokens across 20+ blockchain networks including Solana, Base, BSC, and Ethereum. Get token prices, liquidity pool information, historical data and DEX analytics ([Docs](https://docs.dexpaprika.com)).
- **[dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp)** -  A mcp server that bridges Dune Analytics data to AI agents.
- **[Ergo Blockchain MCP](https://github.com/marctheshark3/ergo-mcp)** -An MCP server to integrate Ergo Blockchain Node and Explorer APIs for checking address balances, analyzing transactions, viewing transaction history, performing forensic analysis of addresses, searching for tokens, and monitoring network status.
- **[EVM MCP Server](https://github.com/mcpdotdirect/evm-mcp-server)** - Comprehensive blockchain services for 30+ EVM networks, supporting native tokens, ERC20, NFTs, smart contracts, transactions, and ENS resolution.
- **[GOAT](https://github.com/goat-sdk/goat/tree/main/typescript/examples/by-framework/model-context-protocol)** - Run more than +200 onchain actions on any blockchain including Ethereum, Solana and Base.
- **[Heurist Mesh Agent](https://github.com/heurist-network/heurist-mesh-mcp-server)** - Access specialized web3 AI agents for blockchain analysis, smart contract security, token metrics, and blockchain interactions through the [Heurist Mesh network](https://github.com/heurist-network/heurist-agent-framework/tree/main/mesh).
- **[Hyperliquid](https://github.com/mektigboy/server-hyperliquid)** - An MCP server implementation that integrates the Hyperliquid SDK for exchange data.
- **[Neo4j](https://github.com/da-okazaki/mcp-neo4j-server)** - A community built server that interacts with Neo4j Graph Database (often used for blockchain analysis).
- **[Solana Agent Kit](https://github.com/sendaifun/solana-agent-kit/tree/main/examples/agent-kit-mcp-server)** - This MCP server enables LLMs to interact with the Solana blockchain with help of Solana Agent Kit by SendAI, allowing for 40+ protocol actions and growing.
- **[whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp)**  -  A mcp server for tracking cryptocurrency whale transactions.

## 📚 Resources

Additional resources focused on MCP within the crypto ecosystem.

- **[Awesome Crypto MCP Servers by badkk](https://github.com/badkk/awesome-crypto-mcp-servers)** - A curated list of MCP servers focused on crypto applications by **[Luke Fan](https://github.com/badkk)**

## 🚀 Getting Started

### Using an MCP Client
Running a server on its own isn't very useful. It should be configured into an MCP client (like Claude Desktop, or custom applications).

For example, a hypothetical Claude Desktop configuration to use the EVM server might look like:

```json
{
  "mcpServers": {
    "evm": {
      "command": "npx",
      "args": ["-y", "@mcpdotdirect/server-evm", "--rpc-url", "https://mainnet.infura.io/v3/YOUR_INFURA_ID"]
    }
  }
}
```
*(Note: Refer to the specific server's documentation for correct installation and configuration commands)*

## 🛠️ Creating Your Own Server

Interested in creating your own MCP server for a specific blockchain, dApp, or crypto tool? Visit the official documentation at [modelcontextprotocol.io](https://modelcontextprotocol.io/introduction) for comprehensive guides, best practices, and technical details.

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for information about contributing to this repository, especially if you have built or found new blockchain/crypto-related MCP servers.

## 🔒 Security

See [SECURITY.md](SECURITY.md) for reporting security vulnerabilities. Remember that interacting with blockchains and smart contracts carries inherent risks; ensure any MCP server you use has appropriate security measures and understand the permissions you grant it.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💬 Community

- [GitHub Discussions](https://github.com/orgs/modelcontextprotocol/discussions) (General MCP)

## ⭐ Support

If you find MCP servers useful for blockchain and crypto applications, please consider starring the repository and contributing new servers or improvements!
