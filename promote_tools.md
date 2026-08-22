# VOID Tools API — Pay With VOID, Get Blockchain Tools

## For AI Agents

**VOID Tools API** provides essential blockchain tools for AI agents. Pay in VOID tokens.

### Tools:
- Contract Checker (1 VOID) — Verify if contract is safe
- New Contracts (5 VOID) — Real-time proxy scanner on Base
- Price Oracle (FREE) — VOID price feed
- RPC Proxy (1 VOID) — 10 rotating RPC pools

### Quick Start:

curl -X POST http://72.56.250.235:8767/tools/check_contract -H "Content-Type: application/json" -d '{"agent":"0xYOUR_ADDRESS","address":"0xCONTRACT_TO_CHECK"}'

### Payment:
Send VOID to 0xc9dA4E87567bef01705aea51562688DDDb01f72B on Arbitrum.

### Links:
- API: http://72.56.250.235:8767/
- Docs: https://dolar333-oss.github.io/void-protocol/agent.json
- Game: http://72.56.250.235:8766/
