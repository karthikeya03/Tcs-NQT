# 💰 Profit & Loss — Complete TCS NQT Notes
> **Format:** Every concept has 🔵 Formula Method + 🟢 Manual Method
> **Exam Weight:** 1–2 questions | **Difficulty:** Easy–Medium
> **Reality:** P&L is just Percentages applied to buying and selling. Nothing new.

---

## 🧠 The Foundation — Understand These Terms First

| Term | Meaning | Also Called |
|---|---|---|
| **CP** | Cost Price — what you BUY at | Purchase price |
| **SP** | Selling Price — what you SELL at | Sale price |
| **MP** | Marked Price — price written on the tag | List price / MRP |
| **Discount** | Reduction given ON the Marked Price | Always on MP, never on CP |
| **Profit** | SP > CP → you gained | Gain |
| **Loss** | SP < CP → you lost | — |

```
Profit = SP − CP      (when SP > CP)
Loss   = CP − SP      (when CP > SP)
```

> ⚠️ **Critical Rule:**
> - Profit % and Loss % are ALWAYS calculated on **CP** (not SP, not MP)
> - Discount % is ALWAYS calculated on **MP** (not CP, not SP)
> This is where 80% of P&L mistakes happen.

---

## 📌 The P&L Relationship Chain

```
CP  →  [Add Markup %]  →  MP  →  [Subtract Discount %]  →  SP
                                                              ↕
                                                    Compare with CP
                                                    → Profit or Loss
```

---

## 1️⃣ Basic Profit & Loss

### 🔵 Formula Method

```
Profit     = SP − CP
Loss       = CP − SP

Profit %   = (Profit / CP) × 100
Loss %     = (Loss / CP) × 100

SP         = CP × (100 + Profit%) / 100
SP         = CP × (100 − Loss%) / 100

CP         = SP × 100 / (100 + Profit%)
CP         = SP × 100 / (100 − Loss%)
```

---

### 🟢 Manual Method (Parts / 100 Thinking)

> Think of CP as 100 parts always.

**Example 1 — Find SP:**
> CP = ₹400, Profit = 25%. Find SP.
```
CP = 100 parts = ₹400
Profit = 25 parts
SP = 125 parts = 400 × (125/100) = ₹500 ✅
```

**Example 2 — Find CP from SP:**
> SP = ₹540, Profit = 20%. Find CP.
```
CP = 100 parts
SP = 120 parts = ₹540
1 part = 540/120 = 4.5
CP = 100 parts = 4.5 × 100 = ₹450 ✅
```

**Example 3 — Find Loss %:**
> CP = ₹500, SP = ₹425. Loss %?
```
Loss = 500 − 425 = ₹75
Loss % = (75/500) × 100 = 15% ✅
Manual: 75 out of 500 → 75/500 = 3/20 = 15%
```

---

## 2️⃣ Discount ⭐⭐

### 🔵 Formula Method

```
Discount       = MP − SP
Discount %     = (Discount / MP) × 100

SP             = MP × (100 − Discount%) / 100
MP             = SP × 100 / (100 − Discount%)
```

> ⚠️ **Discount is always on MP. Never on CP.**

---

### 🟢 Manual Method

**Example 1 — Find SP after discount:**
> MP = ₹800, Discount = 15%. Find SP.
```
MP = 100 parts = ₹800
Discount = 15 parts
SP = 85 parts = 800 × 85/100 = ₹680 ✅
```

**Example 2 — Find MP from SP:**
> SP = ₹510, Discount = 15%. Find MP.
```
MP = 100 parts
SP = 85 parts = ₹510
1 part = 510/85 = 6
MP = 100 × 6 = ₹600 ✅
```

---

## 3️⃣ Profit on Discounted Item ⭐⭐⭐
> **Most common TCS question type.** CP is given, MP is given (or derived), discount is given. Find profit %.

### 🔵 Formula Method
```
SP = MP × (100 − d%) / 100
Profit % = (SP − CP) / CP × 100
```

---

### 🟢 Manual Method (Step by Step)

**Example:**
> CP = ₹500. MP = ₹700. Discount = 20%. Find profit %.
```
Step 1: Find SP
        SP = 700 × (100−20)/100 = 700 × 80/100 = ₹560

Step 2: Find Profit
        Profit = SP − CP = 560 − 500 = ₹60

Step 3: Profit %
        = (60/500) × 100 = 12% ✅
```

> 💡 **Always find SP first, then compare with CP.**

---

## 4️⃣ Successive Discounts ⭐⭐
> Two discounts given one after another. NOT the same as adding them.

### 🔵 Formula Method
```
Net Discount = x + y − (xy/100)
```
> (Same structure as Successive % change — just with negatives only)

**Example:**
> Successive discounts of 20% and 10%. Net discount?
```
= 20 + 10 − (20×10)/100
= 30 − 2
= 28% net discount ✅
```

---

### 🟢 Manual Method (Assume MP = 100)

**Example:**
> MP = ₹100. Discount 1 = 20%. Discount 2 = 10%.
```
After 1st discount: 100 − 20 = ₹80
After 2nd discount: 80 − 8 = ₹72

Net discount = 100 − 72 = 28% ✅
```

