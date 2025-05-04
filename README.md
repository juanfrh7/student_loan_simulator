# 🎓 Loan Repayment Optimization: BSc vs MSc Loans

This project analyzes how to **optimally split a fixed monthly payment** between two student loans — one from a Bachelor's degree (BSc) and one from a Master's degree (MSc). The goal is to either:

- **Minimize the total repayment time**, or
- **Reduce the total interest paid** across both loans.

It simulates concurrent loan repayment and explores different payment strategies using simple financial logic and Python.

---

## 🧠 Motivation

Student loans can span multiple academic programs, each with different principal amounts and interest rates. Paying them off in parallel with a fixed budget can be challenging:

- Which loan should get a larger share of the monthly payment?
- What happens when one loan is paid off — should that money be reallocated?
- How much interest could be saved by tweaking payment strategies?

This notebook helps answer these questions by simulating real-world payment behavior.

---

## 📁 Contents

| File/Section           | Description |
|------------------------|-------------|
| `simulate_loan()`      | Simulates single loan repayment with interest. |
| `simulate_loans()`     | Simulates concurrent repayment of both loans with reallocation. |
| `Scenario 1`           | Repayment using minimum required payments. |
| `Scenario 2`           | Boosted monthly payment of \$100 extra, split between loans. |
| `Optimization routine` | Brute-force search over payment splits to find the best strategy. |
| `README.md`            | You are here! Describes the project. |

---

## ⚙️ How It Works

1. **Define loan parameters**: principal, interest rate, and monthly payment.
2. **Simulate repayment**:
   - Interest is accrued monthly.
   - Payments reduce principal.
   - If one loan is paid off, its share of the payment is redirected to the other.
3. **Evaluate different strategies**:
   - Minimum payments.
   - Arbitrary extra payments.
   - Brute-force search for the optimal split.

---

## Contributions

Feel free to submit issues, suggestions, or improvements!
