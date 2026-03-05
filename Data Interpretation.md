# 📊 Data Interpretation — Complete TCS NQT Notes
> **Format:** Every concept has 🔵 Formula Method + 🟢 Manual Method
> **Exam Weight:** 2–3 questions | **Type:** Tables, Bar Graphs, Pie Charts, Line Graphs
> **Reality:** DI is NOT about maths. It's about reading fast and calculating smart.

---

## 🧠 What is DI in TCS NQT?

> You are given a **chart or table** with data. Then asked 2–4 questions based on it.
> The maths involved is just: percentages, averages, ratios, and basic arithmetic.
> The real skill is **reading the data correctly** and **not making silly errors**.

```
DI Question = Data Reading (60%) + Basic Calculation (40%)
```

---

## 📌 Types of DI That Appear in TCS NQT

| Type | Frequency | What It Looks Like |
|---|---|---|
| 📋 **Tables** | ⭐⭐⭐ Very High | Rows and columns of numbers |
| 📊 **Bar Graphs** | ⭐⭐⭐ Very High | Vertical or horizontal bars |
| 🥧 **Pie Charts** | ⭐⭐ High | Circle divided into sectors with % or degrees |
| 📈 **Line Graphs** | ⭐⭐ High | Points connected by lines showing trend |
| 🔀 **Mixed / Combo** | ⭐ Medium | Two charts together (e.g. table + pie) |

---

## 🔑 The 5 Calculation Types Asked in DI
> Every DI question is one of these 5. Nothing else.

| Type | What it Asks | Formula Needed |
|---|---|---|
| 1 | Find actual value | Direct reading |
| 2 | Find % of total | (Part / Total) × 100 |
| 3 | Find % change | (New − Old) / Old × 100 |
| 4 | Find ratio | A : B |
| 5 | Find average | Sum / Count |

> 💡 **You already know all 5 from Percentages notes. DI is just applying them on given data.**

---

## 1️⃣ Reading Tables

### 🔵 Formula Method
> Tables give raw data. Questions ask you to pick the right cells and apply formulas.

```
% of total   = (Row/Column value / Total) × 100
% change     = (New − Old) / Old × 100
Ratio        = Value A / Value B (simplified)
Average      = Sum of values / Number of values
```

---

### 🟢 Manual Method (How to Read a Table Without Errors)

```
Step 1: Read the TABLE TITLE first → tells you what the whole table is about
Step 2: Read ROW headers (left side) → what each row represents
Step 3: Read COLUMN headers (top) → what each column represents
Step 4: Find the TOTAL row/column → used as base for % questions
Step 5: Only then look at the specific cell the question asks about
```

> ⚠️ **The #1 DI mistake:** Jumping straight to numbers without reading headers.
> You'll pick the wrong row or wrong column and get the answer wrong with correct maths.

---

### 📋 Sample Table + Questions

**Table: Sales of 3 Products (in units) over 3 Years**

| Product | 2021 | 2022 | 2023 | Total |
|---|---|---|---|---|
| A | 200 | 300 | 400 | 900 |
| B | 150 | 250 | 350 | 750 |
| C | 100 | 200 | 250 | 550 |
| **Total** | **450** | **750** | **1000** | **2200** |

---

**Q1. What % of total sales in 2022 was Product B?**

🔵 Formula:
```
= (250 / 750) × 100 = 33.33% ✅
```
🟢 Manual:
```
250 out of 750 → simplify → 1/3 → 33.33% ✅
```

---

**Q2. What is the % increase in Product A's sales from 2021 to 2023?**

🔵 Formula:
```
= (400 − 200) / 200 × 100 = 200/200 × 100 = 100% ✅
```
🟢 Manual:
```
Changed from 200 to 400 → doubled → 100% increase ✅
```

---

**Q3. What is the ratio of Product B's 2022 sales to Product C's 2023 sales?**

```
= 250 : 250 = 1 : 1 ✅
```

---

**Q4. What is the average yearly sale of Product C?**

🔵 Formula:
```
= (100 + 200 + 250) / 3 = 550 / 3 = 183.33 ✅
```
🟢 Manual:
```
Sum = 550. Divide by 3. ≈ 183.3 ✅
```

---

## 2️⃣ Bar Graphs ⭐⭐⭐

### How to Read a Bar Graph
```
Step 1: Read X-axis label → what each bar represents (year, product, city etc.)
Step 2: Read Y-axis label → what is being measured (sales, marks, population etc.)
Step 3: Read Y-axis SCALE → is it in hundreds? thousands? millions?
Step 4: Estimate bar heights carefully using the gridlines
Step 5: Answer only uses what you read — don't assume values between gridlines
```

> ⚠️ **Scale trap:** Y-axis says "in thousands". Bar height = 5. Actual value = 5000. 
> Missing the scale multiplier is the most common mistake in bar graph DI.

---

### 📊 Sample Bar Graph Data + Questions

**Bar Graph: Monthly Revenue of a Company (in ₹ Lakhs)**

