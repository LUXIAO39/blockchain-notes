# blockchain-notes
我的 Web3 学习笔记：DeFi、公链、合约分析
# Web3 学习笔记

## DeFi 协议分析

### Uniswap V3 核心机制
- **集中流动性**：LP 可以在自定义价格区间内提供流动性
- **多级费率**：0.01%、0.05%、0.3%、1% 四档
- **NFT 仓位**：每个 LP 仓位是独立的 ERC-721

### Lido 与流动性质押
- 解决传统 ETH 质押「资金锁仓」的问题
- 质押 ETH → 获得 stETH（可交易、可再质押）
- 核心风险：stETH 脱锚风险

## 公链生态对比
| 公链 | 共识机制 | TVL | 特点 |
|------|---------|-----|------|
| Solana | PoH + PoS | 高 | 高性能、低延迟 |
| Sui | Narwhal & Tusk | 增长快 | 对象模型、Move 语言 |
| Base | OP Stack | Coinbase 生态 | 低费用、大量用户 |
