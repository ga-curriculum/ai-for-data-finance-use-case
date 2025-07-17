<h1>
  <span class="headline">AI Use Case: Financial Forecasting & Analysis</span>
  <span class="subhead">Prompting GenAI for Forecasting & Risk</span>
</h1>

**Learning objective:** By the end of this lesson, students will practice crafting GenAI prompts for financial forecasting, trend analysis, and risk scenario exploration.

## 1. Warm-up: What makes a good forecasting prompt?

GenAI isn’t a spreadsheet. It can’t “calculate” in the same way. But it *can*:

- Describe data trends in natural language
- Extend patterns into likely future outcomes
- Simulate responses to “what if” inputs

To do that well, your prompt needs:

- Clean context (like a revenue table)
- Clear task (“Forecast next 2 quarters”)
- Optional: constraints or assumptions to guide the logic

> 💡 GenAI thrives when you *tell it how to think* — not just what to do.

---

## 2. Prompt pattern: Forecast from past performance

Use this structure when prompting GenAI for projections:

**Prompt Template:**
```
Given the quarterly revenue data below, forecast the next 2 quarters.
Assume a linear trend unless otherwise indicated. List your assumptions.

[insert table or CSV]
```

**Optional Add-ons:**
- "Highlight any anomalies in Q6–Q8."
- "Include a confidence estimate for your projection."
- "Simulate a 10% rise in COGS."

---

## 3. Try it: Your turn to prompt

Open the file: [historical_financials.csv](./assets/historical_financials.csv)

You’ll see:
- Revenue
- COGS (cost of goods sold)
- SG&A (selling, general & administrative expenses)
- 8 quarters of data

### Your tasks:
1. Write a GenAI prompt for **trend analysis**
2. Write a GenAI prompt for **forecasting**
3. Write a GenAI prompt for a **"what if" risk scenario**
   - e.g., "What if SG&A increases by 15% next quarter?"

> 🧠 Use this as a quick format:
> *"Here is a CSV with past 8 quarters. Forecast revenue next 2 quarters. Note assumptions."*