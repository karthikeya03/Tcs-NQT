# ⚙️ Time & Work + Pipes & Cisterns — Complete TCS NQT Notes
> **Format:** Every concept has 🔵 Formula Method + 🟢 Manual Method
> **Exam Weight:** 1–2 questions | **Difficulty:** Easy–Medium
> **Reality:** Every T&W question becomes trivial once you use the LCM method.

---

## 🧠 The Core Idea — Understand This First

```
Work is always ONE complete job = 1 unit of work.

If A finishes a job in N days → A does 1/N work per day.

Work Done = Rate × Time
         = (1/N) × T
```

> This is identical to D = S × T from TSD.
> Work = Distance, Rate = Speed, Time = Time.
> Same triangle. Different words.

```
        [ W = 1 ]
       ──────────
      [ R  ×  T ]
```

---

## 📌 Two Methods for Every T&W Problem

| Method | When to Use |
|---|---|
| 🔵 **Fraction Method** | Simple 1–2 person problems |
| 🟢 **LCM Method** | ANY problem. Always faster. Always safer. |

> 💡 **Master the LCM method. It handles 100% of T&W and Pipes questions without fractions.**

---

## 1️⃣ One Person Working Alone

### 🔵 Fraction Method
```
Rate = 1/N (work per day)
Time to finish = N days
```
> A finishes a job in 12 days. How much does A do in 4 days?
```
Rate = 1/12 per day
Work in 4 days = 4 × 1/12 = 1/3 of the job ✅
```

---

### 🟢 LCM Method
> Assign total work = N (convenient number). Rate = whole number.

> A finishes a job in 12 days.
```
Total work = 12 units
A's rate   = 12/12 = 1 unit/day

Work in 4 days = 4 × 1 = 4 units
Fraction done  = 4/12 = 1/3 ✅
```

> 💡 With one person, LCM = their own days. With two or more, LCM = LCM of all their days.

---

## 2️⃣ Two People Working Together ⭐⭐⭐

### 🔵 Fraction Method
```
Combined Rate = 1/A + 1/B
Time together = 1 / (1/A + 1/B) = AB / (A+B)
```
> A finishes in 6 days, B in 12 days. Together?
```
= (6 × 12) / (6 + 12) = 72/18 = 4 days ✅
```

---

### 🟢 LCM Method (Much Cleaner)

```
Step 1: Total work = LCM(6, 12) = 12 units

Step 2: A's rate = 12/6  = 2 units/day
        B's rate = 12/12 = 1 unit/day

Step 3: Combined rate = 2 + 1 = 3 units/day

Step 4: Time = 12/3 = 4 days ✅
```

> 💡 **Why LCM works:** LCM makes every day's work a whole number. No fractions. No errors.

---

## 3️⃣ Three People Working Together ⭐

### 🟢 LCM Method
> A in 4 days, B in 6 days, C in 12 days. Together?
```
Total work = LCM(4, 6, 12) = 12 units

A's rate = 12/4  = 3 units/day
B's rate = 12/6  = 2 units/day
C's rate = 12/12 = 1 unit/day

Combined = 3 + 2 + 1 = 6 units/day
Time     = 12/6 = 2 days ✅
```

---

## 4️⃣ One Person Leaves Early / Joins Late ⭐⭐⭐

### Classic TCS Pattern:
> A and B work together. After X days, one of them leaves. Find total time.

### 🟢 LCM Method

**Example:**
> A finishes in 10 days, B in 15 days. They work together for 4 days, then A leaves. How many more days for B to finish?

```
Step 1: Total work = LCM(10, 15) = 30 units

Step 2: A's rate = 30/10 = 3 units/day
        B's rate = 30/15 = 2 units/day

Step 3: Work done together in 4 days = (3+2) × 4 = 20 units

Step 4: Remaining work = 30 − 20 = 10 units

Step 5: B finishes alone at 2 units/day
        Time = 10/2 = 5 more days ✅
```

---

### 🔵 Fraction Method
```
Work done in 4 days = 4 × (1/10 + 1/15) = 4 × 5/30 = 2/3
Remaining = 1 − 2/3 = 1/3
B alone: (1/3) ÷ (1/15) = 5 days ✅
```

---

## 5️⃣ Finding When One Person Did How Much Work ⭐⭐

### Classic Pattern:
> A and B together do a job in X days. A alone takes Y days. B alone takes?

### 🔵 Fraction Method
```
1/B = 1/Together − 1/A
```

