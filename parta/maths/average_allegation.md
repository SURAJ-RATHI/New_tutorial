# Average – Complete Notes (Hinglish)

> Source: Viral Maths – Complete Average in one shot.
> Average ek chapter se zyada ek **technique** hai: DI, Arithmetic, Geometry, sab jagah kaam aati hai.

---

## Index

1. Average kya hota hai
2. Basic formula
3. Highway Method (Assumed Average)
4. Jab gap SAME ho (middle value trick)
5. Special sums: 1+2+…+n, squares, cubes
6. Properties of Average
7. Average se Sum nikalna (Sum = Avg × n)
8. Basic solved questions
9. Combined average (do groups ka)
10. Consecutive numbers (NCERT vs Competitive approach)
11. Ratio-based questions
12. "Partial averages diye ho, ek value nikalo" type
13. Entry–Exit Approach (joining / leaving)
14. Wrong number se correct average
15. Cricket & Bowling average
16. Remove / Exclude questions
17. Mains-level questions
18. Quick revision cheat-sheet
19. Common mistakes

---

## 1. Average kya hota hai?

- Hindi: **Ausat**
- Average = **numbers ke group ka representative / leader / mid value / mean**.

**Example:** 5 logon ki family ko dinner par bulana hai. Wo 4, 5, 6, 7, 8 rotiyan khaate hain. Aap sabke liye 6 rotiyan banate ho. Ye "6" hi average (ausat) hai.

**Definition (exam):** Average is a **representative of a group of numbers** (ya "leader of a group of numbers").

Average ke aur naam: **Mean, Mid value, Ausat**.

---

## 2. Basic Formula

**Average = Sum of Observations / Number of Observations**

### Ex1: 25, 28, 30, 32
- Sum = 115, n = 4 → **115/4 = 28.75**

### Ex2: 35, 25, 20, 30, 46
- Sum = 156, n = 5 → **156/5 = 31.2**

---

## 3. Highway Method (Assumed Average) ⭐

**Idea:** Tooti-footi sadak (numbers) ko **level** karna hai. Tile ki mitti se gaddhe bharne hain, bahar se mitti nahi aayegi. Ek **assumed average** (guess) lo, phir har number ka difference likho, **net change** nikalo aur us ko n se divide karke assumed average me adjust karo.

### Steps
1. Koi bhi value assume karo (jo average ke aas-paas lage).
2. Har number ka assumed se difference (+ / −) likho.
3. Differences ka **net sum** nikalo.
4. **Net sum ÷ n** nikalo → Isko assumed me **add/subtract** karo.

### Ex1: 35, 25, 20, 30, 46 (assume 30)
- Differences: +5, −5, −10, 0, +16
- Net = +6; per number = 6/5 = +1.2
- **Average = 30 + 1.2 = 31.2** ✔

### Ex2: 28, 34, 32, 22, 25 (assume 30)
- Differences: −2, +4, +2, −8, −5 → Net = **−9**
- 9/5 = 1.8 → **30 − 1.8 = 28.2** ✔
- (Normal method: sum 141/5 = 28.2 ✔)

**Note:** Assume kuch bhi karo (28, 30, 25), answer **hamesha same** aayega.

---

## 4. Jab Gap SAME ho (Equal Difference)

Agar numbers ke beech ka **gap barabar** ho (AP), to:

- **Average = Middle value** (agar odd count)
- **Average = (First + Last)/2** (kisi bhi count me)

### Ex1: 12, 14, 16, 18, 20, 22 (gap 2)
- (12 + 22)/2 = **17** ✔

### Ex2: 224, 227, 230, 233, 236 (gap 3)
- Middle = **230** ✔

### Ex3: 88, 92, 96, 100 (sort karke)
- (88 + 100)/2 = **94** ✔
- **Dhyan:** Pehle **increasing order** me likho, tab hi middle/first-last trick lagti hai.