| Month | Revenue |
|---|---|
| Jan | 40 |
| Feb | 50 |
| Mar | 70 |
| Apr | 60 |
| May | 80 |
| Jun | 100 |

---

**Q1. Which month had the highest % increase over the previous month?**

🟢 Manual (Check each change):
```
Jan→Feb: +10 on 40 = 25%
Feb→Mar: +20 on 50 = 40%
Mar→Apr: −10 on 70 (decrease, skip)
Apr→May: +20 on 60 = 33.3%
May→Jun: +20 on 80 = 25%

Highest = Feb→Mar = 40% ✅
```

> 💡 **Trick:** Don't calculate every pair. First eliminate decreases. Then compare only increases. The largest absolute jump on a small base usually wins.

---

**Q2. What is the average monthly revenue for the 6 months?**

```
Sum = 40+50+70+60+80+100 = 400
Average = 400/6 = 66.67 lakhs ✅
```

---

**Q3. Revenue in Jun is what % more than revenue in Jan?**

```
Difference = 100 − 40 = 60
Base = Jan = 40
= (60/40) × 100 = 150% more ✅
```

---

## 3️⃣ Pie Charts ⭐⭐

### How to Read a Pie Chart

```
Pie chart gives data as:
  → Percentages (most common in TCS)
  → Degrees (sometimes)

If given %:   Actual value = (% / 100) × Total
If given °:   Convert first → % = (degrees / 360) × 100
              Then: Actual = (% / 100) × Total
```

---

### 🔵 Formula Method

```
Actual value from %     = (% / 100) × Total
Actual value from °     = (degrees / 360) × Total
% share of a sector     = (Actual / Total) × 100
Degrees of a sector     = (% / 100) × 360
```

---

### 🟢 Manual Method

**Key degree-to-% conversions to memorise:**

| Degrees | Percentage |
|---|---|
| 360° | 100% |
| 180° | 50% |
| 90° | 25% |
| 72° | 20% |
| 36° | 10% |
| 18° | 5% |
| 45° | 12.5% |
| 120° | 33.33% |

> 💡 **Quick trick:** % = Degrees ÷ 3.6 (since 360° = 100%, so 1° = 100/360 = 5/18%)

---

### 🥧 Sample Pie Chart Data + Questions

**Pie Chart: Budget Allocation of a Company (Total = ₹5,00,000)**

| Department | % Share |
|---|---|
| Marketing | 25% |
| Operations | 35% |
| HR | 15% |
| R&D | 20% |
| Admin | 5% |

---

**Q1. How much money is allocated to Operations?**

```
= (35/100) × 500000 = ₹1,75,000 ✅
```

---

**Q2. What is the ratio of Marketing to R&D budget?**

```
Marketing = 25%, R&D = 20%
Ratio = 25:20 = 5:4 ✅
```
> 💡 When total is same, ratio of % = ratio of actual values directly.

---

**Q3. HR and Admin together is what % of Marketing + R&D?**

```
HR + Admin     = 15 + 5  = 20%
Marketing + R&D = 25 + 20 = 45%
= (20/45) × 100 = 44.44% ✅
```

---

**Q4. If R&D sector is 72° in the pie chart, verify the %.**

```
= (72/360) × 100 = 20% ✅ (matches the table)
```

---

## 4️⃣ Line Graphs ⭐⭐

### How to Read a Line Graph

```
Step 1: X-axis = time (years, months, quarters)
Step 2: Y-axis = value being measured
Step 3: Each POINT = value at that time
Step 4: Slope going UP = increasing | Slope going DOWN = decreasing
Step 5: Questions usually ask for % change, max, min, or average
```

---

### 📈 Sample Line Graph Data + Questions

**Line Graph: Number of Students Enrolled in a College**

| Year | Students |
|---|---|
| 2018 | 800 |
| 2019 | 1000 |
| 2020 | 900 |
| 2021 | 1200 |
| 2022 | 1500 |

---

**Q1. In which year was there a decrease in enrollment?**

```
2018→2019: 800→1000 ↑
2019→2020: 1000→900 ↓ ← Answer: 2020 ✅
2020→2021: 900→1200 ↑
2021→2022: 1200→1500 ↑
```

---

**Q2. What is the % increase from 2020 to 2022?**

```
= (1500 − 900) / 900 × 100
= 600/900 × 100
= 66.67% ✅
```

---

**Q3. What is the average enrollment over 5 years?**

```
Sum = 800+1000+900+1200+1500 = 5400
Average = 5400/5 = 1080 ✅
```

---

## 5️⃣ Mixed / Combo DI ⭐

> Two data sources are given together. One question links data from both.

### 🟢 Strategy
```
Step 1: Read both charts separately first
Step 2: Understand what each one shows
Step 3: Identify what value from Chart 1 is needed for Chart 2
Step 4: Calculate step by step — never rush
```

**Example:**
> Table gives total company revenue per year.
> Pie chart gives % split of revenue across departments for one year.
> Question: "What is the actual revenue of Department A in 2022?"

