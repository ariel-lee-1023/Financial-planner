# Reference — Brealey, Myers & Allen, *Principles of Corporate Finance*

This book supplies the **neutral arbitration math**. It has no opinions about liquidity,
life stages, or morality — it converts every option into a single comparable number so
the other three frameworks can be adjudicated on a common scale. When Anderson and
Perkins disagree, this is the ruler you measure them with.

## 1. The Net Present Value (NPV) rule

Accept a decision if it adds value; the value it adds is its NPV:

```
NPV = −C0 + Σ ( Ct / (1 + r)^t )   for t = 1..n
```

- `C0` = cash outlay today (a debt repayment, a tuition payment, an investment).
- `Ct` = cash flow in period t (savings, returns, avoided interest).
- `r` = the discount rate = **opportunity cost of capital**.
- Decision rule: **do it if NPV > 0**; between mutually exclusive options, pick the
  highest NPV.

## 2. The opportunity cost of capital sets the hurdle

The discount rate is the return you *give up* by committing the money here instead of in
a capital-market alternative **of equivalent risk**. This is the concept that lets you
compare "pay down the loan" against "invest the cash" against "fund the goal": each is
scored against the same risk-appropriate opportunity cost.

Corollary — **money has a time value and risk has a price.** Cash flows further in the
future, or less certain, are discounted more heavily.

## 3. Cost of debt, tax shield, and WACC

Interest is tax-deductible in many contexts, which lowers the *effective* cost of debt:

```
After-tax cost of debt = rD × (1 − Tc)
```

The **after-tax weighted-average cost of capital**, the blended hurdle rate for a mixed
debt/equity balance sheet:

```
After-tax WACC = rD × (1 − Tc) × (D/V) + rE × (E/V)
```

where `D`, `E` are the market values of debt and equity, `V = D + E`, `Tc` is the tax
rate, `rD`/`rE` the required returns on debt/equity. (Worked example in the text:
3.4 × (1 − 0.21) × 0.22 + 10.3 × 0.78 ≈ 8.6%.)

For a household this translates cleanly: the "cost of debt" is your after-tax loan rate,
and the "opportunity cost of equity" is the after-tax expected return on what you'd
otherwise do with the cash (invest, or fund another goal).

## 4. How to use it in personal-finance arbitration

1. Express every option as a stream of after-tax cash flows across time.
2. Pick a risk-appropriate discount rate (opportunity cost of capital) for each.
3. Compute and compare NPVs; the highest-NPV option is the financially optimal one.
4. Hand the ranking to the other frameworks, which may adjust it for liquidity
   (Anderson), foundation/insurance (Leimberg), or personal utility (Perkins).

## When it applies vs. does not

- **Applies:** always, as the calculation layer. Any time cash flows must be compared
  across time, or you must choose between cash / borrowing / investing.
- **Does NOT stand alone:** it is **utility-blind and liquidity-blind**. It assumes a
  rational agent, prices neither the insurance value of cash nor age-locked life
  experiences, and optimizes financial value, not lifetime fulfillment. Never let a
  positive-NPV answer end the analysis before the liquidity stress test and the Perkins
  utility check.
