# 🚀 Time, Speed & Distance — Complete TCS NQT Notes
> **Format:** Every concept has 🔵 Formula Method + 🟢 Manual Method
> **Exam Weight:** 2–3 questions | **Difficulty:** Easy–Medium

---

## 🧠 The Core Relationship — Understand This First

```
Distance = Speed × Time

Speed    = Distance / Time

Time     = Distance / Speed
```

> 💡 **One triangle. Three formulas. Cover the one you want to find.**

```
        [ D ]
       ───────
      [ S × T ]
```
- Cover D → S × T
- Cover S → D / T
- Cover T → D / S

> Everything in TCS — trains, boats, races, meetings — is built on this one triangle.

---

## 📌 Must-Know Unit Conversions
> **Memorise these. Conversion errors are the #1 reason students lose marks in TCS.**

### Speed Conversion

| From | To | Multiply by |
|---|---|---|
| km/h | m/s | × 5/18 |
| m/s | km/h | × 18/5 |

**Example:**
```
72 km/h → m/s = 72 × 5/18 = 20 m/s
15 m/s → km/h = 15 × 18/5 = 54 km/h
```

> 💡 **Quick Check:** 18 km/h = 5 m/s. Use this as anchor.
> 36 km/h = 10 m/s. 54 km/h = 15 m/s. 72 km/h = 20 m/s.

### Time Conversion

| Unit | Equivalent |
|---|---|
| 1 hour | 60 minutes = 3600 seconds |
| 1 minute | 60 seconds |
| 1 km | 1000 metres |

---

## 1️⃣ Basic Distance / Speed / Time

### 🔵 Formula Method
```
D = S × T     |     S = D/T     |     T = D/S
```

> A car travels at 60 km/h for 2.5 hours. Distance?
```
D = 60 × 2.5 = 150 km ✅
```

---

### 🟢 Manual Method (Unitary Method)
> If formula feels shaky, just think in units.

```
60 km in 1 hour
So in 2.5 hours = 60 × 2.5 = 150 km ✅
```

> Or: "1 hour = 60 km. Half hour = 30 km. Total 2.5 hrs = 120 + 30 = 150 km"

---

## 2️⃣ Average Speed ⭐⭐⭐
> **Most asked TCS trap. 90% of students get this wrong.**

### ⚠️ The Trap
> Average Speed ≠ (S1 + S2) / 2
> That formula only works if TIME is equal. In TCS, distance is usually equal.

---

### 🔵 Formula Method (Equal Distance)
> When same distance is covered at two different speeds:

```
Average Speed = 2 × S1 × S2 / (S1 + S2)
```

> A goes from A to B at 40 km/h and returns at 60 km/h. Average speed?
```
= 2 × 40 × 60 / (40 + 60)
= 4800 / 100
= 48 km/h ✅
```

> ⚠️ Answer is NOT 50. It is always LESS than the simple average.

---

### 🟢 Manual Method (Assume Distance)
> Forget the formula. Just assume a convenient distance.

```
Step 1: Assume distance A to B = 120 km (LCM of 40 and 60)

Step 2: Time A→B = 120/40 = 3 hours
        Time B→A = 120/60 = 2 hours

Step 3: Total distance = 120 + 120 = 240 km
        Total time     = 3 + 2     = 5 hours

Step 4: Average Speed = 240/5 = 48 km/h ✅
```

> 💡 **Always assume distance = LCM of the two speeds. Makes division clean.**

---

## 3️⃣ Relative Speed ⭐⭐⭐
> Used for trains, chasing, meeting problems.

### The Two Rules

| Situation | Relative Speed |
|---|---|
| Moving in **SAME** direction | S1 − S2 (subtract) |
| Moving in **OPPOSITE** direction | S1 + S2 (add) |

> 💡 **Memory:** Same direction = they're helping each other → slow down (subtract)
> Opposite = they're fighting → speed up (add)

---

### 🔵 Formula Method
```
Time to meet / cross = Distance between them / Relative Speed
```

> Two trains, 100 km apart, moving towards each other at 40 km/h and 60 km/h.
```
Relative speed = 40 + 60 = 100 km/h
Time to meet   = 100 / 100 = 1 hour ✅
```

> Two trains, moving same direction at 80 km/h and 50 km/h. 150 km apart.
```
Relative speed = 80 − 50 = 30 km/h
Time to catch  = 150 / 30 = 5 hours ✅
```

---

### 🟢 Manual Method (Close the Gap Thinking)
> Think: how fast is the gap closing (or opening)?