> Together = 6 days, A alone = 10 days. B alone?
```
1/B = 1/6 − 1/10 = 5/30 − 3/30 = 2/30 = 1/15
B alone = 15 days ✅
```

---

### 🟢 LCM Method
```
Total work = LCM(6, 10) = 30 units

Together rate  = 30/6  = 5 units/day
A's rate       = 30/10 = 3 units/day

B's rate = 5 − 3 = 2 units/day
B alone  = 30/2 = 15 days ✅
```

---

## 6️⃣ Efficiency / More or Less Efficient ⭐

### Classic Pattern:
> A is twice as efficient as B. A takes 10 days. B takes?

### 🟢 LCM Method
```
A is 2× efficient → A does 2 units for every 1 unit B does

If A takes 10 days:
  A's rate = 2 units/day → Total work = 20 units
  B's rate = 1 unit/day  → B takes 20 days ✅
```

### 🔵 Fraction Method
```
A = 2B in efficiency
If A takes 10 days, B takes 10 × 2 = 20 days ✅
```

> 💡 **More efficient → Less time. Less efficient → More time.**
> Efficiency and time are inversely proportional (like Speed and Time in TSD).

---

## 7️⃣ Work Done in Alternate Days ⭐⭐

### Classic Pattern:
> A and B work on alternate days. A starts first. How long to finish?

### 🟢 LCM Method

**Example:**
> A finishes in 6 days, B in 12 days. They work on alternate days, A starts.

```
Total work = LCM(6, 12) = 12 units

A's rate = 2 units/day
B's rate = 1 unit/day

Every 2-day cycle: A + B = 3 units

Cycles to finish: 12/3 = 4 cycles = 8 days ✅
```

**If it doesn't divide evenly:**
> A = 4 days, B = 6 days. Alternate, A starts.
```
Total work = LCM(4, 6) = 12 units
A's rate = 3, B's rate = 2

Per 2-day cycle = 5 units
After 2 cycles (4 days) = 10 units done
Remaining = 2 units → A's turn → A does 3/day → needs 2/3 day

Total = 4 + 2/3 days ✅
```

---

## 8️⃣ Wages / Payment Distribution ⭐

### Classic Pattern:
> A and B work together. Total wages = ₹X. Split based on work done.

### 🟢 LCM Method + Ratio

**Example:**
> A finishes in 10 days, B in 15 days. They work together. Total wages = ₹1000. How much does each get?

```
Total work = LCM(10, 15) = 30 units

A's rate = 3 units/day
B's rate = 2 units/day

Ratio of work = 3:2

A gets = (3/5) × 1000 = ₹600
B gets = (2/5) × 1000 = ₹400 ✅
```

> 💡 Wages are split in the RATIO of work done (= ratio of rates when working for same time).

---

## 9️⃣ Part of Work Completed ⭐⭐

### Classic Pattern:
> A can do a job in X days. He works for Y days and leaves. What fraction is done / remaining?

### 🟢 LCM Method

**Example:**
> A finishes a job in 20 days. He works for 8 days, then leaves. B finishes the rest in 6 days. B alone can finish in?
```
Total work = 20 units (set = A's days for simplicity)
A's rate   = 1 unit/day
Work done by A in 8 days = 8 units
Remaining  = 20 − 8 = 12 units

B finishes 12 units in 6 days → B's rate = 2 units/day
B alone = 20/2 = 10 days ✅
```

---

## 🔟 Man-Days Concept ⭐⭐

> Used when number of workers changes.

```
Work = Men × Days × Hours/day

M1 × D1 = M2 × D2  (if work is same)
```

**Example:**
> 6 men finish a job in 8 days. How many days for 4 men?
```
6 × 8 = 4 × D2
D2 = 48/4 = 12 days ✅
```

**Extended version:**
> 10 men, 6 hours/day, finish in 12 days.
> How many days for 8 men working 9 hours/day?
```
M1 × D1 × H1 = M2 × D2 × H2
10 × 12 × 6  = 8 × D2 × 9
720 = 72 × D2
D2 = 10 days ✅
```

---

## 🚰 Pipes & Cisterns ⭐⭐⭐

> Pipes & Cisterns = Time & Work in disguise.
> Filling a tank = doing positive work.
> Draining/emptying = doing negative work (leak).

```
Inlet pipe  → fills tank  → POSITIVE rate  (+)
Outlet pipe → drains tank → NEGATIVE rate  (−)
```

---

### 1️⃣1️⃣ One Pipe Filling

