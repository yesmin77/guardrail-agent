# 🛡️ GuardRail Agent — Demo

## Test Case

**Request:** Buy $50 BTCUSDT Spot

**Execution:** Not allowed

## GuardRail Validation

| Check | Result |
|---|---|
| Capital Limit | ❌ FAIL |
| Allowed Asset | ✅ PASS |
| Trading Mode | ✅ PASS |
| Liquidity | ✅ PASS |
| Risk | ⚠️ UNVERIFIED |
| Human Confirmation | 🔐 REQUIRED |

## Verdict

### 🔴 BLOCKED

**Reason:** The requested $50 order exceeds the configured maximum order size of $10 USDT.

**NO ORDER SENT.**

GuardRail demonstrates that a market opportunity does not automatically become permission to trade.

---

## Safety Principle

**AI approval ≠ execution permission.**

GuardRail keeps policy enforcement and human control between the trading request and execution.