**Opposite direction:**
```
Every hour, Train 1 covers 40 km, Train 2 covers 60 km.
Together they cover 40 + 60 = 100 km per hour.
Gap = 100 km → fills in 1 hour ✅
```

**Same direction:**
```
Every hour, faster train gains 80 − 50 = 30 km on slower.
Gap = 150 km → 150/30 = 5 hours to catch ✅
```

> 💡 This "gap closing" thinking is more intuitive and works even without formulas.

---

## 4️⃣ Train Problems ⭐⭐⭐

### The Golden Rule
```
When a train crosses something:
Distance covered by train = Length of train + Length of object
```

| Object | Length to Add |
|---|---|
| A pole / person / signal | Only train length (pole has 0 length) |
| A platform / bridge | Train length + Platform length |
| Another train | Train 1 length + Train 2 length |

---

### 🔵 Formula Method
```
Time = (Length of train + Length of object) / Speed of train
```
> (Use relative speed if the object is also moving)

**Example 1 — Train crossing a pole:**
> Train 200m long at 72 km/h crosses a pole. Time?
```
Speed = 72 × 5/18 = 20 m/s
Time  = 200 / 20 = 10 seconds ✅
```

**Example 2 — Train crossing a platform:**
> Train 300m long at 54 km/h crosses a 200m platform. Time?
```
Speed    = 54 × 5/18 = 15 m/s
Distance = 300 + 200 = 500m
Time     = 500 / 15 = 33.33 seconds ✅
```

**Example 3 — Two trains crossing each other (opposite):**
> Train A: 200m at 60 km/h. Train B: 300m at 40 km/h. Opposite direction. Time to cross?
```
Relative speed = 60 + 40 = 100 km/h = 100 × 5/18 = 250/9 m/s
Total length   = 200 + 300 = 500m
Time           = 500 / (250/9) = 500 × 9/250 = 18 seconds ✅
```

**Example 4 — Two trains crossing each other (same direction):**
> Train A: 200m at 80 km/h. Train B: 300m at 50 km/h. Same direction. Time to cross?
```
Relative speed = 80 − 50 = 30 km/h = 30 × 5/18 = 25/3 m/s
Total length   = 200 + 300 = 500m
Time           = 500 / (25/3) = 500 × 3/25 = 60 seconds ✅
```

---

### 🟢 Manual Method (Step by Step — No Memorisation)
```
Step 1: Convert speed to m/s (× 5/18)
Step 2: Add up all lengths involved
Step 3: Time = Total length / Speed (or relative speed)
```

> 💡 **The most common mistake:** Forgetting to add the platform/second train length.
> Always ask: "What is the FULL distance the front of the train must travel until the tail clears?"

---

## 5️⃣ Boats and Streams ⭐⭐

### The Core Concept
```
Downstream (with current)  : Effective speed = Boat + Stream
Upstream   (against current): Effective speed = Boat − Stream
```

| What You Know | Formula |
|---|---|
| Downstream speed (D) and Upstream speed (U) | Boat speed = (D + U) / 2 |
| Downstream speed (D) and Upstream speed (U) | Stream speed = (D − U) / 2 |

---

### 🔵 Formula Method
> Boat speed in still water = 15 km/h. Stream = 5 km/h.
```
Downstream = 15 + 5 = 20 km/h
Upstream   = 15 − 5 = 10 km/h
```

> Downstream = 20, Upstream = 10. Find boat speed and stream speed.
```
Boat speed   = (20 + 10) / 2 = 15 km/h ✅
Stream speed = (20 − 10) / 2 = 5 km/h  ✅
```

---

### 🟢 Manual Method (Think Physically)
> Downstream: current HELPS the boat → speed adds up → goes faster
> Upstream: current FIGHTS the boat → speed reduces → goes slower

```
If boat = 15, stream = 5:
Going with stream → 15 + 5 = 20 (faster)
Going against stream → 15 − 5 = 10 (slower)
```

> 💡 Average the two to get back to boat speed. That's it.
```
(20 + 10) / 2 = 15 = boat speed ✅
(20 − 10) / 2 = 5  = stream speed ✅
```

---

## 6️⃣ Meeting / Reaching Problems ⭐⭐

### Type A — Two people walking towards each other

### 🔵 Formula Method
```
Time to meet = Distance / (S1 + S2)
```
> A and B are 300 km apart. A at 50 km/h, B at 70 km/h. Walking towards each other. When do they meet?
```
Time = 300 / (50 + 70) = 300/120 = 2.5 hours ✅
```

---

### 🟢 Manual Method
```
Every hour, the gap reduces by 50 + 70 = 120 km
Gap = 300 km → 300/120 = 2.5 hours ✅
```

