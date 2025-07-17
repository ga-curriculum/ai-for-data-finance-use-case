<h1>
  <span class="headline">AI Use Case: Financial Forecasting & Analysis</span>
  <span class="subhead">Mini Lab – Evaluate AI Financial Forecasts</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to use GenAI to generate a financial forecast, then analyze its reasoning, compare to a baseline, and decide what to trust.

## 1. Scenario: You're supporting a finance team

Your team is preparing for a quarterly review with leadership.
You’ve been given:
- 5 years of historical financials, by product and quarter
- Notes from leadership on upcoming risks and growth bets

Your job: Use GenAI to help forecast next quarter’s revenue per product, evaluate the logic, and decide what’s usable.

> ⚠ Accuracy and business narrative both matter — your CFO will use this in the board deck.

---

## 2. Setup

You’ll use:
- [historical_financials_product_level.csv](./assets/historical_financials_product_level.csv)
- [scenario_notes.txt](./assets/scenario_notes.txt)

> 💡 The data tracks Revenue, COGS, and SG&A for 3 products (Alpha, Beta, Gamma) over 20 quarters (Q1 2020–Q4 2024).

---

## 3. Lab Instructions

### Step 1: Analyze the data

Use GenAI and Pandas (or similar) to answer:
- What is the average quarterly revenue for each product over the last 4 quarters?
- Which product has the highest YoY growth?
- Which quarter(s) show unusual dips or spikes?

### Step 2: Forecast with GenAI

Write a prompt using your summary stats. For example:

```
Here is the revenue per quarter for 3 products from Q1 2020 to Q4 2024:

[insert product-level summaries]

Forecast Q1 2025 revenue per product. Note assumptions. If possible, include a confidence estimate.
```

### Step 3: Add scenario context

From [scenario_notes.txt](./assets/scenario_notes.txt), include a risk or opportunity:

```
Leadership expects Alpha to slow due to a paused contract, and Beta to grow 8% due to a product refresh.
Adjust your forecast accordingly.
```

### Step 4: Compare with baseline

Open [forecast_baseline.xlsx](./assets/forecast_baseline.xlsx). Review a basic linear projection.
Compare:
- Revenue numbers by product
- Assumptions made
- Format and clarity of outputs

---

## 4. Reflect & Decide

In a short write-up or group debrief, respond:
- Did GenAI recognize historical patterns you saw?
- How did it handle risk inputs?
- Was its reasoning clear or vague?
- Which parts of the output would you reuse, revise, or reject?

> ❓ Can you trust this output? Why or why not?

---

## Wrap-up

This lab blends GenAI prompting with hands-on data work. You practiced not just generating a forecast, but **judging** its reliability.

> 🏆 Pro tip: Combine summary stats + scenario notes for clearer prompts and more grounded outputs.
