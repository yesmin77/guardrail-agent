# 🛡️ GuardRail Agent

A Binance Agent OS safety layer built around one principle: **a market opportunity is not permission to trade.**

GuardRail validates proposed trades using live market evidence, predefined risk policies, and human approval before execution.

---

## 🎯 Core Workflow

Instead of:

**Signal → Trade**

GuardRail uses:

**Request → Evidence → Policy → Risk → Human Approval → Order**

Trade Request  
↓  
Binance MCP  
↓  
Market & Account Check  
↓  
Policy & Risk Validation  
↓  
APPROVED / BLOCKED  
↓  
Human Confirmation  
↓  
Order

It determines whether a trade is **allowed to proceed**, not whether it will be profitable.

---

## 🛡️ Safety & Demo

GuardRail checks:

**Capital · Asset · Mode · Liquidity · Risk · Human Approval**

**Example:** BUY BTCUSDT — **$50 USDT** — Spot

Policy limit: **$10 USDT**

### 🔴 BLOCKED

**Reason:** Requested amount exceeds the configured capital limit.

**NO ORDER SENT.**

GuardRail never fabricates data, bypasses failed rules, or claims unconfirmed execution.

**AI approval ≠ execution permission.**

---

## 🧩 Binance Agent OS

GuardRail is designed for **Binance Agent OS** and its MCP interface, using available Binance data for policy and risk validation.

### Default Policy

| Rule | Setting |
|---|---|
| Maximum order | $10 USDT |
| Mode | Spot |
| Assets | BTC, ETH, BNB |
| Confirmation | Required |
| Failed rule | BLOCK |

**Binance Agent OS Mini Hackathon 2026 — Track A**

---

## ⚠️ Disclaimer

GuardRail is a prototype for demonstration and research purposes.

It is a safety and policy-control system and does not guarantee trading profits or provide personalized financial advice.

Always review and confirm any trading action before execution.