---

### Type B — One person chasing another

### 🔵 Formula Method
```
Time to catch = Gap / (S_fast − S_slow)
```
> A starts at 8 AM at 40 km/h. B starts at 10 AM at 60 km/h. When does B catch A?
```
Head start of A = 2 hours × 40 = 80 km
Relative speed  = 60 − 40 = 20 km/h
Time to catch   = 80 / 20 = 4 hours after B starts
B catches A at  = 10 AM + 4 = 2 PM ✅
```

---

### 🟢 Manual Method
```
By 10 AM, A has travelled 2 × 40 = 80 km ahead.
Every hour after that, B gains 60 − 40 = 20 km.
Hours to close 80 km gap = 80/20 = 4 hours.
B catches A at 2 PM ✅
```

---

## 7️⃣ Late / Early Arrival Type ⭐⭐
> **Very common TCS pattern.** Person arrives late or early at two different speeds.

### 🔵 Formula Method
```
Distance = [S1 × S2 × (T1 ± T2)] / (S1 ~ S2)
```
> This formula is complex to remember. Use the manual method instead.

---

### 🟢 Manual Method (Always Use This — Much Easier)

**Example:**
> A man walks at 4 km/h and reaches 10 min late.
> If he walks at 5 km/h he reaches 5 min early. Find distance.

```
Step 1: Time difference = 10 + 5 = 15 minutes = 1/4 hour
        (One is late, one is early → ADD the times)

Step 2: At 4 km/h → takes T hours
        At 5 km/h → takes (T − 1/4) hours
        (5 km/h saves 15 min = 1/4 hour)

Step 3: Distance is same both times
        4 × T = 5 × (T − 1/4)
        4T = 5T − 5/4
        T = 5/4 hours

Step 4: Distance = 4 × 5/4 = 5 km ✅
```

> ⚠️ **When to ADD vs SUBTRACT the time difference?**
> - One late, one early → ADD both times
> - Both late but one more than other → SUBTRACT

---

## 8️⃣ Circular Track / Races ⭐

### Key Ideas

| Situation | When they meet again |
|---|---|
| Same direction on a circular track | Time = Track length / (S1 − S2) |
| Opposite direction on a circular track | Time = Track length / (S1 + S2) |

> 💡 Same idea as relative speed — just the "distance" is now the track length.

---

### 🔵 Formula + Manual Method
> A and B run on a 400m track. A at 10 m/s, B at 6 m/s. Same direction. When do they first meet?
```
Relative speed = 10 − 6 = 4 m/s
Time to meet   = 400 / 4 = 100 seconds ✅
```

> Manual: A gains 4 m every second on B. To lap B (gain 400m), needs 400/4 = 100 sec.

---

## 9️⃣ Time–Speed Inverse Relationship ⭐
> **If distance is constant:** Speed and Time are inversely proportional.

```
S1 / S2 = T2 / T1
```

> A covers a distance in 3 hours at 80 km/h. How long at 60 km/h?
```
T2 = (S1 / S2) × T1 = (80/60) × 3 = 4 hours ✅
```

### 🟢 Manual Method
```
Distance = 80 × 3 = 240 km
Time at 60 = 240 / 60 = 4 hours ✅
```

> 💡 Always the safer method when fractions are messy.

---

## ⚡ Speed Tricks & Shortcuts

| Trick | Method |
|---|---|
| km/h → m/s | × 5/18 (memorise as "divide by ~3.6") |
| m/s → km/h | × 18/5 (memorise as "multiply by 3.6") |
| LCM trick for average speed | Assume distance = LCM of speeds |
| Opposite direction meeting | Add speeds, divide gap |
| Same direction chasing | Subtract speeds, divide gap |
| Train crossing pole | Only train length matters |
| Train crossing platform | Train + Platform length |
| Boat downstream | Add stream speed |
| Boat upstream | Subtract stream speed |

---

## 🧩 TCS NQT — Question Types & Frequency

| Question Type | Frequency | Difficulty | Best Method |
|---|---|---|---|
| Average speed (equal distance) | ⭐⭐⭐ Very High | Easy–Medium | Assume distance = LCM |
| Train crossing platform/train | ⭐⭐⭐ Very High | Medium | Add lengths, relative speed |
| Relative speed (meeting/chasing) | ⭐⭐⭐ Very High | Easy | Gap ÷ relative speed |
| Boats and streams | ⭐⭐ High | Easy | D+U for down, D−U for up |
| Late/early arrival | ⭐⭐ High | Medium | Manual algebra method |
| Circular track / races | ⭐ Medium | Medium | Relative speed on track |
| Basic D=ST | ⭐ Medium | Easy | Direct formula |