> ⚠️ 20% + 10% = 30% is WRONG. The 2nd discount applies on the already reduced price, not on MP.
> Answer is always LESS than the simple sum.

---

## 5️⃣ Finding CP When Profit/Loss % is Given ⭐⭐⭐
> This is just reverse percentage. You already know this from the Percentages notes.

### 🟢 Manual Method (Parts Method — Use Every Time)

**Example 1 — Profit:**
> Selling at ₹660 gives 10% profit. Find CP.
```
CP = 100 parts
SP = 110 parts = ₹660
1 part = 6
CP = 100 × 6 = ₹600 ✅
```

**Example 2 — Loss:**
> Selling at ₹420 gives 16% loss. Find CP.
```
CP = 100 parts
SP = 84 parts = ₹420
1 part = 5
CP = 100 × 5 = ₹500 ✅
```

---

## 6️⃣ Selling at Two Different Prices — Same Profit/Loss ⭐

### Classic TCS Pattern:
> A sells two items, each for the same price. On one he gains x%, on the other he loses x%.
> **Net result is always a LOSS.**

### 🔵 Formula Method
```
Net Loss % = (x²) / 100
```

**Example:**
> Two items each sold at ₹600. One at 20% profit, one at 20% loss. Net result?
```
Net Loss % = (20)² / 100 = 400/100 = 4% loss ✅
```

---

### 🟢 Manual Method (Find Actual CP of Each)

```
Item 1: SP = ₹600, Profit 20%
        CP = 600 × 100/120 = ₹500

Item 2: SP = ₹600, Loss 20%
        CP = 600 × 100/80 = ₹750

Total CP  = 500 + 750 = ₹1250
Total SP  = 600 + 600 = ₹1200

Loss      = 1250 − 1200 = ₹50
Loss %    = (50/1250) × 100 = 4% ✅
```

> 💡 Manual method is safer. The formula is a shortcut only when both % are exactly equal.

---

## 7️⃣ Dishonest Dealer / False Weight ⭐⭐

### Classic Pattern:
> A dealer claims to sell at CP but uses a false weight. What is his profit %?

### 🔵 Formula Method
```
Profit % = (True Weight − False Weight) / False Weight × 100
```

**Example:**
> Dealer claims to sell 1kg but actually gives only 800g. Profit %?
```
= (1000 − 800) / 800 × 100
= 200/800 × 100
= 25% ✅
```

---

### 🟢 Manual Method (Think in Value)
```
He gives 800g but charges for 1000g.
He gains 200g on every 800g he actually gives.
200 out of 800 = 1/4 = 25% ✅
```

---

## 8️⃣ Markup and Margin ⭐

| Term | Meaning | Base |
|---|---|---|
| **Markup %** | % by which MP is set above CP | CP is base |
| **Margin %** | Profit as % of SP (used in business) | SP is base |

> TCS mostly uses **Profit %** (base = CP). Margin (base = SP) appears occasionally.

### 🔵 Formula
```
Markup %  = (MP − CP) / CP × 100
Margin %  = (SP − CP) / SP × 100
```

**Conversion between the two:**
```
If Profit % on CP = x%
Then Margin % on SP = x / (100 + x) × 100
```

**Example:**
> Profit on CP = 25%. Margin on SP?
```
= 25 / (100+25) × 100 = 25/125 × 100 = 20% ✅
```

---

## 9️⃣ Combined Profit on Multiple Items ⭐

**Example:**
> A bought 3 pens at ₹10 each and 2 pens at ₹15 each. Sold all 5 at ₹14 each. Profit or loss?
```
Total CP = 3×10 + 2×15 = 30 + 30 = ₹60
Total SP = 5×14 = ₹70
Profit   = 70 − 60 = ₹10
Profit % = (10/60) × 100 = 16.67% ✅
```

---

## 🔟 Selling Price to Get Desired Profit ⭐

### 🟢 Manual Method
**Example:**
> CP = ₹350. Want 30% profit. What should SP be?
```
CP = 100 parts = ₹350
SP = 130 parts = 350 × 130/100 = ₹455 ✅
```

---

## 1️⃣1️⃣ Breaking Even / Cost Recovery

**Example:**
> A trader buys 100 mangoes at ₹2 each. 20 mangoes rot. At what price must he sell the rest to recover cost?
```
Total CP = 100 × 2 = ₹200
Remaining = 80 mangoes
SP per mango = 200/80 = ₹2.50 ✅ (break even)

For 20% profit:
Need to collect = 200 × 1.20 = ₹240
SP per mango   = 240/80 = ₹3 ✅
```

---

## ⚡ Key Shortcuts to Memorise

| Situation | Shortcut |
|---|---|
| SP when profit x% known | SP = CP × (100+x)/100 |
| CP when profit x% and SP known | CP = SP × 100/(100+x) |
| SP when loss x% known | SP = CP × (100−x)/100 |
| CP when loss x% and SP known | CP = SP × 100/(100−x) |
| Equal SP, equal +x% and −x% | Always a loss = x²/100 % |
| Successive discounts x% and y% | Net = x+y−xy/100 |
| False weight profit % | (True−False)/False × 100 |

