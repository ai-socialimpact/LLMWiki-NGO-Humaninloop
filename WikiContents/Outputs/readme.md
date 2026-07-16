
# Sample output

---

## 📋 Table of Contents
1. [Diet Chart for 8 Months Pregnancy](#1-diet-chart-for-8-months-pregnancy)
2. [Immediate Care for Lower Abdominal Pain](#2-immediate-care-for-lower-abdominal-pain)
3. [Calcium & Iron Supplement Guidelines](#3-calcium--iron-supplement-guidelines)

---

### 1. Diet Chart for 8 Months Pregnancy

* **User Query:** `8 months pregnancy diet chart do`

#### 💬 Verbatim   Answer
> "Aapko 8 mahine ki pregnancy mein kuch extra khana chahiye:
> - Har din 350 extra calories aur 18 grams protein lena zaroori hai. [Source: PNC nutrition and anemia.md]
> - Ek extra meal apne regular diet ke saath khayein. [Source: Essential Nutrients for A Pregnant Woman.md]
> - 4-5 chhoti meals aur healthy snacks din bhar mein lein. [Source: Essential Nutrients for A Pregnant Woman.md]
> - Iron aur Folic Acid ki goliya lena na bhulein. [Source: PNC nutrition and anemia.md]"

#### ⚙️  Wiki Thinking
* **Translation:** User requests an 8-month pregnancy diet plan.
* **Intent & Protocol:** Classified under `lifestyle_nutrition`. Because a milestone ("8 months / third trimester") is explicitly mentioned, the system activates chronological routing.
* **File Selection:** Shortlists and approves `maternal_care_trimester_3_and_birth_prep.md` with no negative exclusions applied.

---

### 2. Immediate Care for Lower Abdominal Pain

* **User Query:** `pregnancy me pet k nichle hisse me dard kyun hota hai`

#### 💬 Verbatim   Answer
> "Pet ke nichle hisse me dard pregnancy ke dauran ek danger sign ho sakta hai. Ye severe abdominal pain kehlata hai aur iske liye turant doctor se sampark karna chahiye. [Source: Ante natal care document.md]"

#### ⚙️   Wiki Thinking
* **Translation:** User asks about the cause of lower abdominal pain during pregnancy.
* **Intent & Protocol:** Identified as an acute severity or high-alert symptom (`Symptoms/Emergencies`). This automatically triggers a `TRIGGER_ACUTE_REDIRECTION_MANDATE`.
* **File Selection:** System maps keywords to "severe abdominal pain" and "pregnancy emergency", bypassing standard pools to route directly to `maternal_danger_signs_and_emergencies.md`.

---

### 3. Calcium & Iron Supplement Guidelines

* **User Query:** `calcium ki dawai kab leni chahiye or kya isse iron wali dawai k sath le sakti hu?`

#### 💬 Verbatim   Answer
> "Calcium ki dawai din mein do baar khana khane ke baad pani ke sath leni chahiye. Iron wali dawai ke sath calcium ki dawai nahi leni chahiye, kyunki dono ek sath lene se asar kam ho sakta hai. [Source: Ante natal care document.md]"

#### ⚙️  Wiki Thinking
* **Translation:** User wants to know when to take calcium medicine and if it can be combined with iron pills.
* **Intent & Protocol:** Falls under routine maternal care and supplementation (`lifestyle_nutrition`). No specific milestone marker is specified, so generic chronological pooling is utilized.
* **File Selection:** Reaches across overlapping indices to extract data from `maternal_care_trimester_2.md`, `maternal_care_trimester_3_and_birth_prep.md`, and `maternal_postpartum_care_and_nutrition.md`.

---
 
