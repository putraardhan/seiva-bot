# Seiva – Telegram AI Assistant for Sei Network

## Project Description

**Seiva** is a Telegram-based AI assistant built specifically for the Sei Network.

Seiva helps users:
- Track wallet activity on Sei (multi-token support)
- Ask intelligent questions about Sei and receive contextual AI responses
- Analyze token insights such as price, volume, holders, and change over time
- Get assistance and guides related to airdrops, staking, and bridging on Sei

The bot is built using n8n, OpenAI API, DexScreener integration, and Sei RPC endpoints, creating a smooth user experience directly from Telegram.

This project was created for the DoraHacks x Sei Hackathon to increase accessibility, transparency, and usability of the Sei blockchain ecosystem.

## Built for DoraHacks x Sei Hackathon
This project was developed specifically for the DoraHacks Sei Hackathon and integrates deeply with Sei's on-chain data.

## Demo
[Watch the demo video here](<https://www.youtube.com/watch?v=AK440aOmV64>)

## Sei Network Integration
- On-chain wallet tracker using Sei RPC and REST endpoints
- Fetches live data of trending tokens and ecosystem projects
- Context-aware project recommendations
- Built with OpenAI & Telegram Bot API via n8n automation

## Folder Structure & Contents
'''├── workflows/                        # JSON exports of n8n Telegram automation workflows
│   ├── ask-questions.json            # Handle user Q&A using OpenAI
│   ├── wallet-checker.json           # Track wallet balances and tokens
│   ├── token-checker.json            # Analyze token stats (price, holders, etc.)
│   └── start-and-help.json           # Provides help commands and onboarding
│
├── prompts/                          # Predefined system prompts for OpenAI agents
│   └── seiva_token_insight_agent.md  # Prompt to guide token analysis assistant
'''

## Example Commands
- `wallet ballance checker`
- `token analyzer 0x...` → analyze token details
- `ask  anything about Sei ecosystem?`

## Socials
- Telegram: [@SeivaBot](https://t.me/sei_vabot)
- Twitter: [@seiva_assistant](https://x.com/seiva_assistant)

## Tech Stack
- n8n
- Telegram Bot API
- OpenAI
- Sei RPC/REST
- Hosted on [n8n.cloud](https://n8n.cloud/)

## License
This project is licensed under the MIT License.