### Ex4: 14 aur 100 ke beech 9 ke multiples ka average
- Multiples: 18, 27, ..., 99 (gap 9, same)
- (18 + 99)/2 = 117/2 = **58.5**

### Ex5: 7 ke multiples (7 aur 55 ke beech, dono exclude)
- 14, 21, 28, 35, 42, 49 → (14 + 49)/2 = **31.5**

### Ex6: Pehle 5 multiples of 5 (5, 10, 15, 20, 25)
- Middle = **15**

### Ex7: Pehle 71 natural numbers (1 se 71)
- (1 + 71)/2 = **36**

---

## 5. Special Sums (Formulas)

| Series | Formula | Example |
|---|---|---|
| 1 + 2 + 3 + … + n | **n(n + 1)/2** | 1…10 = 10 × 11/2 = **55**; 1…100 = **5050** |
| 1² + 2² + … + n² | **n(n + 1)(2n + 1)/6** | n = 10: 10 × 11 × 21/6 = **385** |
| 1³ + 2³ + … + n³ | **[n(n + 1)/2]²** | n = 10: 55² = **3025** |

### Q: 1³, 2³, 3³, 4³, 5³ ka mean
- Sum of cubes = (1 + 2 + 3 + 4 + 5)² = 15² = **225**
- Mean = 225/5 = **45**

**Trap:** Beech wali value (3³ = 27) ko average maan lena **galat** hai, kyunki cubes ka gap same nahi hai.

---

## 6. Properties of Average ⭐

Agar sab numbers me:
- **a add** karo → average me bhi **a add**
- **a subtract** karo → average me bhi **a subtract**
- **a se multiply** karo → average ko bhi **a se multiply**
- **a se divide** karo → average ko bhi **a se divide**

**Example:** 20, 22, 24, 26, 28 (avg 24)
- Sab me +5 → 25, 27, 29, 31, 33 → avg = **29** (24 + 5)
- Sab me −3 → 17, 19, 21, 23, 25 → avg = **21** (24 − 3)

---

## 7. Average se Sum nikalna

**Sum = Average × Number of Observations**

- 8 numbers, avg 50 → Sum = **400**
- 12 numbers, avg 24 → Sum = **288**
- 5 numbers (44, 45, 46, 47, 48): avg 46 → Sum = 46 × 5 = **230**

> Ye formula "Sum/n" se bhi **zyada important** hai. Aage ke zyadatar questions isi par based hain.

---

## 8. Solved Basic Questions

### Q1: 3, 8, 9, x ka average 6. x = ?
- Sum = 6 × 4 = 24
- 3 + 8 + 9 + x = 24 → 20 + x = 24 → **x = 4**

### Q2: 17, 2, 5, x, y ka average 8. x = 4 to y = ?
- Sum = 8 × 5 = 40
- 17 + 2 + 5 = 24 → x + y = 16 → y = 16 − 4 = **12**

### Q3: Pehli 5 consecutive numbers ka avg 30. Sabse bada?
- Middle = 30 → numbers 28, 29, 30, 31, 32 → **32**

---

## 9. Combined Average (Do Groups ka)

### Q: 10 students ka avg 20 aur 8 students ka avg 25. Combined avg?
- Total = 10 × 20 + 8 × 25 = 200 + 200 = **400**; n = 18 → **400/18 = 22.22**

### **Ratio Shortcut:** Number of persons ka **ratio** pehle simplify karo.
- 10 : 8 = **5 : 4**
- Combined = (5 × 20 + 4 × 25)/9 = (100 + 100)/9 = **200/9 = 22.22** ✔

### Q: 48 students ka avg 92, 96 students ka avg 108. Combined?
- Ratio 48 : 96 = **1 : 2**
- Combined = (1 × 92 + 2 × 108)/3 = (92 + 216)/3 = **308/3**

**Lesson:** Actual number of students (48, 96) ki zaroorat nahi, **sirf ratio** chahiye.

