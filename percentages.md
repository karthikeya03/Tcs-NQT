# 📊 Percentages — Complete TCS NQT Notes
> **Your Status:** Concepts 1–3 done ✅ | Continue from 4 below
---

## ✅ What You Already Know

| # | Concept | Formula |
|---|---|---|
| 1 | % → Fraction | Divide by 100 → `x% = x/100` |
| 2 | Fraction → % | Multiply by 100 → `(a/b) × 100` |
| 3 | Increase/Decrease by x% | New = Original × `(100 ± x) / 100` |

---

## 📌 Must-Know Fraction ↔ Percentage Table
> **Memorise this table. It will save you 20–30 seconds per question.**

| Fraction | Percentage | Fraction | Percentage |
|---|---|---|---|
| 1/2 | **50%** | 1/9 | **11.11%** |
| 1/3 | **33.33%** | 1/10 | **10%** |
| 1/4 | **25%** | 1/11 | **9.09%** |
| 1/5 | **20%** | 1/12 | **8.33%** |
| 1/6 | **16.67%** | 2/3 | **66.67%** |
| 1/7 | **14.28%** | 3/4 | **75%** |
| 1/8 | **12.5%** | 3/5 | **60%** |

> 💡 **How to use this:** If a question says "what is 1/8 of 640?" — you instantly know it's 12.5% of 640 = 80. No calculation needed.

---

## 4️⃣ Percentage of a Number

**Formula:**
```
x% of N = (x / 100) × N
```

**Example:**
> What is 35% of 480?
```
= (35/100) × 480
= 35 × 4.8
= 168 ✅
```

**Trick — Break into parts:**
```
35% of 480
= 30% of 480 + 5% of 480
= 144 + 24
= 168 ✅
```
> 💡 Always break ugly percentages into `10% + 5% + ...` chunks. Much faster.

---

## 5️⃣ What Percent is A of B?

**Formula:**
```
(A / B) × 100
```

**Example:**
> 45 is what % of 180?
```
= (45 / 180) × 100
= (1/4) × 100
= 25% ✅
```

> 💡 **Trick:** Always simplify the fraction FIRST before multiplying by 100.

---

## 6️⃣ Finding the Original Number (Reverse Percentage)

> This is one of the **most asked types in TCS NQT.** Very easy to get wrong if you use the wrong base.

**Situation:** After a x% increase/decrease, the final value is Y. Find original.

**Formula:**
```
Original = (Final Value × 100) / (100 ± x)
```

**Example 1 — Increase:**
> After a 20% increase, a number becomes 480. Find original.
```
Original = (480 × 100) / 120
= 48000 / 120
= 400 ✅
```

**Example 2 — Decrease:**
> After a 25% decrease, a number becomes 600. Find original.
```
Original = (600 × 100) / 75
= 60000 / 75
= 800 ✅
```

> ⚠️ **Common Mistake:** Students calculate 20% of 480 = 96, then subtract. WRONG. 
> The 20% was applied on the ORIGINAL, not the final. Always use the formula above.

---

## 7️⃣ Percentage Change (Increase / Decrease)

**Formula:**
```
% Change = [(New Value − Old Value) / Old Value] × 100
```

- If result is **positive** → % Increase
- If result is **negative** → % Decrease

**Example:**
> Price went from ₹400 to ₹520. What is the % increase?
```
= [(520 − 400) / 400] × 100
= [120 / 400] × 100
= 30% increase ✅
```

---

## 8️⃣ Successive Percentage Change ⭐ (Very Frequently Asked)

> When a value is changed by x% and then again by y%, the **net % change is NOT x + y.**

**Formula:**
```
Net % Change = x + y + (xy / 100)
```
- Use **+** for increase, **−** for decrease

**Example 1 — Both Increases:**
> A number is increased by 20%, then again by 10%. Net change?
```
= 20 + 10 + (20 × 10)/100
= 30 + 2
= 32% increase ✅
```

**Example 2 — One Increase, One Decrease:**
> Price increased by 30%, then decreased by 20%. Net change?
```
= 30 + (−20) + (30 × −20)/100
= 10 + (−600/100)
= 10 − 6
= 4% increase ✅
```

**Example 3 — Both Decreases:**
> A value is decreased by 10%, then by 10%. Net change?
```
= −10 + (−10) + (−10 × −10)/100
= −20 + 1
= −19% → 19% decrease ✅
```

> 💡 **TCS Favourite:** "A number is increased by 10% and then decreased by 10% — is it the same?"
> Answer: **NO** → Net = −1% (always a small loss when same % applied up then down)

---

## 9️⃣ Percentage More Than / Less Than ⭐

> Most confusing concept. Read carefully.

### Case A — A is what % MORE than B?
```

= [(A − B) / B] × 100

```
Base is **B** (the one being compared against).

