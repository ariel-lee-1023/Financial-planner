# Principles of Corporate Finance — Brealey, Myers, Allen & Edmans (14th ed.)
**Format**: markdown (extracted textbook) | **Pages**: ~900+ | **Sections**: valuation, risk, financing, governance | **Depth**: study (household-relevant core)

## Mental Model (read first)
Finance is the application of the **net-present-value rule** under uncertainty. Every real decision is a claim on future cash flows; the correct price of those cash flows is obtained by discounting at the **opportunity cost of capital** (the return available on an equivalent-risk alternative). Tax shields, leverage, and agency problems modify the cash flows or the discount rate, but they do not replace the NPV logic. For a household the same machinery adjudicates “pay down the loan vs. invest vs. fund a goal.”

## Frameworks & Structure

### Valuation and the NPV rule (Parts 1–3)
- **Core idea**: Accept projects (or personal decisions) with positive NPV; among mutually exclusive options choose the highest NPV.
- **NPV formula**:
  ```
  NPV = −C₀ + Σₜ Cₜ / (1 + r)ᵗ
  ```
  where `r` is the opportunity cost of capital for cash flows of that risk class.
- **Opportunity cost of capital**: the expected return shareholders (or the household) forgo by committing capital here rather than in a matched-risk market investment. It is the single consistent hurdle that makes “pay debt / invest / consume” comparable.
- **Law of one price / value additivity**: two identical cash-flow streams must have the same present value; portfolios are worth the sum of parts in perfect markets.
- **Anti-pattern** — using accounting rates of return, payback, or internal rate of return without NPV as the primary screen; IRR can rank mutually exclusive projects incorrectly and is silent on scale.

### Risk, return, and the cost of capital
- **Market risk vs. specific risk**: only non-diversifiable (market/beta) risk is priced; idiosyncratic risk is not compensated in equilibrium.
- **CAPM / multifactor models**: expected return ≈ r_f + β × market risk premium (+ other factor premia). For household decisions the relevant “equity” opportunity cost is the expected after-tax return on the diversified portfolio the cash would otherwise occupy.
- **Certainty equivalents vs. risk-adjusted discount rates**: two equivalent ways to handle risk; risk-adjusted rates are the practical default.
- **Anti-pattern** — discounting risky personal cash flows at the risk-free rate, or applying a single “hurdle rate” to projects of very different risk.

### After-tax cost of debt, tax shields, and WACC
- **After-tax cost of debt**:
  ```
  r_D (1 − T_c)
  ```
  Interest tax deductibility (where available) lowers the effective cost.
- **After-tax weighted-average cost of capital**:
  ```
  WACC = r_D (1 − T_c) (D/V) + r_E (E/V)
  ```
  Use market values; adjust when debt capacity or business risk changes.
- **Interest tax shield**: the present value of tax savings from deductible interest is a real source of value (Modigliani–Miller with taxes).
- **Household translation**: the “cost of debt” is the after-tax loan rate; the “cost of equity” is the after-tax expected return on the alternative use of cash. The spread between them is the financial edge of borrowing vs. using cash.
- **Anti-pattern** — comparing pre-tax investment returns with after-tax debt costs, or ignoring the tax shield when it is available.

### Financing decisions, payout, and capital structure
- **MM propositions (baseline)**: in perfect markets capital structure and dividend policy are irrelevant; value is determined by real assets.
- **Trade-off theory**: optimal leverage balances tax shields against costs of financial distress and agency costs.
- **Pecking-order / asymmetric-information effects**: managers prefer internal funds, then debt, then equity.
- **Payout policy**: dividends vs. repurchases; information content; residual policy after investment needs are met.
- **Household parallel**: the household capital structure decision is exactly the Anderson enrichment/oppressive classification plus the NPV spread calculation.

### Options, real options, and flexibility
- **Financial options** (calls, puts) and the Black–Scholes/binomial machinery give the value of asymmetric payoffs.
- **Real options**: the option to delay, expand, abandon, or switch a project can dominate a naïve NPV that treats the decision as now-or-never.
- **Household parallel**: liquidity and undrawn credit lines are real options; their value rises with uncertainty — the formal justification for Anderson’s “value liquidity.”

### Governance, agency, and corporate objectives (later chapters)
- **Agency problems**: conflicts between managers and shareholders, and between shareholders and creditors.
- **Stakeholder vs. shareholder objectives**: recent editions (Edmans) expand the discussion of purpose, long-term value, and responsible business; the core NPV logic remains the measurement engine.
- **Anti-pattern** — treating governance or ESG as a substitute for cash-flow discipline rather than a modifier of long-run cash flows and risk.

## Worked Example
**Graduate-degree financing.**  
Tuition $60 k due now; low-cost student loan at 5.5 % (non-deductible); after-tax liquid return opportunity ~4.5 % (conservative short-term) or ~6 % (balanced portfolio).  
NPV of “borrow and keep cash invested” ≈ present value of interest differential. At a modest negative financial spread the loan still dominates if it preserves a second near-term goal (liquidity real option). Recompute with the actual tax rate, the true expected portfolio return, and a stress scenario (loss of income). The ranking is the input to the Anderson liquidity gate and the Leimberg foundation gate; it is not the final recommendation by itself.

## Decision Rules & Judgment
- Always express competing personal-finance options as after-tax cash-flow streams and rank by NPV at a risk-appropriate opportunity cost of capital.
- After-tax cost of debt = r_D (1 − T_c); never compare pre-tax returns with after-tax debt costs.
- Positive NPV is necessary but not sufficient — it is utility-blind and liquidity-blind; hand the ranking to Anderson (liquidity/leverage limits) and Perkins (age-varying utility).
- Real-option value of cash and credit lines rises with uncertainty; a thin positive NPV that destroys optionality is often the wrong choice.
- Diversifiable risk should not raise the household discount rate; concentration risk should.
- When debt capacity or risk changes, recompute WACC / opportunity cost; do not use a stale blended rate.

## Key Takeaways
1. NPV at the opportunity cost of capital is the neutral ranking engine for every cash-vs-borrow-vs-invest decision.
2. After-tax cost of debt is the correct comparison rate for payoff-vs-invest choices.
3. Only non-diversifiable risk is priced; size leverage so that stress scenarios remain survivable.
4. Tax shields are real value; ignore them only when they are legally unavailable.
5. Liquidity and flexibility are real options whose value is invisible to a myopic interest-rate comparison.
6. Capital-structure theory (trade-off, pecking order) maps directly onto household debt taxonomy and sequencing.
7. Never let a pure positive-NPV answer end the analysis before liquidity and life-stage utility checks.