> Pipe A fills a tank in 6 hours. Part filled in 2 hours?
```
Rate = 1/6 per hour
In 2 hours = 2/6 = 1/3 ✅

LCM: Total = 6 units. Rate = 1 unit/hr. In 2 hrs = 2 units = 2/6 = 1/3 ✅
```

---

### 1️⃣2️⃣ Two Pipes — One Filling, One Draining ⭐⭐⭐

**Example:**
> Pipe A fills in 6 hours, Pipe B drains in 12 hours. Both open. Time to fill?

### 🟢 LCM Method
```
Total work = LCM(6, 12) = 12 units

A's rate = +12/6  = +2 units/hr  (filling)
B's rate = −12/12 = −1 unit/hr   (draining)

Net rate = 2 − 1 = 1 unit/hr

Time to fill = 12/1 = 12 hours ✅
```

---

### 1️⃣3️⃣ Two Filling Pipes + One Drain ⭐⭐

**Example:**
> A fills in 4h, B fills in 6h, C drains in 8h. All open. Time to fill?

### 🟢 LCM Method
```
Total work = LCM(4, 6, 8) = 24 units

A = +24/4 = +6 units/hr
B = +24/6 = +4 units/hr
C = −24/8 = −3 units/hr

Net rate = 6 + 4 − 3 = 7 units/hr

Time = 24/7 = 3.43 hours ✅
```

---

### 1️⃣4️⃣ Tank Partially Filled + Pipe Opened ⭐

**Example:**
> Tank is 1/4 full. Pipe A fills in 12 hours. How long to fill the rest?
```
Remaining = 3/4 of tank
Rate of A  = 1/12 per hour

Time = (3/4) ÷ (1/12) = (3/4) × 12 = 9 hours ✅

LCM: Total = 12 units. A's rate = 1/hr.
Remaining = 9 units. Time = 9 hours ✅
```

---

### 1️⃣5️⃣ Leak Problem ⭐⭐⭐

**Classic TCS Pattern:**
> A pipe fills a tank in X hours. Due to a leak, it takes Y hours. Time for leak to empty full tank?

### 🔵 Formula Method
```
1/Leak = 1/X − 1/Y
```

**Example:**
> Fills in 6 hours normally. With leak, takes 8 hours. Leak empties in?
```
1/Leak = 1/6 − 1/8 = 4/24 − 3/24 = 1/24
Leak empties in 24 hours ✅
```

---

### 🟢 LCM Method
```
Total work = LCM(6, 8) = 24 units

Without leak: rate = 24/6 = 4 units/hr
With leak:    rate = 24/8 = 3 units/hr (slower due to leak)

Leak removes: 4 − 3 = 1 unit/hr
Leak alone empties 24 units in 24 hours ✅
```

---

### 1️⃣6️⃣ Pipe Opened for Part of Time ⭐

**Example:**
> A fills in 4h, B fills in 6h. A is open for full time, B only for 2 hours. Total time to fill?

### 🟢 LCM Method
```
Total = LCM(4, 6) = 12 units
A's rate = 3 units/hr
B's rate = 2 units/hr

B works for 2 hours: does 2 × 2 = 4 units
Remaining for A alone: 12 − 4 = 8 units
A's time for 8 units: 8/3 hours

But A also worked during B's 2 hours:
Total time = t hours
Work by A = 3t
Work by B = 2 × 2 = 4 (only 2 hours)
3t + 4 = 12
3t = 8
t = 8/3 hours

Wait — re-read: A open full time, B open for first 2 hours.
Work = 3t + 4 = 12 → t = 8/3 hours ✅
```

---

## ⚡ Key LCM Trick Table

| People / Pipes | Set Total Work = |
|---|---|
| A (alone: N days) | N |
| A and B | LCM(A's days, B's days) |
| A, B and C | LCM(A, B, C) |
| Inlet X hours, Outlet Y hours | LCM(X, Y) |

---

## 🧩 TCS NQT — Question Types & Frequency

| Question Type | Frequency | Difficulty | Method |
|---|---|---|---|
| Two people together | ⭐⭐⭐ Very High | Easy | LCM method |
| One leaves early / joins late | ⭐⭐⭐ Very High | Medium | LCM — subtract work done |
| Find B alone given together + A | ⭐⭐ High | Easy | LCM — subtract rates |
| Leak problem | ⭐⭐⭐ Very High | Medium | LCM — subtract rates |
| Two pipes one draining | ⭐⭐ High | Easy | LCM with negative rate |
| Wages / payment split | ⭐⭐ High | Medium | Ratio of rates |
| Alternate days | ⭐⭐ High | Medium | Per-cycle calculation |
| Man-days | ⭐ Medium | Easy | M×D = constant |