### Case B — A is what % LESS than B?
```

= [(B − A) / B] × 100

```
Base is still **B**.

---

### Example

A earns ₹800, B earns ₹1000.

- **A's salary is what % less than B?**  
  [(1000 − 800) / 1000] × 100 = **20%**

- **B's salary is what % more than A?**  
  [(1000 − 800) / 800] × 100 = **25%**

⚠️ **Key Insight:**  
20% less ≠ 20% more because the **denominator (base) changes**.

- For **less**, base = bigger number (B)
- For **more**, base = smaller number (A)

---

## 🧠 Can also be solved without formulas

You do not actually need to remember the formula.  
Just follow these steps logically.

1. **Find the difference**
```

Difference = Bigger − Smaller

```

2. **Identify the base**
- If the question says **less than B**, compare with **B**
- If the question says **more than A**, compare with **A**

3. **Convert the difference into a percentage of the base**
```

Percentage = Difference / Base

```

---

### Mental Method Example

A = 800  
B = 1000  

Difference = **200**

**A is % less than B**

Think:  
200 out of 1000

```

200 / 1000 = 0.2 = 20%

```

So **A is 20% less than B**.

---

**B is % more than A**

Think:  
200 out of 800

```

200 / 800 = 0.25 = 25%

```

So **B is 25% more than A**.

---

✔️ **Shortcut idea**

Instead of memorizing formulas, remember:
```
Percentage comparison = Difference ÷ Base
```
```
Then convert the result into percent.
```

## 🔟 Population / Price Growth Formula ⭐

> Used when something grows/decays at a constant % per year.

**Formula:**
```
Final Value = Initial Value × (1 ± r/100)^n
```
- `r` = rate per year
- `n` = number of years
- `+` for growth, `−` for decay/depreciation

**Example:**
> Population of a city is 2,00,000. It grows at 5% per year. Population after 2 years?
```
= 200000 × (1 + 5/100)²
= 200000 × (1.05)²
= 200000 × 1.1025
= 2,20,500 ✅
```

> 💡 This formula is the same as **Compound Interest**. Learn once, use everywhere.

---

## 1️⃣1️⃣ Income / Expenditure Type (Classic TCS Pattern) ⭐⭐

> **"Income increases by x%, expenditure increases by y%, find % change in savings"**
> This is a 2–3 mark question that appears almost every year.

**Standard Method — Use Values:**

**Example:**
> Income increases by 20%, expenditure increases by 10%.
> Originally income = ₹500, expenditure = ₹400, savings = ₹100.
> Find % change in savings.

```
Step 1: Assume income = 500, expenditure = 400, savings = 100
Step 2: New income = 500 × 1.20 = 600
Step 3: New expenditure = 400 × 1.10 = 440
Step 4: New savings = 600 − 440 = 160
Step 5: % change in savings = [(160−100)/100] × 100 = 60% increase ✅
```

> 💡 **Always assume convenient numbers** (multiples of 100). Don't work with variables.

---

## 1️⃣2️⃣ Price × Consumption = Expenditure Type ⭐⭐

> **"Price increases by x%. By how much % must consumption be reduced to keep expenditure same?"**

**Formula:**
```
Required Reduction % = [x / (100 + x)] × 100
```

**Example:**
> Price of petrol increases by 25%. By how much % should consumption be reduced?
```
= [25 / (100 + 25)] × 100
= [25 / 125] × 100
= 20% ✅
```

**Reverse — Price decreases:**
> Price decreases by 20%. By how much % can consumption be increased?
```
Formula: [x / (100 − x)] × 100
= [20 / 80] × 100
= 25% ✅
```

> 💡 **Memory Trick:** Price UP → consumption must come DOWN → divide by (100 + x)
> Price DOWN → consumption can go UP → divide by (100 − x)

---

## 1️⃣3️⃣ Marks / Exam Percentage Type ⭐

**Type 1 — Find marks when % given:**
> A student scores 65% in an exam. Max marks = 800. Marks scored?
```
= (65/100) × 800 = 520 ✅
```

**Type 2 — Passed/Failed type (Very common in TCS):**
> A student scored 30% and failed by 20 marks. Pass % is 40%. Find max marks.
```
Pass marks = 40% of Max
Student got = 30% of Max
Difference = 10% of Max = 20 marks
Max = 20 × 100/10 = 200 ✅
```

**Type 3 — Two students comparison:**
> A scored 40%, B scored 60%. B scored 30 more marks than A. Find max marks.
```
Difference = 60% − 40% = 20% of Max = 30
Max = (30/20) × 100 = 150 ✅
```

---

## 1️⃣4️⃣ Election / Votes Type ⭐

**Classic Pattern:**
> In an election between 2 candidates, winner got 60% of votes and won by 240 votes. Find total votes.