### Q: 80 boys ka avg 12, 40 boys avg 13, 50 boys avg 14, 50 boys avg 15. Overall?
- Ratio 80 : 40 : 50 : 50 = **8 : 4 : 5 : 5** (÷10)
- Sum = 8 × 12 + 4 × 13 + 5 × 14 + 5 × 15 = 96 + 52 + 70 + 75 = **293**
- Total ratio = 22 → **293/22**

---

## 10. Consecutive Numbers

### 10.1 NCERT Approach (Basic)

- 5 consecutive: x, x + 1, x + 2, x + 3, x + 4
- 6 consecutive even: x, x + 2, x + 4, x + 6, x + 8, x + 10
- 6 consecutive odd: x, x + 2, ..., x + 10 (**even aur odd ki series same banti hai**; x ki value decide karti hai even/odd)

### 10.2 Competitive Approach (Chair method)

Utni chairs (positions) khali karo jitne numbers hain. Average **beech** me baithta hai.

### Q1: 5 consecutive numbers ka avg 30. Largest?
- 5 chairs; beech = 30; 28, 29, **30**, 31, 32 → **32**

### Q2: 6 consecutive even numbers ka avg 31. Largest?
- 6 chairs; beech me **31** (do chairs ke beech, chair par nahi baithta)
- Even numbers: 26, 28, 30, | 32, 34, 36
- Largest = **36**

### Q3: 6 consecutive odd numbers ka avg 28. Largest?
- Beech me 28 (do chairs ke beech): 23, 25, 27 | 29, 31, 33
- Largest = **33**

### Q4: 5 consecutive odd numbers ka avg 29. Largest?
- Beech me 29 (chair par): 25, 27, **29**, 31, 33 → **33**

**Shortcut:** n consecutive same-gap numbers ka avg = middle. Chhote se bade tak gap g se chalo.

---

## 11. Ratio-based Questions

### Q: 3 numbers me pehla doosre ka double aur teesre ka aadha hai. Avg 56. Pehle aur teesre ka difference?
- Pehla = 2 × Doosra aur Pehla = Teesra/2
- Maan lo Doosra : Pehla : Teesra = **1 : 2 : 4**
- Sum = 7x = 56 × 3 = 168 → **x = 24**
- Pehla = 2x = 48, Teesra = 4x = 96 → Difference = **48** (= 2x)

---

## 12. Partial Averages Diye Ho, Ek Value Nikalo

**Idea:** Sum = Avg × n. Total me se jitne parts diye hain unka sum ghata do.

### Q1: 9 observations ka avg 87. Pehle 5 ka avg 79, agle 3 ka avg 92. 9th number?
- Total = 87 × 9 = **783**
- First 5 = 79 × 5 = **395**
- Next 3 = 92 × 3 = **276**
- 9th = 783 − 395 − 276 = **112**

### Highway Method se (same question):
- Total avg = 87 (highway)
- First 5: 79 − 87 = **−8** (5 numbers) → −40
- Next 3: 92 − 87 = **+5** (3 numbers) → +15
- Net so far = −25 → 9th number ko **+25** hona hoga → **87 + 25 = 112** ✔

### Q2: 7 observations ka avg 34. Pehle 3 ka avg 28, aakhri 2 ka avg 47. Beech ke 2 ka sum?
- Total = 34 × 7 = 238
- First 3 = 84; last 2 = 94
- Middle 2 = 238 − 84 − 94 = **60**

### Q3: 4 numbers me pehle 3 ka avg 16, aakhri 3 ka avg 15. Aakhri number 20. Pehla number?
- a + b + c = 48; b + c + d = 45
- Subtract: a − d = 3
- d = 20 → **a = 23**

### Q4: 12 data ka avg 30. Inme se 8 ka avg 15. Baaki 4 ka avg?
- Total = 360; 8 ka sum = 120
- Baaki 4 ka sum = 240 → avg = **60**

### Q5: 16 students ka avg 100 cm. Pehle 6 ka avg 70, aakhri 8 ka avg 75. Beech ke 2 ka avg?
- Total = 1600; first 6 = 420; last 8 = 600
- Beech 2 ka sum = 1600 − 1020 = 580 → avg = **290**

