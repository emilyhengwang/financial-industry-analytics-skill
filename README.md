# 📊 Financial Industry Analytics — Claude AI Tutor Skill

A Claude AI skill designed for **MSBA students** in the *Financial Industry Analytics* course. It acts as a friendly, always-available tutor that explains finance concepts in plain English, debugs Python code, and walks students through hands-on financial analysis — no finance or coding background required.

---

## 🎯 What This Skill Does

| Capability | Description |
|---|---|
| 💬 Finance concept explainer | Plain-English definitions, real-world analogies, intuition before math |
| 🐛 Python code debugger | Identifies errors, explains causes, shows fixes with prevention tips |
| 🧑‍💻 Step-by-step coding walkthroughs | Annotated templates for every major finance coding task |
| 🔗 Theory ↔ code connector | Always answers: *what does this code mean financially?* |

---

## 📚 Course Modules Covered

| Module | Topics |
|---|---|
| 1 — Python & Data Basics | Jupyter setup, pandas, `yfinance`, loading financial data |
| 2 — Time Series & Volatility | Returns, log returns, rolling volatility, GARCH models |
| 3 — Risk & Portfolios | VaR, CVaR, Sharpe ratio, diversification |
| 3b — Portfolio Optimization | Efficient frontier, mean-variance optimization, min-variance & max-Sharpe portfolios |
| 4 — Asset Pricing & Prediction | CAPM, Fama-French factors, alpha, predictive regression |
| 5 — Sentiment & Capstone | VADER, FinBERT, NLP for finance, merging sentiment with returns |

---

## 🚀 How to Install

### Option 1 — Install via `.skill` file (recommended)
1. Download [`fia-skill.skill`](./fia-skill.skill)
2. In Claude.ai, go to **Settings → Skills**
3. Upload the `.skill` file
4. The skill is now active in your conversations

### Option 2 — Manual install from `SKILL.md`
1. Copy the contents of [`SKILL.md`](./SKILL.md)
2. In Claude.ai, go to **Settings → Skills → Create New Skill**
3. Paste the content and save

---

## 💡 Example Student Prompts

Once installed, students can ask things like:

```
"What is the efficient frontier and why does it matter?"
"My yfinance download is returning an empty DataFrame — what's wrong?"
"Walk me through how to build a max Sharpe portfolio in Python"
"What's the difference between VADER and FinBERT for sentiment analysis?"
"Why do we use log returns instead of simple returns?"
"What does beta actually mean — is it the same as volatility?"
"Help me debug this GARCH model error"
"How do I merge FinBERT sentiment scores with stock return data?"
```

---

## 📦 Repository Structure

```
fia-github-repo/
├── SKILL.md          # The full Claude skill definition
├── fia-skill.skill   # Packaged skill file (ready to upload)
└── README.md         # This file
```

---

## 🛠️ Key Python Libraries Covered

| Library | Used For |
|---|---|
| `pandas` | DataFrames, time series manipulation |
| `yfinance` | Downloading real market data |
| `numpy` | Numerical computation, matrix operations |
| `matplotlib` | Plotting prices, returns, frontiers |
| `statsmodels` | OLS regression, CAPM, Fama-French |
| `scipy.optimize` | Portfolio optimization (min variance, max Sharpe) |
| `arch` | GARCH volatility models |
| `transformers` | FinBERT sentiment analysis (HuggingFace) |
| `vaderSentiment` | Rule-based sentiment (fast baseline) |

---

## 🤖 About This Skill

This skill was built using [Anthropic's Claude](https://claude.ai) skill system. It instructs Claude to behave as a patient, analogy-driven tutor — always explaining the *why* behind finance concepts and code, not just the *what*.

The skill follows a consistent response structure:
- **Concept questions**: Plain English → Analogy → Why it matters → Math → Code
- **Debug requests**: Error type → Root cause → Fix → Prevention tip
- **Code walkthroughs**: Goal → Steps → Block-by-block explanation → Output interpretation

---

## 📝 License

MIT License — free to use, share, and adapt for educational purposes.

---

## 🙋 Contributing

Found a bug in a code template? Want to add a new module or analogy? Pull requests are welcome!

1. Fork the repo
2. Edit `SKILL.md`
3. Submit a pull request with a description of what you changed

---

*Built for MSBA students. Powered by Claude AI.*
