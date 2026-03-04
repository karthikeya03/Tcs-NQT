# 📊 Percentages — Complete TCS NQT Notes
> **Your Status:** Concepts 1–3 done ✅ | Every concept has **Formula Method + Manual Method**

---

## ✅ What You Already Know

| # | Concept | Formula |
|---|---|---|
| 1 | % → Fraction | Divide by 100 → `x% = x/100` |
| 2 | Fraction → % | Multiply by 100 → `(a/b) × 100` |
| 3 | Increase/Decrease by x% | New = Original × `(100 ± x) / 100` |

---

## 📌 Must-Know Fraction ↔ Percentage Table
> **Memorise this. Saves 20–30 seconds per question.**

| Fraction | Percentage | Fraction | Percentage |
|---|---|---|---|
| 1/2 | **50%** | 1/9 | **11.11%** |
| 1/3 | **33.33%** | 1/10 | **10%** |
| 1/4 | **25%** | 1/11 | **9.09%** |
| 1/5 | **20%** | 1/12 | **8.33%** |
| 1/6 | **16.67%** | 2/3 | **66.67%** |
| 1/7 | **14.28%** | 3/4 | **75%** |
| 1/8 | **12.5%** | 3/5 | **60%** |

---

## 4️⃣ Percentage of a Number

### 🔵 Formula Method
```
x% of N = (x / 100) × N
```
> What is 35% of 480?
```
= (35/100) × 480 = 35 × 4.8 = 168 ✅
```

---

### 🟢 Manual Method (No Formula — Breaking Trick)
> You already use this instinctively. Just build 10% first, then add up.

```
Step 1: Find 10% of 480 → move decimal left → 48
Step 2: 30% = 3 × 48 = 144
Step 3: 5% = half of 10% = 24
Step 4: 35% = 30% + 5% = 144 + 24 = 168 ✅
```

> 💡 **Break ANY ugly % into 10% + 5% + 1% chunks. Always works.**

| Need | How to Get It |
|---|---|
| 10% | Move decimal left once |
| 5% | Half of 10% |
| 1% | Move decimal left twice |
| 20% | Double of 10% |
| 25% | Divide by 4 |
| 50% | Divide by 2 |
| 15% | 10% + 5% |
| 35% | 30% + 5% |
| 12% | 10% + 2% (2 × 1%) |

---

## 5️⃣ What Percent is A of B?

### 🔵 Formula Method
```
(A / B) × 100
```
> 45 is what % of 180?
```
= (45/180) × 100 = (1/4) × 100 = 25% ✅
```

---

### 🟢 Manual Method
> Think of it as: **"A is how many parts out of B total? Scale that to 100."**

```
Step 1: Write as a fraction → 45/180
Step 2: Simplify → 1/4
Step 3: 1/4 means 1 out of 4 parts
Step 4: If total is 100, then 1 part = 25
→ Answer = 25% ✅
```

> 💡 **Simplify the fraction first, THEN convert. Never multiply big numbers.**

---

## 6️⃣ Finding the Original Number (Reverse Percentage) ⭐⭐⭐

### 🔵 Formula Method
```
Original = (Final Value × 100) / (100 ± x)
```
> After 20% increase, number becomes 480. Original?
```
= (480 × 100) / 120 = 400 ✅
```
> After 25% decrease, number becomes 600. Original?
```
= (600 × 100) / 75 = 800 ✅
```

---

### 🟢 Manual Method (Unitary / Parts Method)
> Think of original as 100 parts. After x% change, it becomes (100 ± x) parts. You know the final. Scale back.

**Example — 20% Increase:**
```
Original = 100 parts
After 20% increase = 120 parts = 480 (given)

So 120 parts = 480
→ 1 part = 480 / 120 = 4
→ 100 parts = 4 × 100 = 400 ✅
```

**Example — 25% Decrease:**
```
Original = 100 parts
After 25% decrease = 75 parts = 600 (given)

So 75 parts = 600
→ 1 part = 600 / 75 = 8
→ 100 parts = 8 × 100 = 800 ✅
```

> ⚠️ **The Classic Wrong Approach (Never Do This):**
> "20% of 480 = 96, so original = 480 − 96 = 384" ❌ WRONG
> The 20% was on the ORIGINAL, not the final. The parts method above makes this crystal clear.

---

## 7️⃣ Percentage Change

### 🔵 Formula Method
```
% Change = [(New − Old) / Old] × 100
```
> Price went from ₹400 to ₹520. % increase?
```
= [(520 − 400) / 400] × 100 = [120/400] × 100 = 30% ✅
```

---