---

## 🔁 Practice Questions (TCS Level)

**Q1.** A person goes to office at 30 km/h and returns at 20 km/h. Average speed?
```
Manual: Assume distance = 60 km (LCM of 30, 20)
Time there = 60/30 = 2h | Time back = 60/20 = 3h
Total = 120 km in 5h → Avg = 24 km/h ✅
```

**Q2.** A 300m train at 90 km/h crosses a 200m platform. Time taken?
```
Speed = 90 × 5/18 = 25 m/s
Distance = 300 + 200 = 500m
Time = 500/25 = 20 seconds ✅
```

**Q3.** Two trains 400m and 500m long, speeds 60 km/h and 40 km/h, opposite direction. Time to cross?
```
Relative speed = 100 km/h = 100 × 5/18 = 250/9 m/s
Total length = 900m
Time = 900 ÷ (250/9) = 900 × 9/250 = 32.4 seconds ✅
```

**Q4.** Boat goes 30 km downstream in 2 hours, 18 km upstream in 3 hours. Find stream speed.
```
Downstream speed = 30/2 = 15 km/h
Upstream speed   = 18/3 = 6 km/h
Stream speed = (15 − 6)/2 = 4.5 km/h ✅
```

**Q5.** A walks at 3 km/h, late by 20 min. At 4 km/h, early by 10 min. Distance?
```
Time difference = 20 + 10 = 30 min = 1/2 hour
3T = 4(T − 1/2) → 3T = 4T − 2 → T = 2 hours
Distance = 3 × 2 = 6 km ✅
```

**Q6.** A and B on 600m circular track, same direction. Speeds 8 m/s and 5 m/s. When do they first meet?
```
Relative speed = 3 m/s
Time = 600/3 = 200 seconds ✅
```

---

## 🗺 Concept Map

```
TIME, SPEED & DISTANCE
│
├── CORE: D = S × T
│   ├── Find D, S, or T
│   └── Unit Conversion (km/h ↔ m/s)
│
├── AVERAGE SPEED
│   ├── Equal distance → 2S1S2/(S1+S2)  ⭐
│   └── Assume distance = LCM (manual)
│
├── RELATIVE SPEED
│   ├── Opposite direction → Add speeds  ⭐
│   ├── Same direction → Subtract speeds ⭐
│   └── Think: "How fast is the gap closing?"
│
├── TRAIN PROBLEMS  ⭐⭐
│   ├── Cross a pole → only train length
│   ├── Cross a platform → train + platform
│   └── Cross another train → both lengths + relative speed
│
├── BOATS & STREAMS  ⭐
│   ├── Downstream = Boat + Stream
│   ├── Upstream = Boat − Stream
│   └── Find boat/stream from D and U
│
├── MEETING / CHASING
│   ├── Towards each other → add speeds
│   └── Same direction → subtract speeds
│
├── LATE / EARLY ARRIVAL  ⭐
│   └── Manual algebra (set up time equation)
│
└── CIRCULAR TRACK / RACES
    ├── Same direction → relative speed
    └── Opposite direction → relative speed
```

---

## 🚨 Common Mistakes — Never Make These in TCS

| Wrong Approach | Correct Approach |
|---|---|
| Average speed = (S1 + S2) / 2 | Use 2S1S2/(S1+S2) OR assume LCM distance |
| Forgetting to add platform length | Total distance = Train + Platform always |
| Not converting km/h to m/s for trains | Always convert when lengths are in metres |
| Adding time difference when both late | Add only when one late + one early; subtract when both same direction |
| Boat: Upstream = Boat + Stream | Upstream = Boat **−** Stream (current fights you) |
| Using simple average for unequal time journeys | Use D = S × T for each leg separately |

---

## 🧠 The One Mental Model Behind Everything

```
Every TCS Time-Speed-Distance problem is a GAP problem.

→ Two things are separated by a GAP (distance).
→ The GAP closes or opens at the RELATIVE SPEED.
→ Time = GAP / Relative Speed.

For trains:    GAP = sum of lengths to be cleared
For boats:     GAP = distance to travel; speed = boat ± stream
For meetings:  GAP = distance between people
For chasing:   GAP = head start distance
```

> Once you see every problem as a "gap closing at some speed", the setup becomes automatic.

---

> **Next Topic:** Time & Work (including Pipes & Cisterns)
> It's built on the same fraction/parts thinking you used in Percentages.
> Work = Rate × Time — same triangle as D = S × T.
