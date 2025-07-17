# Seiva Bot

**Seiva is your personal on-chain assistant for the Sei Network, accessible directly through Telegram.**  
It helps you track wallet activity, explore projects, and ask anything about the Sei ecosystem—right from your chat.

## Features

- **Sei Q&A**: Ask anything about Sei using `/ask` or by sending questions directly.
- **Wallet Checker**: Send an EVM wallet address to check token balances.
- **Token Analyzer**: Send a message like `token <0xContractAddress>` to analyze token details.

## How to Use

1. Chat directly with [Seiva Bot on Telegram](https://t.me/sei_vabot).
2. Use one of the supported commands or just send your question/address.
3. Get instant, AI-powered responses.

## Example Commands

- `wallet ballance checker`
- `token DEGEN 0x...` → analyze token details
- `ask  anything about Sei ecosystem?`

## Folder Structure

```bash
workflows/
├── wallet-checker.json
├── ask-anything.json
├── token-analyzer.json
└── help-and-start.json