```
Winner = 60%, Loser = 40%
Difference = 20% of Total = 240
Total = (240/20) × 100 = 1200 ✅
```

---

## 1️⃣5️⃣ Data Interpretation with Percentages

> In TCS DI questions, you'll see % of totals in tables/pie charts. Key formulas:

```
Actual Value = (% / 100) × Total
% Share = (Part / Total) × 100
% Change between years = [(New − Old) / Old] × 100
```

> 💡 For pie charts: if a sector = 72°, its % = (72/360) × 100 = **20%**

---

## ⚡ Speed Tricks Summary

| Trick | How |
|---|---|
| **10% of any number** | Move decimal one place left. 10% of 450 = 45 |
| **5% of any number** | Half of 10%. 5% of 450 = 22.5 |
| **1% of any number** | Move decimal two places left. 1% of 450 = 4.5 |
| **25% of any number** | Divide by 4 |
| **50% of any number** | Divide by 2 |
| **33.33% of any number** | Divide by 3 |
| **12.5% of any number** | Divide by 8 |
| **Breaking method** | 37% = 30% + 7% = 30% + 5% + 2% |

---

## 🧩 TCS NQT — Percentage Question Types & Frequency

| Question Type | Frequency | Difficulty |
|---|---|---|
| Reverse percentage (find original) | ⭐⭐⭐ Very High | Easy |
| Successive % change | ⭐⭐⭐ Very High | Easy–Medium |
| Income/Expenditure/Savings | ⭐⭐⭐ Very High | Medium |
| Price × Consumption | ⭐⭐ High | Medium |
| Exam marks (pass/fail) | ⭐⭐ High | Easy |
| % more / % less than | ⭐⭐ High | Easy |
| Election / Votes | ⭐ Medium | Easy |
| Population growth | ⭐ Medium | Medium |

---

## 🔁 Practice Questions (Solve These — TCS Level)

> Try each one yourself before seeing the answer.

**Q1.** A number is increased by 15% and then decreased by 10%. Net % change?
```
Answer: = 15 − 10 + (15 × −10)/100 = 5 − 1.5 = 3.5% increase
```

**Q2.** After a 20% discount, a shirt costs ₹640. Original price?
```
Answer: = (640 × 100) / 80 = ₹800
```

**Q3.** Price of rice increases by 20%. By how much % must consumption be reduced to keep expenditure same?
```
Answer: = [20/120] × 100 = 16.67%
```

**Q4.** A scored 75% marks, B scored 50% marks. By what % is A's marks more than B?
```
Answer: Let max = 100. A = 75, B = 50. % more = [(75−50)/50] × 100 = 50%
```

**Q5.** In an election, winner got 55% votes and won by 60 votes. Find total votes.
```
Answer: Difference = 10% = 60 votes → Total = 600
```

**Q6.** A man spends 75% of his income. If income increases by 20% and expenditure by 10%, find % change in savings.
```
Answer: Let income = 400, expenditure = 300, savings = 100
New income = 480, new exp = 330, new savings = 150
% change = [(150−100)/100] × 100 = 50% increase
```

---

## 🗺 Concept Map

```
PERCENTAGES
│
├── BASICS
│   ├── % ↔ Fraction conversion
│   ├── % of a number
│   └── What % is A of B
│
├── CHANGE PROBLEMS
│   ├── % Increase / Decrease
│   ├── Reverse % (find original)
│   ├── Successive % change ⭐
│   └── % More / Less than ⭐
│
├── REAL-WORLD APPLICATIONS
│   ├── Income / Expenditure / Savings ⭐⭐
│   ├── Price × Consumption ⭐⭐
│   ├── Exam Marks (Pass/Fail) ⭐
│   ├── Election / Votes ⭐
│   └── Population Growth
│
└── DATA INTERPRETATION
    ├── % from tables
    ├── % from pie charts (degree → %)
    └── % change across years
```

---

## 🚨 Common Mistakes to NEVER Make in TCS

| Mistake | Correct Approach |
|---|---|
| After 10% up then 10% down = same value | It's **−1%** net. Never same. |
| Finding original by subtracting x% from final | Use `Original = Final × 100 / (100 ± x)` |
| Using wrong base for "% more / % less" | Always divide by the **reference value** (B) |
| 25% more ↔ 25% less are inverses | If A is 25% more than B, B is **20%** less than A |
| Adding % directly (30% + 20% = 50%) | Only valid if same base. Use successive formula. |

---

> **Next Topics to Study:** Profit & Loss (builds directly on Percentages) → then Simple Interest → then Compound Interest
> All three are just applied percentages. Master this sheet and the next 3 topics become very easy.


<img width="764" height="839" alt="image" src="https://github.com/user-attachments/assets/f967dfaa-5ba4-4635-a09e-d9bf54f07944" />
