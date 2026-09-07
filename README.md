# 🛡️ GuardRail Agent

A Binance Agent OS safety layer built around one simple principle: **a market opportunity is not permission to trade.** GuardRail evaluates a proposed trade using live market evidence, predefined risk policies, and human approval before allowing it to proceed.

At its core, it is a **Policy & Risk Validation workflow** — checking capital limits, allowed assets, trading mode, market liquidity, and risk conditions before producing a clear **APPROVED** or **BLOCKED** verdict.

---

## What is GuardRail?

GuardRail is an AI-powered trading safety and policy agent designed for Binance Agent OS.

Instead of focusing on:

**Signal → Trade**

GuardRail focuses on:

**Request → Evidence → Policy → Risk Check → Human Approval**

The agent does not decide whether a trade is profitable.

**It decides whether the proposed trade is allowed to proceed.**

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
Order ---

## 📋 Default Policy

| Rule | Setting |
|---|---|
| Maximum order | $10 USDT |
| Trading mode | Spot |
| Allowed assets | BTC, ETH, BNB |
| Human confirmation | Required |
| Failed mandatory rule | BLOCK |

---

## 🧩 Binance Agent OS Integration

GuardRail is designed to work with Binance Agent OS and its MCP interface.

It uses available Binance data as evidence for policy and risk validation before producing a decision.

The system does not assume data that is unavailable.

---

## 🏗️ Project Status

**Binance Agent OS Mini Hackathon 2026 — Track A**

Current focus:

- Binance Agent OS / MCP integration
- Pre-trade policy enforcement
- Market-data validation
- Risk validation
- Human confirmation
- Explainable decisions
- Safe execution flow

---

## ⚠️ Disclaimer

GuardRail is a prototype created for demonstration and research purposes.

It is a safety and policy-control system and does not guarantee trading profits or provide personalized financial advice.

Always review and confirm any trading action before execution.