---

## 🔁 Practice Questions (TCS Level)

**Q1.** A in 12 days, B in 18 days. Together?
```
LCM = 36. A = 3/day, B = 2/day. Together = 5/day.
Time = 36/5 = 7.2 days ✅
```

**Q2.** A in 10 days, B in 15 days. Work together for 3 days. A leaves. B finishes alone in?
```
LCM = 30. A = 3, B = 2. In 3 days together = 15 units.
Remaining = 15. B's rate = 2. Time = 15/2 = 7.5 days ✅
```

**Q3.** Together in 8 days, A alone in 12 days. B alone in?
```
LCM = 24. Together = 3/day. A = 2/day. B = 1/day.
B alone = 24 days ✅
```

**Q4.** A fills in 5h, B drains in 20h. Both open. Fill time?
```
LCM = 20. A = +4, B = −1. Net = 3 units/hr.
Time = 20/3 = 6.67 hours ✅
```

**Q5.** Pipe fills in 10h. Leak empties in 15h. Net time to fill?
```
LCM = 30. Fill = 3/hr, Leak = −2/hr. Net = 1/hr.
Time = 30 hours ✅
```

**Q6.** 8 men do a job in 9 days. How many men for 6 days?
```
8 × 9 = M × 6 → M = 12 men ✅
```

**Q7.** A is 3× efficient as B. Together they finish in 6 days. B alone?
```
A's rate = 3x, B's rate = x. Together = 4x.
4x → 6 days → Total work = 24x units.
B alone = 24x/x = 24 days ✅
```

**Q8.** A in 6 days, B in 12 days. Alternate days, A starts. Total time?
```
LCM = 12. A = 2/day, B = 1/day.
Per 2-day cycle = 3 units. 12/3 = 4 cycles = 8 days ✅
```

---

## 🗺 Concept Map

```
TIME & WORK + PIPES & CISTERNS
│
├── CORE IDEA
│   ├── Work = Rate × Time
│   ├── Rate = 1/N (fraction method)
│   └── Rate = LCM/N (LCM method) ← USE THIS
│
├── BASIC TYPES
│   ├── One person alone
│   ├── Two/three together → LCM, add rates ⭐
│   └── Find one person given together + other
│
├── INTERMEDIATE TYPES
│   ├── One leaves early → work done + remaining ⭐⭐
│   ├── Alternate days → per cycle calculation ⭐
│   ├── Part work done, find rest ⭐
│   └── Wages → split by rate ratio ⭐
│
├── EFFICIENCY / MAN-DAYS
│   ├── Efficiency ∝ 1/Time
│   └── M × D × H = constant ⭐
│
└── PIPES & CISTERNS
    ├── Inlet = positive rate (+)
    ├── Outlet/Leak = negative rate (−) ⭐⭐
    ├── Net rate = sum of all rates with signs
    └── Leak problem → without leak rate − with leak rate ⭐⭐
```

---

## 🚨 Common Mistakes — Never Make These in TCS

| Wrong Approach | Correct Approach |
|---|---|
| Adding days directly (A=6, B=12 → together=18) | Use LCM method. Together = 4 days, not 18 |
| Forgetting negative sign for drain pipe | Always mark inlet as + and outlet as − |
| Treating efficiency and time as directly proportional | They are **inversely** proportional |
| Using fraction method and getting confused mid-calculation | Switch to LCM — no fractions needed |
| Wages split equally | Split in ratio of their work rates |
| Alternate days — adding rates and halving | Do per 2-day cycle, not per day |

---

## 🧠 The One Mental Model Behind Everything

```
Every T&W and Pipes problem is the same:

Total Work = Fixed (set it to LCM)

Each person/pipe has a RATE (units per day)
  → Filling / Doing work = POSITIVE rate
  → Draining / Leaving   = NEGATIVE rate

Net Rate = Sum of all rates with correct signs

Time = Total Work / Net Rate

That's the entire topic in 5 lines.
```

> 💡 **The LCM method removes every fraction from the problem.**
> Set total work = LCM. Every rate becomes a whole number. Calculate and done.

---

> **Next Topic:** Ratio & Proportion
> Built on the same fraction thinking — ratios are just comparing two quantities,
> and proportion is two equal ratios. Very fast to master after T&W.