### Q6: A to I (9 numbers). Overall avg 87, A–E avg 79, F–H avg 92. I?
(Same as Q1 → **112**)

### Q7: 7 observations ka avg 34. Pehle 3 ka avg 28, aakhri 2 ka avg 47. Beech ka sum?
(Same as Q2 → **60**)

---

## 13. Entry–Exit Approach ⭐

**Idea:** Jab koi **join** kare ya **chhode**, to average me jo change aata hai wo us naye/purane person ke **extra/less weight** ki wajah se hota hai.

### Core concept
- Ek naya aadmi aata hai aur average **+d** ho jata hai → Naya aadmi **sabko d-d** baant raha hai → Uske paas **extra = (total persons) × d** tha.
- Isliye: **New person = Old person (jo gaya) + (n × d)**

### Q1: 50 students me se ek (20 kg) chala gaya, naya aaya, avg 0.5 kg badh gaya. Naye ka weight?
- Naya student sabko 0.5 kg baant raha hai → 50 × 0.5 = **25 kg extra**
- Naya = 20 + 25 = **45 kg**

### Q2: 34 students ka avg weight 42 kg. Teacher ko include karne par avg 1 kg badha. Teacher ka weight?
- People = 35, new avg = 43
- Entry–Exit: Teacher = (34 × 1) + 43 = **77 kg**
  (Ya: 35 × 43 − 34 × 42 = 1505 − 1428 = 77 ✔)

### Q3: 15 members ka avg 60 kg. Teen new log (A, B, C) aaye, avg 65 ho gaya. A:B:C = 3:4:2. A aur C ke weight ka difference?
- Method 1: Total (15) = 900; total (18) = 18 × 65 = 1170 → Teen naye ka sum = **270**
- Method 2 (Entry-Exit): (15 × 5) + (3 × 65) = 75 + 195 = **270** ✔
- Ratio 3 : 4 : 2 → total 9 units = 270 → **1 unit = 30 kg**
- A − C = (3 − 2) × 30 = **30 kg**

### Q4: 25 bachhon ka avg height 14 (units). 5 bachhe chale gaye, avg 16 ho gaya. Gaye hue 5 ka avg?
- Total (25) = 350; Remaining 20 → 20 × 16 = 320
- Gaye 5 ka sum = 30 → avg = **6**

### Q5: Jab average ka change dono taraf negative ho
(Jaise Q: 64 innings, 2 hataane par) → "−" aur "−" ko **plus** lo.

---

## 14. Wrong Number se Correct Average

**Formula:** **Correct avg = Wrong avg ± (Difference / n)**

### Q1: 10 numbers ka avg 50. Galti se 54 likha tha, sahi 45. Correct avg?
- Wrong number zyada tha (54 vs 45) → Difference = 9 → average kam hoga
- 9/10 = 0.9 → **50 − 0.9 = 49.1**

### Q2: 40 students ka avg 68. Do marks galti se 48 aur 64 likhe gaye, sahi 84 aur 46. Correct avg?
- Wrong sum = 48 + 64 = 112; Correct sum = 84 + 46 = 130
- Difference = 18 (sahi zyada) → avg badhega
- 18/40 = 0.45 → **68 + 0.45 = 68.45**

---

## 15. Cricket & Bowling Average

### 15.1 Batting

**Q:** Batsman ka 11 innings tak avg x tha. 12th inning me 100 run bane aur avg 5 kam ho gaya. New average?
- Entry–Exit: 12th inning = new person (score 100)
- 11 × (−5) + new avg = 100? Use: Sum equation:
- 11x + 100 = 12(x − 5) → 11x + 100 = 12x − 60 → **x = 160**
- New avg = 160 − 5 = **155**

### 15.2 Remove / Exclude