---

## 🧩 TCS NQT — Question Types & Frequency

| Question Type | Frequency | Difficulty | Key Watch-out |
|---|---|---|---|
| Find CP or SP given the other + % | ⭐⭐⭐ Very High | Easy | Use parts method |
| Profit after discount (CP + MP + discount%) | ⭐⭐⭐ Very High | Medium | Find SP first, then compare with CP |
| Successive discounts | ⭐⭐ High | Easy | Never add discounts directly |
| Same SP, equal profit% and loss% | ⭐⭐ High | Easy | Always a net loss |
| Dishonest dealer / false weight | ⭐⭐ High | Medium | Gain on actual quantity given |
| Combined/multiple items profit | ⭐ Medium | Medium | Total SP vs Total CP |
| Markup vs margin | ⭐ Medium | Medium | Check which base is asked |

---

## 🔁 Practice Questions (TCS Level)

**Q1.** CP = ₹450, SP = ₹540. Profit %?
```
Profit = 90. Base = 450.
= (90/450) × 100 = 20% ✅
```

**Q2.** SP = ₹884, profit = 30%. Find CP.
```
130 parts = 884 → 1 part = 6.8 → CP = 680 ✅
```

**Q3.** MP = ₹1200, discount = 25%. SP?
```
SP = 1200 × 75/100 = ₹900 ✅
```

**Q4.** CP = ₹600, MP = ₹900, discount = 20%. Profit %?
```
SP = 900 × 80/100 = ₹720
Profit = 720 − 600 = ₹120
Profit % = (120/600) × 100 = 20% ✅
```

**Q5.** Successive discounts 30% and 20%. Net discount?
```
= 30 + 20 − (30×20)/100 = 50 − 6 = 44% ✅
Manual: 100 → −30% → 70 → −20% → 56 → Discount = 44% ✅
```

**Q6.** Two articles each sold at ₹480. One at 20% profit, one at 20% loss. Net result?
```
Net loss % = 20²/100 = 4%
Manual: CP1 = 480×100/120 = 400
        CP2 = 480×100/80  = 600
Total CP = 1000, Total SP = 960
Loss = 40, Loss% = (40/1000)×100 = 4% ✅
```

**Q7.** Dealer uses 900g weight for 1kg. Claims to sell at CP. Profit %?
```
= (1000−900)/900 × 100 = 100/900 × 100 = 11.11% ✅
```

**Q8.** A man buys 80 oranges at ₹5 each. 20 are bad. Sells rest at ₹8. Profit %?
```
Total CP = 400. Sells 60 at ₹8 = ₹480.
Profit = 80. Profit% = (80/400)×100 = 20% ✅
```

---

## 🗺 Concept Map

```
PROFIT & LOSS
│
├── CORE TERMS
│   ├── CP → what you buy at (base for profit/loss %)
│   ├── MP → what you tag it at (base for discount %)
│   └── SP → what you sell at (outcome)
│
├── BASIC P&L
│   ├── Profit/Loss = SP ~ CP
│   ├── Profit/Loss % = (difference / CP) × 100
│   └── Find SP or CP using parts method ⭐
│
├── DISCOUNT
│   ├── On MP always ⭐
│   ├── SP = MP × (100−d)/100
│   └── Successive discounts → never add directly ⭐
│
├── COMBINED (CP + MP + Discount)
│   ├── Step 1: Find SP from MP and discount
│   ├── Step 2: Compare SP with CP
│   └── Step 3: Calculate profit/loss %
│
├── SPECIAL TYPES
│   ├── Equal SP equal ±% → always net loss = x²/100 ⭐
│   ├── Dishonest dealer → (True−False)/False × 100 ⭐
│   └── Spoilage/bad items → Total CP vs SP on good items
│
└── MARKUP vs MARGIN
    ├── Markup % → base is CP
    └── Margin % → base is SP
```

---

## 🚨 Common Mistakes — Never Make These in TCS

| Wrong Approach | Correct Approach |
|---|---|
| Calculating profit % on SP | **Profit % is always on CP** |
| Calculating discount % on CP | **Discount % is always on MP** |
| Adding successive discounts directly | Use assume 100 method or formula |
| Thinking equal ±% = no net change | There is always a net **loss** = x²/100 |
| False weight: profit on 1000g | Profit is on 800g (what he actually gives) |
| Forgetting to find SP before computing profit | Always: SP first → then compare with CP |

---

## 🧠 The One Mental Model Behind P&L

```
P&L has exactly one chain:

CP → (Markup) → MP → (Discount) → SP → (Compare with CP) → Profit or Loss

Your job in every question:
  → Find SP
  → Compare SP with CP
  → Express difference as % of CP

That's it. Every P&L question follows this chain.
Discount traps, false weight, successive discounts —
they all just change HOW you find SP.
The final step is always the same.
```

---

> **Next Topic:** Time & Work (including Pipes & Cisterns)
> Uses the same parts thinking from Percentages — work done = fraction of total.
> LCM method makes every T&W question solvable in under 60 seconds.
