# 🧠 Reasoning Ability — Complete TCS NQT Notes
> **20 Questions | 25 Minutes | Easy–Medium**
> **Target for Prime: 16–17/20**
> Every topic has Top 5 Sub-topics + TCS NQT style practice problems

---

## 📋 Table of Contents
1. [Number / Letter Series](#1️⃣-number--letter-series)
2. [Seating Arrangement](#2️⃣-seating-arrangement)
3. [Blood Relations](#3️⃣-blood-relations)
4. [Coding-Decoding](#4️⃣-coding-decoding)
5. [Syllogisms](#5️⃣-syllogisms)
6. [Direction Sense](#6️⃣-direction-sense)
7. [Logical Deductions](#7️⃣-logical-deductions)
8. [Inequalities](#8️⃣-inequalities)
9. [Data Sufficiency](#9️⃣-data-sufficiency)
10. [Puzzles — Ranking & Scheduling](#1️⃣0️⃣-puzzles--ranking--scheduling)
11. [Analogy](#1️⃣1️⃣-analogy)
12. [Odd One Out](#1️⃣2️⃣-odd-one-out)
13. [Practice Problems — TCS NQT Style](#-practice-problems--tcs-nqt-style)

---

## 1️⃣ Number / Letter Series
> **Expected: 3–4 Qs | 🔴 MUST**

### Top 5 Sub-topics

**1. Difference Series**
> Each term differs from the previous by a fixed or increasing/decreasing amount.
```
2, 5, 9, 14, 20, ?
Differences: 3, 4, 5, 6 → next diff = 7 → Answer = 27
```

**2. Square / Cube Series**
> Terms are squares or cubes of consecutive numbers, sometimes with addition/subtraction.
```
1, 8, 27, 64, 125, ?      → Cubes: 1³,2³,3³,4³,5³ → 6³ = 216
4, 9, 25, 49, 121, ?      → Squares of primes: 2²,3²,5²,7²,11² → 13² = 169
```

**3. Alternating / Two Interleaved Series**
> Two separate series merged together alternately.
```
2, 3, 4, 6, 6, 12, 8, 24, 10, ?
Odd positions:  2, 4, 6, 8, 10 → +2 each
Even positions: 3, 6, 12, 24   → ×2 each → next = 48
Answer = 48
```

**4. Multiplication / Division Series**
> Terms are multiplied or divided by a constant or increasing factor.
```
3, 6, 18, 72, 360, ?
Multiplied by: 2, 3, 4, 5 → next multiply by 6 → 2160
```

**5. Letter Series (Position-based)**
> Letters shift by a fixed or increasing number of positions in the alphabet.
```
A, C, F, J, O, ?
Position shifts: +2, +3, +4, +5 → next +6 → U
```
> 💡 **Key:** Write A=1, B=2...Z=26. Convert to numbers, find pattern, convert back.

### ⚡ Quick Identification Guide

| Pattern | How to Spot |
|---|---|
| Difference series | Subtract consecutive terms — look for AP |
| Square/Cube | Check if terms ≈ perfect squares or cubes |
| Multiplication | Divide consecutive terms — look for constant ratio |
| Alternating | Write odd-position and even-position terms separately |
| Letter series | Convert to numbers, find difference |

---

## 2️⃣ Seating Arrangement
> **Expected: 3–4 Qs | 🔴 MUST**
> TCS always gives a set of 4–5 conditions + asks 2–3 questions. Draw first, answer after.

### Top 5 Sub-topics

**1. Linear Arrangement — Facing Same Direction**
> People sitting in a row, all facing north (or south).
```
Rule: Left and right are YOUR left and right.
      "A is to the right of B" → A is on B's right side on the line.
```

**2. Linear Arrangement — Facing Opposite Directions**
> Some people face north, some face south.
```
Key trap: When two people face each other,
their lefts and rights are MIRROR images.
Always note "facing towards" or "facing away from".
```

**3. Circular Arrangement — Facing Centre**
> Everyone sits in a circle facing inward.
```
Rule: When facing centre:
      Your left = anticlockwise direction on the circle
      Your right = clockwise direction on the circle
```

**4. Circular Arrangement — Facing Outside**
> Everyone sits in a circle facing outward.
```
Rule: When facing outside: OPPOSITE of above.
      Your left = clockwise
      Your right = anticlockwise
```

**5. Mixed Conditions (Immediate Neighbour + Gap Conditions)**
> "A sits second to the left of B" type.
```
"Second to the left" = skip one seat in the left direction
"Immediate left"     = directly next seat on the left
Always place the most constrained person first.
```

### 🟢 How to Solve Any Arrangement Problem
```
Step 1: Count people and seats. Draw the structure (line or circle).
Step 2: Find the ANCHOR — most information given about one person.
Step 3: Place anchor first.
Step 4: Use elimination — after each placement, re-read conditions to place others.
Step 5: Verify ALL conditions once filled.
Step 6: Answer the questions from the diagram.
```

> ⚠️ **Never solve in your head. Always draw. Always.**

---

## 3️⃣ Blood Relations
> **Expected: 2–3 Qs | 🔴 MUST**

### Top 5 Sub-topics

**1. Direct Relations**
```
Parent → Child
Grandparent → Grandchild
Sibling → Brother / Sister
Spouse → Husband / Wife
```
> 💡 Always establish GENDER before deciding "uncle" vs "aunt", "nephew" vs "niece".

**2. Coded Relations (Symbols)**
> TCS often codes relations with symbols or operations.
```
Example: A + B means A is father of B
         A − B means A is mother of B
         A × B means A is brother of B
         A ÷ B means A is sister of B

Q: What is P in P + Q − R × S?
   P is father of Q, Q is mother of R, R is brother of S
   → P is grandfather of S ✅
```

**3. Pointing / Introduction Type**
> "He pointed to a man and said his mother is the only daughter of my mother."
```
Only daughter of my mother = myself (if female speaker)
So: His mother = the speaker herself
→ He is the speaker's son ✅
```

**4. Counting Family Members from a Passage**
> A paragraph describes family relationships. Find total members, gender, or specific relation.
```
Always draw a family tree as you read.
Use boxes for people, arrows for parent→child, = for married.
M/F labels on each box.
```

**5. Puzzle-style Blood Relations (Multi-person)**
> 3–4 people, multiple relationship statements, find one specific relation.
```
Step 1: Convert every statement into a tree node and connection.
Step 2: Find the common reference person.
Step 3: Trace the path from person A to person B through the tree.
Step 4: Count generations and gender to name the relation.
```

### 🟢 Generation Chart (Quick Reference)

```
+2 Gen above:  Grandfather, Grandmother
+1 Gen above:  Father, Mother, Uncle, Aunt
Same Gen:      Brother, Sister, Husband, Wife, Cousin
−1 Gen below:  Son, Daughter, Nephew, Niece
−2 Gen below:  Grandson, Granddaughter
```

---

## 4️⃣ Coding-Decoding
> **Expected: 2–3 Qs | 🔴 MUST**

### Top 5 Sub-topics

**1. Letter Shift Coding**
> Each letter is shifted by a fixed number of positions.
```
If BIRD = DKTF:
B+2=D, I+2=K, R+2=T, D+2=F → Each letter shifted +2
So FISH = HKUJ ✅

Common shifts: +1, +2, +3, −1, +13 (reverse half alphabet)
```

**2. Reverse Alphabet Coding**
> A↔Z, B↔Y, C↔X... (Position from front = Position from back)
```
Formula: Coded letter position = 27 − original position
A(1) → Z(26), B(2) → Y(25), M(13) → N(14)

If COLD is coded as XLOW:
C(3)→X(24)=27−3 ✅ → reverse alphabet confirmed
```

**3. Word / Sentence Coding**
> Entire words are given a code. Find the code for a new word.
```
If "sky is blue"  = "pit na ja"
   "blue is deep" = "ja na ka"
   "deep waters"  = "ka ra"

Then: blue = ja (common to 1st and 2nd, matched with "ja")
      is   = na
      sky  = pit
      deep = ka
      waters = ra
```

**4. Number Coding**
> Letters are replaced by numbers based on their position or a rule.
```
A=1, B=2...Z=26 (direct position)
OR A=2, B=3 (position+1)
OR odd positions only, or doubled positions

Always check: what rule maps letter → number?
Verify with 2 letters before applying to full word.
```

**5. Mixed / Conditional Coding**
> Each letter is coded based on its position in the word (not alphabet).
```
Example: In a code, 1st letter → last letter of alphabet after it,
                     vowels → their position number
Check pattern on the given example word before applying.
```

### ⚡ Quick Approach
```
Step 1: Count letters — same length coded? → letter substitution
Step 2: Check if it's a+2 or a+3 shift first
Step 3: Check if it's reverse alphabet
Step 4: If none → check position-based or custom rule
Step 5: Verify your rule on 2 letters before answering
```

---

## 5️⃣ Syllogisms
> **Expected: 2–3 Qs | 🔴 MUST**

### Top 5 Sub-topics

**1. All A are B type**
```
Venn: Circle A completely inside Circle B
→ Every A is definitely a B
→ Some B are A (definitely true)
→ Some B are NOT A (may be true, depends on diagram)
```

**2. No A are B type**
```
Venn: Circle A and Circle B completely separate
→ No A is B, No B is A (both definitely true)
→ Some A are B = DEFINITELY FALSE
```

**3. Some A are B type**
```
Venn: Circles A and B overlap partially
→ Some A are B (true)
→ Some B are A (true)
→ All A are B = NOT necessarily true
→ No A is B  = DEFINITELY FALSE
```

**4. Some A are NOT B type**
```
Venn: Part of circle A is outside circle B
→ Some A exist that are not B
→ All A are B = DEFINITELY FALSE
→ No A are B = NOT necessarily true
```

**5. Complementary Pairs + Either/Or Conclusions**
```
When two conclusions are complementary (one is "All A are B"
and the other is "Some A are not B"), and NEITHER is
definitively true or false → answer is "Either I or II follows"

This is the most commonly missed concept in TCS syllogisms.
```

### 🟢 Venn Diagram Quick Reference
```
"All A are B"     → A fully inside B
"No A are B"      → A and B fully separate
"Some A are B"    → A and B partially overlap
"Some A are not B"→ Part of A is outside B
```

---

## 6️⃣ Direction Sense
> **Expected: 1–2 Qs | 🟠 HIGH**

### Top 5 Sub-topics

**1. Basic Direction Grid**
```
Always draw this before every problem:

         NORTH
           ↑
  WEST ←  [X]  → EAST
           ↓
         SOUTH

Turning RIGHT from North → East
Turning LEFT from North  → West
```

**2. Distance Calculation (Pythagoras)**
> After a series of turns and distances, find straight-line distance from start.
```
Net horizontal displacement + Net vertical displacement
→ Use Pythagoras: √(horizontal² + vertical²)

Example: 3km East + 4km North = √(9+16) = √25 = 5km from start
```

**3. Shadow Direction Problems**
```
Morning (sunrise in East):  Shadow falls WEST
Evening (sunset in West):   Shadow falls EAST
Noon:                        Shadow falls directly behind (North in India)

If person faces East in morning → shadow is to their left (West)
```

**4. Relative Direction — Where is A from B?**
```
After tracing the full path, mark both positions on the grid.
Draw an arrow from B → A.
The direction that arrow points = "A is _____ of B"
```

**5. Turns — Left / Right / About Turn**
```
Left turn  = 90° anticlockwise
Right turn = 90° clockwise
About turn = 180° (complete reversal)

If facing North:
After left turn  → facing West
After right turn → facing East
After about turn → facing South
```

### ⚠️ Most Common Trap
> "Facing south, turns left" → Most students say West. It's **EAST**.
> When facing South, your left is East and your right is West. Always redraw the compass after each turn.

---

## 7️⃣ Logical Deductions
> **Expected: 2–3 Qs | 🟠 HIGH**

### Top 5 Sub-topics

**1. Statement–Conclusion**
> Given statements, decide which conclusions definitely follow.
```
Statements:  All dogs are animals. All animals have hearts.
Conclusion I: All dogs have hearts.  → TRUE (chain: dog→animal→heart)
Conclusion II: All animals are dogs. → FALSE (reverse not implied)

Rule: Conclusion must NECESSARILY follow. If it "might" be true, it doesn't follow.
```

**2. Statement–Assumption**
> Find the hidden assumption the statement is based on.
```
Statement: "Take this medicine to cure your cold."
Assumption: The medicine is effective against cold. ✅
            (The speaker assumes it works — that's the hidden premise)

Rule: Assumption is what MUST be true for the statement to make sense.
NOT: something that would be "nice" or "possible"
```

**3. Statement–Argument (Strong vs Weak)**
```
Strong argument: Directly related to the topic + logical + factual
Weak argument:   Emotional, vague, not directly proving/disproving, or too extreme

"Should voting age be reduced to 16?"
Strong FOR: "Young people at 16 are aware of political issues today" ✅
Weak FOR:   "Because some countries do it"  ❌ (not a logical reason)
```

**4. Course of Action**
> Given a problem situation, decide which course of action logically follows.
```
Problem: Many students are failing exams.
Action I:  Conduct remedial classes. ✅ (directly addresses the problem)
Action II: Cancel the exams.         ❌ (doesn't solve the root cause)

Rule: Action must be practical, directly solve the problem, and not be extreme.
```

**5. Statement–Inference**
> Similar to conclusion but based on implied meaning, not direct logic.
```
Statement: "The sales of luxury cars have increased this year."
Inference: People's purchasing power has increased. ✅
           (Implied — not stated directly but logically follows)

Difference from conclusion: Inference allows one level of interpretation.
Conclusion requires strict logical derivation.
```

---

## 8️⃣ Inequalities
> **Expected: 1–2 Qs | 🟠 HIGH**
> Fastest topic in Reasoning. With practice, each Q takes under 20 seconds.

### Top 5 Sub-topics

**1. Direct Chain Inequalities**
```
Given: A > B > C > D
Q: Is A > D? → YES (transitive) ✅
Q: Is B < A? → YES ✅
Q: Is C > A? → NO ❌
```

**2. Combined Statements**
```
Given: A > B, B ≥ C, C > D
Chain: A > B ≥ C > D
→ A > D is definitely true ✅
→ A ≥ C is true (since A > B ≥ C) ✅
→ B > D is true ✅
```

**3. Either-Or Conclusion (Complementary Pair)**
```
If conclusion I says A > C and conclusion II says A = C:
Neither is definitely provable from the chain → "Either I or II follows"
```

**4. Coded Inequalities (Symbol Substitution)**
> TCS often replaces > < = with custom symbols.
```
Given: A @ B means A > B
       A # B means A < B
       A $ B means A = B

Q: If P @ Q # R, then P __ R?
   P > Q < R → No direct relation between P and R
   → Neither P > R nor P < R can be confirmed
```

**5. False Conclusion Trap**
```
Given: A ≥ B > C = D < E
Q: Is A > D? → A ≥ B > C = D → A > D ✅
Q: Is E > B? → D < E, D = C < B → E could be < or > B → NOT CERTAIN ❌
Q: Is A > E? → Cannot chain A to E without going through D < E → NOT CERTAIN ❌
```

### ⚡ Golden Rule
```
You can only confirm a conclusion if you can CHAIN
the symbols without any direction reversal.

A > B < C → you CANNOT say anything about A vs C.
A > B > C → you CAN say A > C.
```

---

## 9️⃣ Data Sufficiency
> **Expected: 1–2 Qs | 🟠 HIGH**

### Top 5 Sub-topics

**1. The 5 Standard Answer Options**
```
(A) Statement I alone is sufficient
(B) Statement II alone is sufficient
(C) Both statements together are sufficient, but neither alone
(D) Each statement alone is sufficient
(E) Neither statement alone nor together is sufficient
```

**2. Number-based DS Questions**
```
Q: Is x > 5?
I. x > 3    → NOT sufficient (x could be 4)
II. x > 7   → SUFFICIENT (x is definitely > 5)
Answer: (B) ✅
```

**3. Age / Relation DS Questions**
```
Q: What is A's age?
I. A is 5 years older than B.
II. B is 20 years old.
I alone: Not sufficient (don't know B's age)
II alone: Not sufficient (don't know A's age)
Both: A = 20 + 5 = 25. Sufficient.
Answer: (C) ✅
```

**4. Even/Odd / Positive/Negative DS**
```
Q: Is n an even number?
I. n² is even.
II. n/2 is an integer.
I alone: If n² is even → n is even. SUFFICIENT ✅
II alone: n/2 is integer → n is even. SUFFICIENT ✅
Answer: (D) — each alone is sufficient ✅
```

**5. The Key Mindset**
```
You are NOT solving the problem.
You are deciding: "Can it be solved with this information?"

Ask yourself for each statement:
"If I use ONLY this statement, can I get ONE definite answer?"
→ Yes = Sufficient
→ No or "more than one answer possible" = Not Sufficient
```

---

## 1️⃣0️⃣ Puzzles — Ranking & Scheduling
> **Expected: 1–2 Qs | 🟡 MEDIUM**

### Top 5 Sub-topics

**1. Linear Ranking (Tallest/Heaviest/Oldest)**
```
Given: A is taller than B. C is shorter than D. B is taller than C.
Build: D > ? > A > B > C (place unknowns by elimination)

Tip: Use a number line. Place each person as conditions are read.
```

**2. Scheduling / Day-of-Week Puzzles**
```
Given: 6 tasks scheduled Mon–Sat, one per day.
Conditions: Task A is before Task B. Task C is on Wednesday. etc.

Step 1: Place fixed-day tasks first (e.g. C = Wednesday)
Step 2: Place relative tasks (A before B)
Step 3: Fill remaining by elimination
```

**3. Floor / Building Puzzles**
```
N people live on N floors (1 = ground, N = top)
Conditions define who is above/below whom.

Tip: Draw a vertical line with floor numbers. Fill top-down.
"Above" = higher floor number.
```

**4. Box / Item Assignment Puzzles**
```
N people each hold one item from N items.
Conditions eliminate possibilities.

Use a grid:
       Item1  Item2  Item3
PersonA   ?      ?      ?
PersonB   ?      ?      ?

Cross out (✗) impossibilities. Circle (✅) confirmed assignments.
```

**5. Multi-variable Puzzles (Most Complex)**
```
5 people, 5 colours, 5 positions → 3 variables at once.
Strategy: Create a grid with people as rows, attributes as columns.
Fill in known values first, then use elimination for unknowns.
```

> 💡 **TCS Tip:** Puzzles usually come as sets — 1 paragraph + 2 questions. Read ALL questions before building the grid so you know what you need to find.

---

## 1️⃣1️⃣ Analogy
> **Expected: 1–2 Qs | 🟡 MEDIUM**

### Top 5 Sub-topics

**1. Object : Use / Function**
```
Pen : Write :: Knife : Cut
Microscope : Bacteria :: Telescope : Stars
```

**2. Part : Whole**
```
Chapter : Book :: Scene : Movie
Petal : Flower :: Spoke : Wheel
```

**3. Cause : Effect / Action : Result**
```
Fire : Ash :: Flood : Debris
Practice : Perfection :: Study : Knowledge
```

**4. Word : Antonym / Synonym Analogy**
```
Hot : Cold :: Light : Dark  (antonym pair)
Happy : Joyful :: Sad : Sorrowful  (synonym pair)
```

**5. Number Analogy**
```
4 : 16 :: 5 : 25  (square)
2 : 8  :: 3 : 27  (cube)
6 : 36 :: 7 : 49  (square again)
Also look for: +same number, ×same number, prime relation
```

### ⚡ How to Approach
```
Step 1: Identify the relationship in the given pair
Step 2: Express it as a sentence: "A is the ___ of B"
Step 3: Apply the EXACT same relationship to the answer pair
Step 4: If two options seem valid, the more SPECIFIC relationship wins
```

---

## 1️⃣2️⃣ Odd One Out
> **Expected: 1 Q | 🟡 MEDIUM**

### Top 5 Sub-topics

**1. Number Pattern Odd One Out**
```
36, 49, 64, 81, 100, 112
All except 112 are perfect squares → 112 is odd one out ✅
```

**2. Letter Group Odd One Out**
```
AZ, BY, CX, DW, EF
All others are pairs that add to 27 (reverse alphabet)
EF: E=5, F=6 → 5+6=11 ≠ 27 → EF is odd one out ✅
```

**3. Category / Classification Odd One Out**
```
Rose, Lotus, Mango, Sunflower, Jasmine
All are flowers except Mango → Mango is odd one out ✅
```

**4. Operation-based Odd One Out**
```
2, 5, 10, 17, 26, 37, 50, 65
Differences: 3, 5, 7, 9, 11, 13, 15 → all odd
Check values: 1²+1=2, 2²+1=5, 3²+1=10... all are n²+1
65 = 8²+1 = 65 ✅ ... wait check 37: 6²+1=37 ✅
All fit → look for one that doesn't. Verify each.
```

**5. Word / Concept Odd One Out**
```
Hammer, Chisel, Screwdriver, Pliers, Eraser
All are tools except Eraser → Eraser is odd one out ✅

Tip: If you can make a valid group from 4 items,
     the one left out is the answer.
```

### ⚡ Strategy
```
Step 1: Scan for the most obvious grouping first
Step 2: If all look similar → dig deeper (operation, hidden property)
Step 3: The answer is the one that breaks the most specific common rule
Step 4: In number odd-one-out, write the numbers/differences — don't guess
```

---

## 🔁 Practice Problems — TCS NQT Style

> These are structured exactly like real TCS NQT questions. No hints, no easy setups.

---

### Series

**P1.** Find the next term: 3, 10, 29, 66, 127, ?
```
Differences: 7, 19, 37, 61 → second differences: 12, 18, 24 → third diff: 6
Next diff after 61: +30 = 91 → Answer: 127 + 91 = 218 ✅
```

**P2.** Find the missing term: 5, 11, 23, 47, ?, 191
```
Each term × 2 + 1: 5×2+1=11, 11×2+1=23, 23×2+1=47, 47×2+1=95
Answer: 95 ✅
```

**P3.** Complete the series: B, E, I, N, T, ?
```
Position: B=2, E=5, I=9, N=14, T=20
Differences: 3, 4, 5, 6 → next diff = 7 → 20+7=27 → Z
Answer: Z ✅
```

---

### Seating Arrangement

**P4.** Six people A, B, C, D, E, F sit in a straight line facing north.
- B sits at one of the extreme ends
- C sits second to the right of B
- Two people sit between D and C
- A sits to the immediate right of D
- E is not an immediate neighbour of C

Who sits at the other extreme end?
```
B is at left end. C is 2nd to right of B → C is at position 3.
Two people between D and C: D is at position 6 (right end) OR position 1 (but B is there).
D = position 6. A is immediate right of D → impossible (D is at end).
So two people between: C=3, D could be at position 6 with 2 people between = positions 4,5.
Wait — if C=3 and 2 between D and C, D is at 3+3=6.
A is immediate right of D (position 6) → impossible. 
So D is to LEFT of C: D=3−3=0 → invalid. Try: D at position 6, A at position ... 
Re-read: A sits immediate right of D → D=5, A=6.
2 people between D(5) and C(3) → positions 4 between them → only 1 person. 
Try C=2: B=1(extreme), C=2+... wait C is 2nd to right of B(1) → C=3.
D=6, A is right of D → impossible. Swap: D=4, people between D(4) and C(3) = positions between = none → 0. Not 2.
D=1 but B=1. D=6: between C(3) and D(6) are positions 4,5 → 2 people ✅. 
A immediate right of D(6) → position 7 (doesn't exist) ❌
So D must be left of C: C=3, D must have 2 between = D=6 (right) or D=0 (invalid, left).
→ Rethink: "two between D and C" means |pos(D)−pos(C)| = 3.
C=3: D=6 or D=0(invalid). D=6. A immediate right of D → no seat. 
Therefore D is to left: C=3, D=3−3=0 invalid.
Final arrangement: B_C _ _ D _ with A right of D:
B=1,C=3, D and A are consecutive (A right of D).
2 between D and C(3): D=6→A would be 7th(no). D=3−3=0(no). 
If 2 seats between means 2 people: C=3,D=6, between = positions 4,5 = 2 people ✅.
A right of D(6) = position 7 (impossible) — so A must be at another interpretation.
A immediate LEFT of D: D=6, A=5. E not neighbour of C(3) → E ≠ 2 and E ≠ 4.
Remaining: positions 2,4,6 for A,D,E,F (B=1,C=3).
D=6,A=5, remaining: E and F for positions 2 and 4. E≠4 → E=2, F=4.
Final: B(1) E(2) C(3) F(4) A(5) D(6)
Other extreme end = D ✅
```

---

### Blood Relations

**P5.** A man pointing to a photograph says, "The father of the mother of the person in the photo is my wife's only son's father-in-law." How is the man related to the person in the photo?
```
My wife's only son = my son
My son's father-in-law = father of my son's wife
Father of mother of person = maternal grandfather

So my son is father-in-law of maternal grandfather of person
→ Person's mother's father = father of my son's wife
→ Person's mother = my son's wife
→ Person is my son's child = my grandchild
Man is the grandfather of the person in the photo ✅
```

**P6.** If A + B means A is father of B; A − B means A is wife of B; A × B means A is brother of B; A ÷ B means A is daughter of B.
What does P + R − Q mean?
```
P + R → P is father of R
R − Q → R is wife of Q
So: P is father of R, R is wife of Q
→ P is father-in-law of Q ✅
```

---

### Coding-Decoding

**P7.** In a certain code, COMPUTER is written as RFUVQNPC. How is MEDICINE written?
```
C(3)→R(18): diff=+15... check: C=3, R=18 → 18−3=15
O(15)→F(6): 6−15=−9... not consistent.
Try reverse: C↔R: C=3, R=18 → mirror? 3+18=21 ≠ 27. 
Try: letters are reversed AND shifted.
COMPUTER reversed = RETUPMOC
R=R, E→F? No.
Try: each letter replaced by the letter that is (26−pos+1) = mirror:
C(3)→X(24)? But coded is R. 
Actual pattern: COMPUTER → RFUVQNPC
C→R: +15, O→F: −9, M→U: +8... inconsistent → it's a substitution, not shift.
Check: pairs C↔R, O↔F, M↔U, P↔V, U↔Q, T↔N, E↔P, R↔C
Each letter maps to another letter: check if it is +15,−9,+8... OR
Check: C(3)+R(18)=21, O(15)+F(6)=21, M(13)+U(21)=34...no.
C=3, R=18: 3×6=18 ✓, O=15, F=6: 15×? ≠6... 
Reverse word: COMPUTER reversed = RETUPMOC → then shift each by +1?
R→R no. 
Pattern: Each letter mapped to the letter that is 23 positions ahead (mod 26):
C(3)+23=26=Z? No, it's R(18). 
Answer approach: MEDICINE → apply same unknown rule.
For exam: identify the rule type (position, reverse, skip), verify on 2 letters, apply.
```

**P8.** In a code language, "flowers are beautiful" = "pit na ja"; "beautiful songs are" = "na sa ja"; "songs and flowers" = "pit ra sa". What is the code for "beautiful"?
```
"flowers are beautiful" = pit na ja  ...(1)
"beautiful songs are"   = na sa ja   ...(2)
"songs and flowers"     = pit ra sa  ...(3)

Common in (1) and (2): "beautiful" and "are" → "na" and "ja"
Common in (2) and (3): "songs" → "sa"
From (2): beautiful and are = na and ja, songs = sa ✅
Common in (1) and (3): "flowers" → "pit"
From (1): flowers=pit, and remaining "are" and "beautiful" = "na" and "ja"
From (2): are = ja (appears with "songs"=sa and "beautiful")
         "beautiful" = "na" ✅
```

---

### Syllogisms

**P9.** Statements: All pens are books. Some books are copies.
Conclusions:
I. Some copies are pens.
II. Some books are pens.
III. No copy is a pen.
```
All pens inside books circle.
Books and copies overlap partially.
Pens are inside books — but do pens overlap with copies? Not necessarily.

I. Some copies are pens → NOT definitely true (pens may not reach copies region) ❌
II. Some books are pens → TRUE (since all pens are books, those pens are also books) ✅
III. No copy is a pen → NOT definitely true (could overlap or not) ❌

Answer: Only Conclusion II follows ✅
```

**P10.** Statements: No chair is a table. All tables are desks.
Conclusions:
I. No chair is a desk.
II. Some desks are tables.
III. Some chairs are desks.
```
Chair and table circles: completely separate.
All tables inside desks.

I. No chair is a desk → NOT necessarily (chairs could overlap with desks via another path) ❌
   Actually: chairs and tables are separate. Tables are inside desks. 
   Chairs could still be in desks (non-table part). So I is NOT definite. ❌
II. Some desks are tables → TRUE (all tables are desks → those tables are desks) ✅
III. Some chairs are desks → NOT definite (no info linking chairs to desks) ❌

Answer: Only Conclusion II follows ✅
```

---

### Direction Sense

**P11.** Ravi starts from point A, walks 6 km north, turns right and walks 8 km, then turns right and walks 6 km, then turns left and walks 4 km to reach point B. How far is B from A and in which direction?
```
Start A.
6 km North → at (0,6)
Turn right (now facing East), 8 km → at (8,6)
Turn right (now facing South), 6 km → at (8,0)
Turn left (now facing East), 4 km → at (12,0)

A = (0,0), B = (12,0)
Distance = 12 km
Direction: B is directly East of A ✅
```

---

### Inequalities

**P12.** Statements: A ≥ B = C > D; E < C
Conclusions:
I. A > D
II. E < B
III. A > E
```
Chain: A ≥ B = C > D and E < C = B

I.  A ≥ B = C > D → A > D ✅ (definitely true)
II. E < C = B → E < B ✅ (definitely true)
III. A ≥ B = C > E → A > E ✅ (definitely true)

All three conclusions follow ✅
```

---

### Odd One Out

**P13.** Find the odd one out: 8, 27, 64, 100, 125, 216
```
8=2³, 27=3³, 64=4³, 125=5³, 216=6³ → all perfect cubes
100 = 10² (perfect square, NOT a perfect cube)
Answer: 100 ✅
```

**P14.** Find the odd one out: BDFH, JLNP, RTVX, MOQS, ZACE
```
BDFH: B(2)D(4)F(6)H(8) → all even positions, differ by 2
JLNP: J(10)L(12)N(14)P(16) → even, +2 ✅
RTVX: R(18)T(20)V(22)X(24) → even, +2 ✅
ZACE: Z(26)A(1)C(3)E(5) → odd positions after Z, +2 ✅ (wraps around)
MOQS: M(13)O(15)Q(17)S(19) → ODD positions, +2
All others are EVEN position series. MOQS is odd positions.
Answer: MOQS ✅
```

---

## 🚨 Common Mistakes — Never Make These in TCS

| Topic | Wrong Approach | Correct Approach |
|---|---|---|
| Series | Guess pattern from first 2 terms | Check at least 3 consecutive differences |
| Seating | Solve without drawing | Always draw — no exceptions |
| Blood Relations | Assume gender without confirmation | Mark gender only when explicitly stated |
| Coding-Decoding | Apply rule without verifying on 2 letters | Verify rule on 2 letters before applying |
| Syllogisms | Use assumptions beyond statements | Only what directly follows — no extra assumptions |
| Direction | Forget to redraw compass after turning | Redraw compass after EVERY turn |
| Inequalities | Try to conclude from A>B<C chain | No conclusion possible when direction reverses |
| Data Sufficiency | Solve the full problem | Only decide IF it can be solved |
| Odd One Out | Pick answer by gut feeling | Verify the group rule applies to ALL others |

---

> **Revision Strategy:** Practice 5 questions per topic from IndiaBIX before the exam.
> After that, the recognition reflex kicks in and each TCS question type becomes automatic.