**Q:** 64 innings ka avg 62. Max aur min score ka difference 200. In dono ko hata do to avg 60. Max score?
- Total = 64 × 62 = 3968
- Remaining = 62 innings × 60 = 3720
- Removed (max + min) = 3968 − 3720 = **248**
- Max − Min = 200
- Max = (248 + 200)/2 = **224**

### 15.3 Bowling Average (Alligation)

**Bowling avg = Runs given per wicket**

**Q:** Bowler ka avg 11 runs/wicket. Agle match me 7 wickets sirf 42 runs me. Avg 1 kam ho gaya. Total wickets?
- Naye match ka avg = 42/7 = **6**
- Naya overall avg = 11 − 1 = **10**
- Alligation (wickets ka ratio, kyunki wicket "weight" hai):
  - Purane avg (11) se: 11 − 10 = **1**
  - Naye avg (6) se: 10 − 6 = **4**
  - Old wickets : New wickets = **4 : 1**
- New = 7 wickets → Old = **28**
- Total = 28 + 7 = **35 wickets**

(Equation: (11w + 42)/(w + 7) = 10 → w = 28 ✔)

---

## 16. Mains-Level Questions

### Q1: 5 students P, Q, R, S, T. P, Q, R, S, T ka avg (x+6). R aur T ka avg (x−6). U aur add hone par avg 5 kam. P, Q, S, U ka avg 94.5. x = ?
- 6 persons ka avg = (x + 6) − 5 = **x + 1** → Total = 6(x + 1)
- R + T = 2(x − 6)
- P + Q + S + U = 94.5 × 4 = **378**
- P + Q + S + U = Total(6) − (R + T) = 6x + 6 − (2x − 12) = 4x + 18
- 4x + 18 = 378 → 4x = 360 → **x = 90**

### Q2: Delhi ka temperature. Mon–Thu avg 52. Tue–Fri avg 55. Mon:Fri = 5 : 7. Friday ka temp?
- Mon + Tue + Wed + Thu = 52 × 4 = **208**
- Tue + Wed + Thu + Fri = 55 × 4 = **220**
- Subtract: Fri − Mon = **12**
- Ratio 5 : 7 → 2x = 12 → x = 6
- **Friday = 7x = 42**

---

## 17. Quick Revision Cheat-Sheet

| Topic | Key Trick |
|---|---|
| Average | Sum / n |
| Sum | Avg × n |
| Gap same | Middle ya (First + Last)/2 |
| Combined avg | Persons ka ratio use karo |
| Highway | Assume → differences → net/n |
| 1 + 2 + … + n | n(n + 1)/2 |
| Sum of cubes | [n(n + 1)/2]² |
| Sum of squares | n(n + 1)(2n + 1)/6 |
| Properties | +a, −a, ×a, ÷a avg par bhi |
| New person joins | New = Old + (n × avg change) |
| Wrong number | ±(Difference/n) |
| Remove items | Total − Remaining = Removed |
| Bowling avg | Alligation on wickets |
| Consecutive | Chairs method |

---

## 18. Common Mistakes

1. **Cubes/squares me beech wali value ko average maan lena** (gap same nahi).
2. **Numbers sorted na karke middle trick lagana.**
3. **Combined avg me simple avg lena** (persons ke weights ignore karna).
4. **Even/odd ki series alag samajhna** — dono ki NCERT series same hoti hai.
5. **Entry–Exit me n galat lena** (naye ke baad total persons).
6. **Wrong-number question me sign galat** — sahi value zyada ho to avg badhega, kam ho to ghatega.
7. **"Remove 2 innings" me 64 ki jagah 62 se multiply** — remaining count dhyan se lo.
8. **Bowling avg me runs par ratio** — wickets par lagana hota hai.

---

## Study Tips (Sir ki advice)

- **Basic aur Highway method** dono seekho; question dekh kar jo fit baithe use karo.
- **"Sum = Avg × n"** sabse zyada use hone wala formula hai.
- Fractions/ratio se **calculation chhoti** karne ki practice karo.
- Pehle khud try karo, phir solution dekho.

*All the best! 🎯*