### 🟢 Manual Method
> Find how much it changed → express that as a fraction of original → convert to %

```
Step 1: Change = 520 − 400 = 120
Step 2: "120 is what fraction of 400?"
         → 120/400 = 3/10
Step 3: 3/10 = 30% ✅
```

> 💡 **Simplify the fraction first using the fraction table.** If it's 1/4 you already know it's 25%.

---

## 8️⃣ Successive Percentage Change ⭐⭐

### 🔵 Formula Method
```
Net % Change = x + y + (xy / 100)
```
Use + for increase, − for decrease

> 20% increase then 10% increase:
```
= 20 + 10 + (20×10)/100 = 30 + 2 = 32% ✅
```
> 30% increase then 20% decrease:
```
= 30 + (−20) + (30×−20)/100 = 10 − 6 = 4% increase ✅
```
> 10% decrease then 10% decrease:
```
= −10 + (−10) + (−10×−10)/100 = −20 + 1 = −19% ✅
```

---

### 🟢 Manual Method (Assume 100, Apply Changes Step by Step)
> Forget the formula entirely. Just take 100 and apply the percentages one by one.

**Example — 20% increase then 10% increase:**
```
Start:           100
After 20% up:    100 + 20 = 120
After 10% up:    120 + 12 = 132

Net change = 132 − 100 = 32 → 32% increase ✅
```

**Example — 30% increase then 20% decrease:**
```
Start:           100
After 30% up:    100 + 30 = 130
After 20% down:  130 − 26 = 104

Net change = 104 − 100 = 4 → 4% increase ✅
```

**Example — 10% down then 10% down:**
```
Start:           100
After 10% down:  100 − 10 = 90
After 10% down:  90 − 9 = 81

Net change = 81 − 100 = −19 → 19% decrease ✅
```

> 💡 **This manual method is actually FASTER than the formula** once you get used to it.
> It also works for 3 successive changes — formula gets messy, this stays clean.

> **TCS Favourite Trap:** "10% up then 10% down = same?" → **NO → always −1%**
```
100 → 110 → 99 → Lost 1 → 1% loss ✅
```

---

## 9️⃣ Percentage More Than / Less Than ⭐⭐

### 🔵 Formula Method
```
A is what % MORE than B?  = [(A − B) / B] × 100   (base = B)
A is what % LESS than B?  = [(B − A) / B] × 100   (base = B)
```

---

### 🟢 Manual Method (What You Learned — Difference ÷ Base)
> No formula needed. Just 3 steps:

```
Step 1: Find the Difference = Bigger − Smaller
Step 2: Identify the Base (who is being compared AGAINST)
Step 3: Percentage = (Difference / Base) × 100
```

**Example: A = 800, B = 1000**

*A is what % less than B?*
```
Difference = 1000 − 800 = 200
Base = B = 1000 (comparing against B)
= 200/1000 = 0.2 = 20% ✅
```

*B is what % more than A?*
```
Difference = 1000 − 800 = 200
Base = A = 800 (comparing against A)
= 200/800 = 0.25 = 25% ✅
```

> ⚠️ **Key Insight — The Reverse Trap:**
> If A is **25% more** than B → B is **NOT 25% less** than A
> Let A = 125, B = 100
> B is less than A by: 25/125 × 100 = **20%** ← different number, different base

| Statement | Base Used |
|---|---|
| X is more than Y | Y is base |
| X is less than Y | Y is base |
| X is more than Z by 30% | Z is base |
> 💡 **Simple Rule: The base is always the thing AFTER the word "than".**

---

## 🔟 Population / Price Growth Formula ⭐

### 🔵 Formula Method
```
Final Value = Initial Value × (1 ± r/100)^n
```
> Population 2,00,000 grows at 5% per year. After 2 years?
```
= 200000 × (1.05)² = 200000 × 1.1025 = 2,20,500 ✅
```

---

### 🟢 Manual Method (Apply % Year by Year)
> Only practical for n = 2. For n = 3+ use the formula.

```
Year 0: 2,00,000
Year 1: 200000 + 5% of 200000 = 200000 + 10000 = 2,10,000
Year 2: 210000 + 5% of 210000 = 210000 + 10500 = 2,20,500 ✅
```

> 💡 This is identical to Compound Interest. Learn once, apply everywhere.

---

## 1️⃣1️⃣ Income / Expenditure / Savings Type ⭐⭐⭐

### 🔵 Formula Method
> No clean formula — always use assumed values. See manual method below.

---

### 🟢 Manual Method (Assume Numbers — Always Use This)
> **Never use variables (algebra) for this type. Assume numbers and work with them.**

