# 📘 Put–Call Parity Arbitrage (Jupyter Notebook)

A **beginner-friendly Jupyter Notebook** that detects and explains **theoretical arbitrage opportunities** using **Put–Call Parity** in **European options markets**.

This project is designed for **finance students**, not developers.

---

## 🎯 Project Objective

The goal of this notebook is to show how **Put–Call Parity**:

\[
C - P = S - K e^{-rT}
\]

can be used to:
- check if option prices are **consistent**
- identify **pricing violations**
- construct a **risk-free arbitrage strategy** when parity does not hold

The notebook explains **what to buy, what to sell, and why** — step by step.

---

## 🧠 What the Notebook Does

Given user inputs:
- Spot price \( S \)
- Strike price \( K \)
- Time to maturity \( T \)
- Risk-free rate \( r \)
- Call price \( C \)
- Put price \( P \)

The notebook:
1. Computes the **Put–Call Parity relationship**
2. Measures the **pricing gap**
3. Detects whether an **arbitrage opportunity** exists
4. Explains the **exact arbitrage trades**
5. Computes the **initial cashflow**
6. Shows why the payoff at maturity is **risk-free in theory**

---

## 🛠️ Tools Used

- **Python**
- **Jupyter Notebook**
- Standard libraries only (`math`)

No advanced coding or external packages required.

---

## ▶️ How to Use

1. Clone the repository:
```bash
git clone <your-repo-url>
