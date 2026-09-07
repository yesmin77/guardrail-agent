# 🛡️ GuardRail Agent

A Binance Agent OS safety layer built around one principle: **a market opportunity is not permission to trade.**

GuardRail evaluates a proposed trade using market evidence, risk policies, and human approval before execution.

---

## What is GuardRail?

GuardRail is an AI-powered trading safety and policy agent for Binance Agent OS.

Instead of:

**Signal → Trade**

GuardRail uses:

**Request → Evidence → Policy → Risk → Human Approval → Order**

It does not decide whether a trade is profitable.  
**It decides whether the trade is allowed to proceed.**

---

## 🔄 How It Works

```text
Trade Request
     ↓
Binance MCP
     ↓
Market & Account Check
     ↓
Policy Engine
     ↓
Risk Validation
     ↓
APPROVED / BLOCKED
     ↓
Human Confirmation
     ↓
Order
## 🔄 🛡️ Safety Checks
💰 Capital limit
🪙 Allowed assets
📊 Trading mode
💧 Market liquidity
⚠️ Risk conditions
👤 Human confirmation
If a mandatory rule fails:
🔴 BLOCKED
If all mandatory rules pass:
🟢 APPROVED FOR HUMAN CONFIRMATION
## 🔄 Demo
BUY BTCUSDT — $50 USDT — Spot
Maximum order: $10 USDT
Result:
🔴 BLOCKED
Reason: The requested amount exceeds the maximum order limit.
NO ORDER SENT.
## 🔄 📋 Default Policy
Rule
Setting
Maximum order
$10 USDT
Trading mode
Spot
Allowed assets
BTC, ETH, BNB
Human confirmation
Required
Failed rule
BLOCK
## 🔄 🔐 Safety Principles
GuardRail never:
Invents market or account data
Fabricates balances or positions
Claims execution without Binance confirmation
Bypasses failed safety rules
Executes without explicit human confirmation
Unavailable data is marked UNVERIFIED, not assumed.
## 🔄 🎯 Why GuardRail?
Most trading agents ask:
“Should I trade?”
GuardRail asks:
“Is this trade allowed under my rules?”
This creates a controlled and explainable safety layer between an AI request and trade execution.
## 🔄 👤 Human-in-the-Loop
Even when all policy checks pass, the user must explicitly confirm before execution.
AI approval ≠ permission to execute.
## 🔄 🧩 Binance Agent OS
GuardRail is designed for Binance Agent OS and its MCP interface.
Available Binance data is used as evidence for policy and risk validation.
## 🔄 🏗️ Project Status
Binance Agent OS Mini Hackathon 2026 — Track A
Focus:
Binance Agent OS / MCP
Policy enforcement
Risk validation
Market-data checks
Human confirmation
Explainable decisions
## 🔄 ⚠️ Disclaimer
GuardRail is a prototype for demonstration and research purposes.
It is a safety and policy-control system and does not guarantee trading profits or provide personalized financial advice.
Always review and confirm any trading action before execution.