```
Step 1: Get Total Revenue 2022 from Table → say ₹10,00,000
Step 2: Get % of Dept A from Pie chart → say 30%
Step 3: Actual = (30/100) × 1000000 = ₹3,00,000 ✅
```

---

## ⚡ DI Speed Tricks

| Situation | Trick |
|---|---|
| % change between two close values | Approximate: change/original ≈ rough % |
| Finding 33.33% of something | Divide by 3 |
| Finding 25% of something | Divide by 4 |
| Ratio comparison across bars | Don't calculate — just compare bar heights visually |
| Checking which is highest/lowest | Scan visually first, calculate only to confirm |
| Sum of all pie chart % | Must = 100. Use this to find missing % |
| Sum of all pie chart degrees | Must = 360. Use this to find missing degrees |

---

## 🧩 DI Question Types & Frequency in TCS NQT

| Question Type | Frequency | Difficulty | Tip |
|---|---|---|---|
| Find actual value from % / degrees | ⭐⭐⭐ Very High | Easy | Direct formula |
| % change between two years | ⭐⭐⭐ Very High | Easy | (New−Old)/Old × 100 |
| Which year had max/min increase | ⭐⭐⭐ Very High | Medium | Calculate each or approximate |
| Average of values | ⭐⭐ High | Easy | Sum ÷ Count |
| Ratio of two values | ⭐⭐ High | Easy | Simplify fraction |
| Combined two-chart question | ⭐⭐ High | Medium | Identify link between charts |
| % share of one item in total | ⭐⭐ High | Easy | Part/Total × 100 |

---

## 🔁 Practice Questions (TCS Level)

Use the table below:

**Table: Marks of 5 Students in 3 Subjects (out of 100 each)**

| Student | Maths | Science | English | Total |
|---|---|---|---|---|
| Arun | 80 | 70 | 60 | 210 |
| Bala | 60 | 80 | 75 | 215 |
| Charan | 90 | 65 | 85 | 240 |
| Dev | 55 | 90 | 70 | 215 |
| Eva | 75 | 60 | 80 | 215 |
| **Total** | **360** | **365** | **370** | **1095** |

---

**Q1.** What % of total marks did Charan score?
```
= (240 / (5×300)) × 100 = (240/1500) × 100 = 16% ✅
```

**Q2.** What is the average Maths score of all 5 students?
```
= 360 / 5 = 72 ✅
```

**Q3.** By what % are Charan's marks more than Arun's?
```
Difference = 240 − 210 = 30
Base = Arun = 210
= (30/210) × 100 = 14.28% ✅
```

**Q4.** What is the ratio of Science total to English total?
```
= 365 : 370 = 73 : 74 ✅
```

**Q5.** In Maths, Dev's marks are what % less than Charan's?
```
Difference = 90 − 55 = 35
Base = Charan = 90
= (35/90) × 100 = 38.89% ✅
```

---

## 🗺 Concept Map

```
DATA INTERPRETATION
│
├── TYPES OF CHARTS
│   ├── Table       → rows × columns, find cell + calculate
│   ├── Bar Graph   → read Y-axis scale, compare bar heights
│   ├── Pie Chart   → % or degrees → actual values
│   ├── Line Graph  → trend over time, % change between points
│   └── Mixed/Combo → link two charts using one common value
│
├── CALCULATION TYPES (only 5 ever asked)
│   ├── Actual value     → direct read or (% × total)/100
│   ├── % of total       → (part/total) × 100
│   ├── % change         → (new−old)/old × 100
│   ├── Ratio            → A:B simplified
│   └── Average          → sum / count
│
├── READING STRATEGY
│   ├── Title → Row headers → Column headers → Scale → THEN numbers
│   └── Never pick a number before understanding what it represents
│
└── COMMON TRAPS
    ├── Y-axis scale (÷1000, ÷ lakh etc.)
    ├── Wrong base in % change (use OLD as base)
    ├── Degrees vs % in pie chart
    └── Misreading row vs column
```

---

## 🚨 Common Mistakes — Never Make These in TCS

| Wrong Approach | Correct Approach |
|---|---|
| Ignoring Y-axis scale | Always check: "in thousands?" "in lakhs?" Multiply accordingly |
| Using new value as base for % change | Base is always the **OLD / original** value |
| Using degrees directly as % | Convert first: % = (degrees/360) × 100 |
| Rushing to calculate before reading chart | Read title → headers → scale → then calculate |
| Calculating all options when asked "which is highest" | Scan visually first. Only calculate 2–3 close ones. |
| Adding % across different totals | Only add % if the total base is the same |

---

## 🧠 The One Mental Model Behind DI

```
DI is NOT a maths test. It's a reading + calculation test.

The maths is always one of: %, change%, ratio, average.
You already know all of these.

The real question is:
"Are you reading the right number from the right place?"

So your process should always be:
  Read → Identify → Calculate → Verify unit

Never:
  Calculate → then try to match to the chart
```

> 💡 In the exam, spend **30 seconds reading the chart before touching any question.**
> That 30 seconds will save you from 2–3 wrong answers.

---
