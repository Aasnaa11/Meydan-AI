 # Meydan AI — Investor Decision Support Engine

An AI-powered business viability tool built for UAE 
entrepreneurs and Meydan Free Zone investors.

Type in your business idea and get a full analysis
in seconds — no consultant fees, no waiting.

---

## What It Does

Takes basic business inputs and returns:

- Viability score out of 10
- Risk level — Low, Medium, or High
- Estimated profit range in UAE Dirhams
- 5-year revenue and cost projection chart
- UAE market data for your industry
- Strategic report with 4 action steps

---

## How It Works

User inputs → Llama 3.2 via Groq API → structured
business intelligence report. A second rule-based
layer checks budget and revenue targets independently.

Results appear across 3 dashboard screens:
1. Viability score + financial projections
2. UAE market data + competitor landscape  
3. Written strategic recommendations

---

## Why UAE-Specific

- Data and benchmarks built for UAE and Meydan Free Zone
- Covers 8 major UAE industries
- Supports English and Arabic output
- Relevant to local market conditions, not generic global data

---

## Tech Stack

Python · Streamlit · Groq API · Llama 3.2 · Plotly

---

## Setup

1. Install dependencies:

```bash
pip install streamlit groq plotly
```

2. Add your Groq API key:

```python
GROQ_API_KEY = "YOUR_GROQ_API_KEY"
```

3. Run the app:

```bash
streamlit run app.py
```

---

## Architecture

Single-file Python application.
No database. No complex server setup.
Streamlit handles the UI, Plotly handles
charts, Groq API handles AI inference.

---

## Status

Completed · 2026
Built for Meydan Free Zone ecosystem