**Example:**
> Income increases by 20%, expenditure by 10%. Originally income = ₹500, expenditure = ₹400. Find % change in savings.

```
Step 1: Savings = 500 − 400 = 100

Step 2: New income     = 500 × 1.20 = 600
        New expenditure = 400 × 1.10 = 440
        New savings     = 600 − 440  = 160

Step 3: % change = [(160 − 100) / 100] × 100 = 60% increase ✅
```

> 💡 **What numbers to assume?**
> If the question gives spending % of income (e.g. "spends 75%"), then:
> - Let income = 400, expenditure = 300, savings = 100
> - Choose numbers where savings is a round 100 — makes % calculation trivial

**Example with %:**
> A man spends 75% of his income. Income increases by 20%, expenditure by 10%. % change in savings?
```
Let income = 400 (so 75% = 300 is easy)
Expenditure = 300, Savings = 100

New income      = 400 × 1.20 = 480
New expenditure = 300 × 1.10 = 330
New savings     = 480 − 330  = 150

% change = [(150−100)/100] × 100 = 50% increase ✅
```

---

## 1️⃣2️⃣ Price × Consumption = Expenditure Type ⭐⭐

### 🔵 Formula Method
```
Price increases by x% → Reduce consumption by: [x / (100 + x)] × 100
Price decreases by x% → Increase consumption by: [x / (100 − x)] × 100
```
> Price up 25% → reduce by [25/125] × 100 = 20% ✅
> Price down 20% → increase by [20/80] × 100 = 25% ✅

---

### 🟢 Manual Method (Fix Expenditure, Find New Consumption)
> Keep expenditure constant. Adjust consumption.

**Example — Price increases by 25%:**
```
Let original price = 100, original consumption = 100
Original expenditure = 100 × 100 = 10000

New price = 125 (25% more)
New consumption = 10000 / 125 = 80

Reduction = 100 − 80 = 20
% reduction = (20/100) × 100 = 20% ✅
```

**Example — Price decreases by 20%:**
```
Let original price = 100, consumption = 100
Expenditure = 10000

New price = 80
New consumption = 10000 / 80 = 125

Increase = 125 − 100 = 25
% increase = (25/100) × 100 = 25% ✅
```

> 💡 **Memory Hook:** Price and consumption are inversely related (like a seesaw).
> Price goes UP → consumption must come DOWN to keep expenditure flat.
> Price goes DOWN → consumption can go UP.

---

## 1️⃣3️⃣ Marks / Exam Percentage Type ⭐

### 🔵 Formula Method
```
Pass/Fail: (Pass% − Student%) × Max = Marks difference
Max = Marks difference / (Pass% − Student%) × 100
```

---

### 🟢 Manual Method (Think in Parts)

**Type — Pass/Fail:**
> Scored 30%, failed by 20 marks. Pass % = 40%.
```
Student got    = 30% of Max
Pass marks     = 40% of Max
Gap between them = 10% of Max = 20 marks

Think: 10 parts out of 100 = 20 marks
       So 1 part = 2
       100 parts = 200

Max marks = 200 ✅
```

**Type — Two Student Comparison:**
> A scored 40%, B scored 60%. B got 30 more marks. Find max.
```
Difference = 60% − 40% = 20% of Max = 30 marks
So 20 parts = 30 → 1 part = 1.5 → 100 parts = 150

Max marks = 150 ✅
```

---

## 1️⃣4️⃣ Election / Votes Type ⭐

### 🟢 Manual Method (Parts Method — Same Logic as Above)
> In an election, winner got 60% and won by 240 votes.
```
Winner = 60%, Loser = 40%
Difference = 20% of Total = 240 votes

20 parts = 240
1 part = 12
100 parts = 1200

Total votes = 1200 ✅
```

> 💡 **This is the same unitary/parts thinking used in reverse percentage, exam type, and here.** Once you get this thinking, all 3 types become one type.

---

## 1️⃣5️⃣ Data Interpretation with Percentages

### Key Conversions

```
Actual Value from %    = (% / 100) × Total
% share of a part      = (Part / Total) × 100
% change across years  = [(New − Old) / Old] × 100
Pie chart sector → %   = (Degrees / 360) × 100
```

**Pie chart example:**
> Sector = 72°
```
= (72/360) × 100 = 20% ✅
```

### 🟢 Manual for DI % Change
```
Year 1 value = 400, Year 2 value = 500
Change = 100
100 out of 400 = 1/4 = 25% increase ✅
```
> Simplify the fraction first before converting. Always faster.

---

## ⚡ Speed Tricks Summary

