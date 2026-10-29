# PARANOID

PARANOID lets you use AI models without the service learning who asked. You buy a pack of questions once,
and every question then carries a fresh zero-knowledge proof, made on your own device, that it was paid for.
The gateway can check the proof but cannot tell which member sent it, and no two questions can be tied to
each other or to the wallet that paid.

It runs open models such as DeepSeek, Kimi, Qwen and GLM, including uncensored ones, and the questions are
paid for on Solana in USDC or in $PARANOID.

## $PARANOID

CA: `22rWiyDiY9GgxSrFiWC2vX1GxNxjkvrRPmZJDzv9pq6X` ([Solscan](https://solscan.io/token/22rWiyDiY9GgxSrFiWC2vX1GxNxjkvrRPmZJDzv9pq6X))

The supply can only go down, because the mint has no authority left to create more. Every USDC purchase of
questions buys $PARANOID back, half for stakers and half to burn, and questions paid in $PARANOID burn the
tokens outright.

## Use it

- **In the browser** at [paranoid.red/app](https://paranoid.red/app): buy questions, then chat.
- **In Claude Code, Cursor or any MCP client** with [paranoid-mcp](https://github.com/paranoiddotred/paranoid-mcp),
  one file with no install step.
- **From your own app or agent** through an OpenAI-compatible endpoint. Agents can buy their own questions
  with x402, as the [docs](https://paranoid.red/docs/agents) explain.

## Repositories

| Repository | What is in it |
| --- | --- |
| [paranoid](https://github.com/paranoiddotred/paranoid) | The Solana program, the request circuit and their tests. The source builds to the exact bytes deployed on mainnet. |
| [paranoid-mcp](https://github.com/paranoiddotred/paranoid-mcp) | The connector for Claude Code, Cursor and other MCP clients. |

## Credit

PARANOID is built on zkAPI, released by the Ethereum Foundation and the Open Anonymity Project from the design
Vitalik Buterin and Davide Crapis proposed: deposit once, make paid calls that cannot be linked, and catch
anyone who spends a ticket twice.

Follow along on [X](https://x.com/paranoiddotred) and read more at [paranoid.red](https://paranoid.red).