| Trick | Method |
|---|---|
| 10% of N | Move decimal one place left |
| 5% of N | Half of 10% |
| 1% of N | Move decimal two places left |
| 25% of N | Divide by 4 |
| 50% of N | Divide by 2 |
| 33.33% of N | Divide by 3 |
| 12.5% of N | Divide by 8 |
| 37% of N | = (30% + 5% + 2%) of N |

---

## 🧩 TCS NQT — Question Types & Frequency

| Question Type | Frequency | Difficulty | Best Method |
|---|---|---|---|
| Reverse % (find original) | ⭐⭐⭐ Very High | Easy | Parts method |
| Successive % change | ⭐⭐⭐ Very High | Easy | Assume 100, apply steps |
| Income / Expenditure / Savings | ⭐⭐⭐ Very High | Medium | Assume values |
| Price × Consumption | ⭐⭐ High | Medium | Fix expenditure |
| Exam marks (pass/fail) | ⭐⭐ High | Easy | Parts method |
| % more / % less than | ⭐⭐ High | Easy | Difference ÷ Base |
| Election / Votes | ⭐ Medium | Easy | Parts method |
| Population growth | ⭐ Medium | Medium | Year-by-year or formula |

---

## 🔁 Practice Questions (TCS Level)

**Q1.** A number is increased by 15%, then decreased by 10%. Net % change?
```
Manual: 100 → +15% → 115 → −10% → 115 − 11.5 = 103.5
Net = 3.5% increase ✅
```

**Q2.** After 20% discount, a shirt costs ₹640. Original price?
```
Parts: 80 parts = 640 → 1 part = 8 → 100 parts = 800
Original = ₹800 ✅
```

**Q3.** Price of rice up 20%. By what % should consumption reduce to keep expenditure same?
```
Fix expenditure = 10000. New price = 120.
New consumption = 10000/120 = 83.33
Reduction = 16.67% ✅
```

**Q4.** A scored 75%, B scored 50%. By what % is A's marks more than B?
```
Difference = 25. Base = B = 50.
25/50 = 1/2 = 50% ✅
```

**Q5.** Winner got 55% of votes and won by 60 votes. Total votes?
```
Difference = 10% = 60 → 1% = 6 → 100% = 600 ✅
```

**Q6.** Man spends 75% of income. Income up 20%, expenditure up 10%. % change in savings?
```
Income = 400, Expenditure = 300, Savings = 100
New income = 480, New exp = 330, New savings = 150
% change = 50% increase ✅
```

---

## 🗺 Concept Map

```
PERCENTAGES
│
├── BASICS
│   ├── % ↔ Fraction conversion
│   ├── % of a number (breaking method)
│   └── What % is A of B (simplify fraction first)
│
├── CHANGE PROBLEMS
│   ├── % Increase / Decrease (change ÷ original)
│   ├── Reverse % — Parts Method ⭐
│   ├── Successive % — Assume 100 Method ⭐
│   └── % More / Less — Difference ÷ Base ⭐
│
├── REAL-WORLD APPLICATIONS
│   ├── Income / Expenditure / Savings — Assume Values ⭐⭐
│   ├── Price × Consumption — Fix Expenditure ⭐⭐
│   ├── Exam Marks Pass/Fail — Parts Method ⭐
│   ├── Election / Votes — Parts Method ⭐
│   └── Population Growth — Year by Year
│
└── DATA INTERPRETATION
    ├── % from tables
    ├── % from pie charts (degrees ÷ 360 × 100)
    └── % change across years
```

---

## 🚨 Common Mistakes — Never Make These in TCS

| Wrong Approach | Correct Approach |
|---|---|
| 10% up then 10% down = same | 100 → 110 → 99 → **−1% loss** always |
| Finding original by subtracting x% from final | Use parts method: (100 ± x) parts = Final |
| Adding successive % directly | Assume 100, apply step by step |
| Using wrong base for % more/less | Base = the word AFTER "than" |
| 25% more ↔ 25% less are inverses | If A is 25% more than B → B is **20%** less than A |

---

## 🧠 The One Mental Model Behind Everything

> Once you see this, all percentage problems become easy.

```
Think of ORIGINAL as 100 parts.

After x% increase  → it becomes (100 + x) parts
After x% decrease  → it becomes (100 − x) parts

You are always given one value and asked for another.
Use unitary method: find 1 part, then scale.
```

> This single idea solves: Reverse %, Election, Exam Marks, Income/Savings — all of them.

---

> **Next:** Profit & Loss — it's just Percentages applied to buying and selling. 
> Every formula in P&L is derived from what you just learned here.
